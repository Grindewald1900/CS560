## CS410/560 - Software Engineering
### Assignment 3 G AN
### Group members : Yi Ren (002269013), Wentao Lu (002276355)
### Requirements Engineering
**This exercise is for a simplified supermarket cash register system. The normal procedure
for using the cash register is as follows:
• A customer arrives at the checkout with items to pay.
• The cashier records the identification number of each item, as well as the quantity
if it is greater than one.
• The checkout displays the price of each item and its description.
• When all purchases are recorded, the cashier signals the end of the sale.
• The cash register displays the total purchases.
• The customer chooses his method of payment:
✓ cash: the cashier collects the money received; the cashier indicates the
currency to be returned to the customer;
✓ check: the cashier checks the creditworthiness of the customer by
transmitting a request to an authorization center via the cashier;
✓ credit card: a bank terminal is part of the cash register. It transmits an
authorization request to an authorization center according to the type of
card.
• The cash register registers the sale and prints a receipt.
• The cashier gives the customer the receipt.
After the items have been entered, the customer can present discount coupons for certain
items to the cashier. When payment is completed, the checkout transmits information on
the number of items sold to the inventory management system.
Every morning, the store manager initializes the cashes register for the day.**

**1. Write a detailed use case diagram for the cash register. Feel free to use the use case
relationships to make your diagram more precise.**
<div align=center><img src="http://15.222.11.163/wp-content/uploads/2020/04/userCase--948x1024.png" width="80%" height="80%"></div>
<br></br>

**2. Write an essential detailed description of the main use case: PROCESS
CHECKOUT. (See Textual Use Case Description Example in 7. Modeling with
UML Part 2, slide 10).**
<div align=center><img src="http://15.222.11.163/wp-content/uploads/2020/04/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20200406233923.png" width="50%" height="5%"></div>  
<br></br>
<div align=center><img src="http://15.222.11.163/wp-content/uploads/2020/04/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20200406234034.png" width="50%" height="50%"></div>
<br></br>
<div align=center><img src="http://15.222.11.163/wp-content/uploads/2020/04/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20200406234040.png" width="50%" height="50%"></div>
<br></br>
<div align=center><img src="http://15.222.11.163/wp-content/uploads/2020/04/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20200406234044.png" width="50%" height="50%"></div>
<br></br>
<div align=center><img src="http://15.222.11.163/wp-content/uploads/2020/04/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20200406234047.png" width="50%" height="50%"></div>
<br></br>
<div align=center><img src="http://15.222.11.163/wp-content/uploads/2020/04/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20200406234049.png" width="50%" height="50%"></div>
<br></br>



**3. Write a system sequence diagram that describes the nominal scenario of the
essential use case PROCESS CHECKOUT, considering only cash payment.**
<div align=center><img src="http://15.222.11.163/wp-content/uploads/2020/04/Sq-1024x691.png" width="80%" height="80%"></div>
<br></br>

**4. Show by a state diagram the forced succession of the system operations for the case
of PROCESS CHECKOUT use, always considering only cash payment.**
<div align=center><img src="http://15.222.11.163/wp-content/uploads/2020/04/state1-620x1024.png" width="50%" height="50%"></div>
<br></br>

**5. Expand the diagram in 4) by considering the different types of payment, as well as
the other actions of the cashier**
<div align=center><img src="http://15.222.11.163/wp-content/uploads/2020/04/state2-856x1024.png" width="80%" height="80%"></div>
<br></br>
