![[Table_Foreigner_Trade.png]]
- Subscribe data
- Listen realtime data and handle processing data
- declare dataBuy and dataSell, set value to it
- Call getForeignerData function to:
	- Declare an `InputParams` contain information of tableIsBuy.
	- send request to server contain `GetForeignerData`, `InputParams` and `handleGetHisForeignerTradeData` to store and handle processing data
- Render table