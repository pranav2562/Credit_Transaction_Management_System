# Credit Transaction Management System

## Tables and Forms
Created table Transaction, Transaction detail, Payment, Item, Mode, Customer  <br>
### Transaction Table & Form: <br>
Transaction table is to store Suppliers and Customers details which is linked to the party table <br>
### Transaction detail Table & Sub-form: <br>
Transaction detail table is to store the sold/purchase item which is linked to the item table and added column type to distinguse them between purchase & sales. To distinguish I have used "Purchse" or "Sales" which is backed by a list. <br>
### Payment Table & Sub-form:
Payment table is to store te payment records with customer's name which is linked to customer table. To distinguse them I have used "Paid" & "Receipt" which is backed by a list. To handle the mode of payment I have used drop-down list which is backed by mode table. <br>
### Item Table:
Item table is to store all the item name <br>
### Mode Table:
Mode table is to store all the payment mode <br>
### Customer Table:
Customer table is store all the customer related information <br>
### Report Form:
Report form is used to get the summary of the required customer, under a specific date. <br>
Under this form atached two buttons to view or print the summary of the required customer, under a specific date.

## Quaries & Reports
### Ledger Quary:
For ledger quary I used SQL & Design view to quary and arrange them as double entry system.<br>
To transform them as double entry system I used unions, joins and filter. 
### Report:
Prepare a printable summary for all the transactions, which is backed by ledger quary
