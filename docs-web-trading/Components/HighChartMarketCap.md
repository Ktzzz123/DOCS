![[HighChartMarketCap.png]]
==[link code](\src\views\MarketCap\ChartMarketCap\index.js)==
- SetInterval to convert data every 10 seconds.
- SubScribe to server to get data of stock
	- call convertData TreeMap to update data to chart table
- Render chart