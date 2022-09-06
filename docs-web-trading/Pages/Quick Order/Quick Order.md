# Sumary
- Quick order inform
	- Normal order
	- GTC order
	- Reservation order
- Stock information table
	- Order book
	- Buying power
	- Stocks ownership
> Pages includes: [Header](../../Common%20UI/Header.md), [Menu](../../Common%20UI/Menu.md), [Footer](../../Common%20UI/Footer.md) 
# Content
## Quick order inform
### Normal order
**Images:**
![](images/Quick%20order%20inform.png)
**Feature:**
 - User can make normal order(sell or buy) here
 - User can choose sub-account to make order
 - User can choose which stock, price, and quantity to make order
 - User can confirm order by click *sell/buy ...* order button
**Code:**
- UI:
- Logic
### GTC order
**Images:**
![](images/GTC%20order.png)
**Feature:**
> Good 'Til Canceled is order user create with condition to execute If the market price hits the price of the GTC order before expiration, the trade will be executed
 - User can make GTC order(sell or buy) here
 - User can choose sub-account to make order
 - User can choose date to execute GTC order here
 - User can choose which stock, price, and quantity to make order
 - User can confirm order by click *sell/buy ...* order button
**Code:**
- UI:
- Logic
### Reservation order
**Images:**
![](images/Reservation%20order.png)
**Feature:**
> Reservation order is order user reservate an order with given conditons.
> There are four type of reservation orders:
>	**ATO**: named after At The Open, ATO order is an order traded at the matching price to determine the opening price, only applicable to the Ho Chi Minh Stock Exchange(HSX). Orders can be entered into the system before or during a periodic order matching session to determine the opening price. After 9:15, the order is not executed or the rest of the order is not matched and automatically cancelled
>	**Continue morning**:Is a trading method made on the basis of matching buy orders and sell orders as soon as orders are entered into the trading system. Time of order in each exchange is: HSX 9:15’ to 11:30’, HNX and UPCOM 9:00’ to 11:30’ 
>	**Contunue afternoon**: has similar properties to the **Continue morning** order. but time of order in each exchange is: HSX 13:00’ to 14:30’, HNX and UPCOM 13:00’ to 15:00’ 
>	**ATC**: named after At The Close, has similar properties to the ATO order, but to determine the closing price at 14:45. The ATC order is used on both Ho Chi Minh(HSX) and Hanoi(HNX) exchanges.
- User can make ATO, Continue morning, Contunue afternoon, ATC order in here
- User can choose sub-account to make order
- User choose which stock, price and quantity of order
- User choose period of time of order
- User  confirm order by click *sell/buy ...* button 
**Code:**
- UI:
- Logic
## Stock information table

### Order book
**Images:**
![](images/Order%20book%201.png)
**Feature:**
- Show list of order of user 
- User can click *Cancel* button to cancel order
- User can edit order by click *Edit* button
**Code:**
- UI:
- Logic
### Buying power
**Images:**
![](images/Buying%20power.png)
**Feature:**
- Show buy power of sub-account include amount of sub-account
**Code:**
- UI:
- Logic
### Stocks ownership
**Images:**
![](images/Stock%20owndership.png)
**Feature:**
- Show list of stock that sub-account own
- User can click *Sell* button to sell that stock
**Code:**
- UI:
- Logic