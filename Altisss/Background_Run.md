0. background run
	1. 
	- system check hotkeys, set language, set notification setting first, and read config.js file. 
	- call setConfigNodeServer function to set websocket server info.
	- After have websocket info, system will create two connections to server. one for stream connection and one for trading connection
![[Pasted image 20220823143733.png]]
		1. SetNewConnectionStream
			- If client connected to server, return and warning
			- Set up connection: get URL of each company base on active code saved in global service.
			- connect to socket server base on URL already got.
[Link code](altisss\ALT-WebClientV3\src\utils\service\socket_service.js)
		1. setNewConnectionTrading
			- 
	- get content for menu bar to global service
	- read hotkeys, font family for each company
	2. listen RxJS event. if this is the first time connect to server, request list of stocks and info of each stock in each exchanges and save it to local data in each type of language
	[App.js](altisss\ALT-WebClientV3\src\App.js)
	