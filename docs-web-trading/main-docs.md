# Sumary
Curent Version: 0.0.1
Change log: 

| Index | Date | Version | Note | PIC |
| --- | --- | --- | --- | --- |
| 1 | 27/08/2022 | 0.0.1 | Init Document <br> Folder Structure for documents <br> Docs rules | Dũng & Tiên |
| 2 | 31/08/2022 | 0.0.2 | Stock Transaction <br> Cash Transaction <br> Portfolio Management <br> SSV Service | Tien|
| 3 |  |  |  | |
| 4 |  |  |  | |

---
# Folder Structure
- [ ] Project Structure
	- [ ] Components
	- [ ] Views/Pages
	- [ ] Constants
- [ ] CSS Structure
- [ ] Assets Structure
- [ ] Plugins/Tools Structure (Eslint, Prettier, Builds Scripts, ... )

---
#  Background Process
Every thing run on background
![10%](https://progress-bar.dev/10?title=Progress)
- [x] [Background Service](#Background%20Service%20Background%20Background%2020Service%20background-service%20md)
- [ ] [Context Store](#Context%20Store)
- [ ] [Global Service](#Global%20Service)
- [ ] [Socket Service](#Socket%20Service)
- [ ] [Control Service](#Control%20Service)

##  [Background Service](Background/Background%20Service/background-service.md)
> Task run on background example: Subcribe common data, get init data for app, Monitor subcribe, ...

## Context Store
> Store common state variable like: theme, colors, applicationConfigs, language, ...
> 
## Global Service
> Store static data, define function that use in all project
> 
## Socket Service
> Establisb socket connection, listen response from server, check and handle simple data before store to Global service ...

## Control Service
> Control Sub/Unsub status
> Control Request status
>
---
# Pages
> View/Pages is describe all UI of product. Separate by route or modal dispatch content. 

1. **Fullpage** 
	- [x] [Homepage - PriceBoard](Pages/HomePage%20-%20Priceboard/homepage-priceboard.md.md)
	- [x] [Login - Register](Pages/Login%20-%20Register/Login%20-%20Register.md)
		- [x] [Login](Pages/Login%20-%20Register/Login/Login.md)
		- [x] [Register](Pages/Login%20-%20Register/Register/Register.md)
	- [ ] Tradingview

2. **Pages - Service (From Menu)**

	***Market Info***
	- [x] [Market View](Pages/Market%20View/market-view.md)
	- [x] [Market Cap](Pages/Market%20Cap/market-cap-layout.md)
	- [x] [Market Foreigner Trade](Pages/Foreginer%20Trade/foreginer-trade.md)
	- [x] [Market Liquidity](Pages/Market%20Liquidity/market-liquidity.md)
	- [x] [News - Events](Pages/News%20-%20Events/News%20-%20Events.md)

	***Stock Transaction***
	- [x] [Order](Pages/Normal%20Oder/normal-order.md)
	- [x] [Take Profits - Stop Loss Order](Pages/Take%20Profit%20and%20Stop%20Loss/TakeProfitAndStopLoss.md)
	- [x]  [Duplicate Order](Pages/Duplicate%20Order/duplicate-order.md)
	- [x] [Regular Investment](Pages/Regular%20Invesment/Regular%20Investment.md)
	- [x] [Alert](Pages/Alert/Alert.md)
	- [x] [Order History](Pages/Order%20history/Order%20History.md)
	- [x] [Right Informations](Pages/Right%20Information/Right%20Informations.md)
	- [x] [Expected right on Portfolio](Pages/Expected%20right%20on%20Portfolio/Expected%20right%20on%20Portfolio.md)
	- [x] [Internal Stock Transfer](Pages/Internal%20Stock%20Transfer/Internal%20Stock%20Transfer.md)
	- [x] [Rights to buy](Pages/Right%20to%20buy/Rights%20to%20buy.md)
	- [x] [Advertise Order](Pages/Advertise%20order/Advertise%20Order.md)
	
	***Cash Transaction***
	- [x] [Deposit Inform](Pages/Deposit%20inform/Deposit-inform.md)
	- [x] [Online Banking (BIDV)](Pages/Online%20Banking%20(BIDV)/Online%20Banking%20(BIDV).md)
	- [x] [Interal Transfer](Pages/Internal%20Transfer/Interal%20Transfer.md)
	- [x] [Pay in Advanced](Pages/Pay%20in%20Advanced/Pay%20in%20Advanced.md)
	- [x] [Withdrawal Request](Pages/Withdrawal%20request/Withdrawal%20Request.md)
	
	***Portfolio Management***
	- [x] [Portfolio](Pages/Portfolio/Portfolio.md)
	- [ ] Profit loss caculator (this section will be restart in the future)
	- [x] [Margin Extension](Pages/Margin%20Extension/Margin%20Extension.md)
	- [x] [Margin Repayment](Pages/Margin%20Repayment/Margin%20Repayment.md)
	- [x] [Performance](Pages/Performance/Performance.md)
	- [x] [Statement](Pages/Statement/Statement.md)
	- [x] [Confirm your Order](Pages/Confirm%20your%20Order/Confirm%20your%20Order.md)
	
	***SSV Service***
	- [x] [User guide](Pages/User%20guide/User%20guide.md)
	- [x] [Margin Stock List](Pages/Margin%20Stock%20List/Margin%20Stock%20List.md)
	- [x] [Research Center](Pages/Research%20Center/Research%20Center.md)
	- [x] [Registration of Selling Odd lot](Pages/Registration%20of%20Selling%20Odd%20lot/Registration%20of%20Selling%20Odd%20lot.md)
	- [x] [Advisory](Pages/Advisory/Advisory.md)
	- [x] [Bank Account Management](Pages/Bank%20Account%20Management/Bank%20Account%20Management.md)
1. **Others Services (Features)** 
	- [x] [Quick Order](Pages/Quick%20Order/Quick%20Order.md)
	- [x] [Feedback](Pages/Feedback/Feedback.md)
	- [x] [Account settings](Pages/Account%20Settings/Account%20settings.md)
		- [x] [Account Information](Pages/Account%20Information/Account%20Information.md)
		- [x] [Change Login Password](Pages/Change%20Login%20Password/Change%20Login%20Password.md)
		- [x] [Change Trading Password](Pages/Change%20Trading%20Password/Change%20Trading%20Password.md)
		- [x] [Forgot Trading Password](Pages/Forgot%20Trading%20Password/Forgot%20Trading%20Password.md)
	
	- [ ] Config System 
		- [ ] Config Price/Unit
		- [ ] Config Session
		- [ ] Config Hotkey 


---



