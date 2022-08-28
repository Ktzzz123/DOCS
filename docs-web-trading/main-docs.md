# Sumary
Curent Version: 0.0.1
Change log: 

| Index | Date | Version | Note | PIC |
| --- | --- | --- | --- | --- |
| 1 | 27/08/2022 | 0.0.1 | Init Document <br> Folder Structure for documents <br> Docs rules | Dũng & Tiên |
| 2 |  |  |  | |
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
	- [ ] Login - Register
	- [ ] Tradingview

2. **Pages - Service (From Menu)**

	***Market Info***
	- [ ] Market View
	- [x] [Market Cap](Pages/Market%20Cap/market-cap-layout.md)
	- [ ] Market Foreigner 
	- [ ] News - Events

	***Stock Transaction***
	- [ ] Order 
	- [ ] Dublicate Order
	- [ ] Take Profits - Stop Loss Order
	- [ ] Regular Invesment
	- [ ] Alert
	- [ ] Order History
	- [ ] Right Informations
	- [ ] Expected right on Portfolio
	- [ ] Internal Stock Transfer
	- [ ] Rights to buy
	- [ ] Advertis Order
	
	***Cash Transaction***
	- [ ] Deposit inform 
	- [ ] Online Banking (BIDV)
	- [ ] Internal Transfer
	- [ ] Cash in Advanced
	- [ ] Widthdrawal Request
	
	***Portfolio Management***
	- [ ] Portfolio 
	- [ ] Profit loss caculator
	- [ ] Margin Extension
	- [ ] Margin Repayment
	- [ ] Performance
	- [ ] Statement
	- [ ] Confirm your Order
	
	***SSV Service***
	- [ ] Research Center
	- [ ] Registation of Selling Oddlot
	- [ ] Advisory
	
3. **Others Services (Features)** 
	- [ ] Quick Order
	- [ ] Feedback
	- [ ] Account Settings
		- [ ] Account Infomation
		- [ ] Change Login Password
		- [ ] Change Trading Password
		- [ ] Forgot Trading Password
		- [ ] Bank Account Management
	- [ ] Config System 
		- [ ] Config Price/Unit
		- [ ] Config Session
		- [ ] Config Hotkey 


---



