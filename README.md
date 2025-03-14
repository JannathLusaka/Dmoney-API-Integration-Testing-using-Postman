# About d-money project
D-money is a transactional system where user can send money, payment and transaction.In this project I have created a postman
collection based on test cases created from the following scenarios:
- Admin creates an Agent, 2 random Customers, and a Merchant.
- Deposit some money from the SYSTEM account to the Agent.
- System account: SYSTEM (range 10 TK to 10,000 TK)
- Agent deposits money to one of the Customers.
- Check the Agent's balance.
- Then, send money from one Customer to another Customer.
- Withdraw any amount from a Customer to the Agent (range 10 TK to 10,000 TK).
- Check the Customer's balance and transaction statement by trnxId.
- Make a payment from the second Customer to the Merchant.
- The second Customer checks both balance and transaction statement.
- The Merchant checks his balance.
Then I generated a Newman report.

# Technology used:
- postman
- newman
- nodejs

# How to run?
- Clone this project
- PUT .env file
- Give following command:
- ``` npm i ```
- ``` npm test```

# User Documentation:
https://documenter.getpostman.com/view/39824465/2sAYBVis3J

# Test Case Report:
https://docs.google.com/spreadsheets/d/1e-B2oNLjTaxlMytzavlPLEdj20SvSYSA/edit?usp=drive_link&ouid=105813272865639316259&rtpof=true&sd=true

# Bug Report:
https://docs.google.com/spreadsheets/d/1p6IHxP9gLZOn_eeHttBs66k6nyXmsRCh/edit?usp=drive_link&ouid=105813272865639316259&rtpof=true&sd=true

# Report: 
![NewmanReport1](https://github.com/user-attachments/assets/8985e410-5d7e-472f-95ec-16ee52d50117)
![NewmanReport2](https://github.com/user-attachments/assets/7ad41639-8a6e-47be-a39e-f2641e2869ee)
![Newman1](https://github.com/user-attachments/assets/3af0d567-07d9-41e8-9341-4d1c99a00f4e)



