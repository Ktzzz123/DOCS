- Save data to inputParam, onSuccess, onFailed, reqInfoMap
- if request success (Result = 1),
	- if topic of inputParam incluse 'MDD|Si', setTimeout to multicast data after 100 miliseconds. 
	- Pass data to onSuccess
	- Clear timeout when sub success
- else request error
	- multicast 'SUB-INFO_ERROR'
	- Pass data to onFailed