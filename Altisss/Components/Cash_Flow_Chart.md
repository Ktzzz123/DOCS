![[Cash_Flow_Chart.png]]
- Code of chart and isIndex variables was passed from MarketView component to Cash_Flow_Chart component as a props with the same name.
- Subcribe to listen RxJS event to get data
	- If type of msg is 'BUY_SELL_FLOW' and msgKey equal to code, and activeRef equal to 'T'.
		- If typeChartRef now references to value equal to 'rt', call handleDataRealtime function to get data
		- Else call handleDataAccumulate to get data
	- Call changeActive funtion to get data