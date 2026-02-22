## Repository File Overview:

### 1.Bill.txt: 
This is the text file in which we are generating the bill from the code present in project file .
---
### 2.Python assessment: 
This is the python assessment file containing questions on every topic. 
---
### 3.lc_lambda file: 
This the the file containing the list comprehension and lambda questions
---
### 4.project file: In this I have created 2 projects first is Hotel Billing and second is College Fees Calculation. 

#### Hotel Billing Project: 
I have created 4 class:<br>

➜DatabaseConnection : In this I have created 1 method i.e create connection to connect python with SQL Server DB <br>
➜MenuOrder : Here I have inherited DatabaseConnection class so that it can use method of that class. Here I have created one method DisplayMenuTakeOrder in which I have taken the menu from customer and store the details in dictionary <br>
➜OrderDB : In this class I have inherited MenuOrder class and created one method OrderDisplay to insert the orders stored in the dictionary to the Orders table present in SQL Server DB.<br>
➜Billing : In this class I have inherited OrderDB class and 2 methods i.e GenerateBill which displays the bill on console .Then PrintBillFile method saves the bill to the text file

#### In College Fee Calculation project: 
I have created 4 class:<br>

➜DatabaseConnection : in this i have created 1 method i.e create connection to connect python with SQL Server DB<br>
➜CollegeInput : Here I have inherited DatabaseConnection class so that it can use method of that class. I have created 3 method first is constructor method ,take_input method to take the input from user, calculate_fees to calculate the college fee of student and stored the details to the dictionary.<br>
➜FeeDB: Here I have inherited CollegeInput class and one method store_fee to insert the data to CollegeFees table in the DB.<br>
➜FeeBilling: I have inherited FeeDB and created method generate_bill to display the bill on console.<br>
