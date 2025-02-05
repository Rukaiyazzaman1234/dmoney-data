# About dmoney-data

DMoney-Data is a comprehensive transactional and user management system designed to facilitate financial interactions among different user roles: admin, agents, customers, and merchants.

# Key Features:

User Creation: Admin can create agents, multiple customers, and merchants.

Transaction Types:
* Customers can send money to each other.
* Agents can transfer funds to customers and merchants.
* Customers can withdraw money from their accounts and make payments to merchants.
* Agents can deposit funds into customers' accounts.
* Balance and Statement Access: Agents, customers, and merchants can check their account balances and transaction statements.
Security Measures:

* Invalid login attempts for admin and users are not permitted.
* Transactions require valid information and sufficient balance to be processed successfully.
* This structured system ensures efficient and secure financial transactions among users while providing robust management capabilities for administrators.



# Technology used:
- Postman
- Newman
- Visual studio code
- node.js
- git

# How to run?
- Clone this project
- Make folder and open that folder with visual studio code
- Export .env file in that folder
- Give following command:
- npm init -y
- npm i newman
- npx run newman(add here the dmoney-data project share link) .\env.js
- make report.js and make a foler with name Reports
- In that reports folder have to make a html
- html file will create by .\report.js , which will show the newman report


# User documentation:
https://documenter.getpostman.com/view/39880661/2sAYBYe9uH


# Newman Report:
![image](https://github.com/user-attachments/assets/ea0b1147-9116-43e6-a014-4a51c7e71c62)
![image](https://github.com/user-attachments/assets/d11c5b8e-d66d-401a-8cc0-0970763825cb)

# API Bug Report:
https://docs.google.com/spreadsheets/d/1xSOxVyea6Kq04kYMbffKR53c8ZQnVk5nwQ9znKiZ6h0/edit?usp=sharing

# Test Case:
https://docs.google.com/spreadsheets/d/1iWAQXCR2nKHDD6SoHXI1Dm6sf7aqeo1yoqQ007JPaN0/edit?usp=sharing
