# AIM
To solve Credit Purchase & Sales tracking
## 📌 IDEA
To create a database for small businesses, because it takes most of their time. Still ends up halfway through.
## 📌 About
Out of many, I choose MS Access. As I know Finance and Accounting, some what of database & structures.
# 📌 Database creation
## 📁 Database structures & table creation
🗂️ Customer(C) : Stores customers detail for repetitive use.<br>
🗂️ Item(I) : Stores product details, mainly those products store trades on.<br>
🗂️ Transaction(T) : Stores customer information, dates, invoice id as it initiates tracking.<br>
🗂️ Transaction detail(TD) : Stores product details purchased or sold.<br>
🗂️ Payment(P) : Stores the payment records, both paid & received.
## 🔗 Relationships: -
🪢 C.Custmer_ID 🔗 T.Custmer_ID: - As the transaction requires customer name.<br>
🪢 C.Custmer_ID 🔗 P.Custmer_ID: - As the payment requires customer name.<br>
🪢 T.Transaction_ID 🔗 TD.Transaction_ID: - As transaction detail requires connection with transaction, because of multiple entries for more than one products.<br>
🪢 I.Item_ID 🔗 TD.Item: - As transaction detail has important column items.
## 🎁 Quarries / Reports: -
🗝️ To summaries and get our report, I quarried in a way that it delivers Date, Transaction ID, Customer Name, Transaction type, Debit, Credit.<br>
🗝️ To get tailored report for a customer within a date range. I created another quarry with a form to enter customer name & date range.<br>

## 👀 Preview
👁️Transaction form
![image alt](https://github.com/pranav2562/Credit_Transaction_Management_System/blob/main/Record.jpg?raw=true)
👁️ Customer Report

![image alt](https://github.com/pranav2562/Credit_Transaction_Management_System/blob/main/Report.jpg?raw=true)

## 🎗️ Outcome: -
🔖 As this project is on Credit Purchase & Sales tracking. There was problem to track the purchase or sales entries and under payment received or paid entries.<br>
🔖 To counter that I created a TYPE column under Transaction Detail and Payment table. The work is simple while entering we need to select purchase or sales under Transaction Detail & received or paid under Payment table.<br>
🔖 There was one more catch the mode of payment; I created another column Mode under Payment table.<br>
🔖 I ended up creating a database for small businesses who enters data as single entry, but as outcomes it becomes double entry. Which is a standard accounting system to record transactions.

