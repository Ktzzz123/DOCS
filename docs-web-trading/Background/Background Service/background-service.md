

# Task and Functions



# Details

- System will check hotkeys, set language, set notification settings.
	- Register device to OneSignal
	- Listening notification messages
	- Reading config.js file
		- Calling `setConfigNodeServer` function to set websocket server info.
		- Calling subscribe method to listen event.
			- If client connected server, call checkVersionStockList to load list of stocks in each stock exchanges.
			- If event listened was `CHANGE_CONFIG_HOTKEY`, reassign hotkeys
		- After having websocket info, system will create two connections to server. one for stream connection and one for trading connection
				![[Pasted image 20220823143733.png]]
			1. `SetNewConnectionStream`
				- If client connected to server, return and warning
				- Setting up connection: get URL of specific company base on active code saved in global service.
				- connecting to socket server base on URL already got.
				- [socket StartListener Stream](components/socket_StartListener_Stream.md)
			
				==[Link code](altisss\ALT-WebClientV3\src\utils\service\socket_service.js)==
			2. `setNewConnectionTrading`
				- if client connected to server, return and warning
				- Setting up connection: get URL of company base on activeCode in (Global service)
				- Connecting to socket server base on URL.
					- connect to server.
					-  [socket StartListener Trading](components/socket_StartListener_Trading.md)		
		- Saving content for menu bar to global service
		- Reading hotkeys, font family for each company
		- Saving and initializing font family for specific company
	- listen RxJS event. if this is the first time browser connect to server, request list of stocks and info of each stock in each exchange and save it to local data in each type of language
		- Call hanldeDataTradingview function to set trading data
