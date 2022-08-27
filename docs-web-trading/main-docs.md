

# 1. Background Process
Every thing run on background
- [x] Backgroud Service: [[#1 1 Background Service background_process md]]
- [ ] Context Store [[#1 2 Context Store]]
- [ ] Global Service [[#1 3 Global Service]] 
- [ ] Socket Service [[#1 4 Socket Service]]
- [ ] Control Service [[#1 5 Control Service]]

## 1.1. [Background Service](background_process.md)
> Task run on background example: Subcribe common data, get init data for app, Monitor subcribe, ...

## 1.2. Context Store
> Store common state variable like: theme, colors, applicationConfigs, language, ...
> 
## 1.3. Global Service
> Store static data, define function that use in all project
> 
## 1.4. Socket Service
> Establisb socket connection, listen response from server, check and handle simple data before store to Global service ...

## 1.5. Control Service
> Control Sub/Unsub status
> Control Request status
>
---
# 2. Pages
> View/Pages is describe all UI of product. Separate by route or modal dispatch content. 

1. **Fullpage** 
	- [ ] Homepage - Priceboard
	- [ ] Login - Register
	- [ ] Tradingview

2. **Pages - Service (From Menu)**

	***Market Info***
	- [ ] Market View
	- [ ] Market Cap
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
## 2.1. Homepage - Priceboard
- [Header.md](Header.md)
- [Menu](Menu.md)
- [Chart Index](Chart_Index.md)
    - [Table Index Overview](Table_Index_Overview.md)
    - [Table PriceBoard](Table_PriceBoard.md)
- [Footer](Footer.md)
- [PriceBoard_Content](PriceBoard_Content.md)



