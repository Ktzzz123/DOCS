![[Cash_flow_history.png]]
- Code of chart and isIndex was passed as props with the same name.
- Set data to a null array
- Create an InputParams contain 'NET_FLOW', '5', code value
- sendRequest to get history cash flow with InputParams and two functions: getHistoryCashFlowResult, getHistoryCashFlowTimeout.
- [getHistoryCashFlowResult](getHistoryCashFlowResult.md)