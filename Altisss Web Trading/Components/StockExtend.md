![[StockExtend.png]]
==[Code link](src\views\NormalOrder\index.js)==
stockCode, component, levelSize was passed from parent component.
-  If `stickCode` exist and `glb_sv.StockMarket[stockCode]` exist
	- Call getHist method to subscibe to server
	- Function stockExtendEvent call subscribe method to sen subscribe request to server
	- 
