# About DMoney REST API Testing Project
D-Money is a demo financial project that simulates fake money transfers. I automated key API functionalities such as user login, user creation, money deposit, withdrawal, sending money, and payments using Postman and Newman. All test cases were written manually, and a Newman report was generated to track API test results. Any issues found during testing were documented in a bug report. This project helped ensure the reliability and correctness of the D-Money API.
## Test Case Scenerio
1.  Admin creates an Agent, 2 random Customers, and a Merchant.
1.  Admin email: admin@roadtocareer.net / Pass: 1234
1.  Deposit some money from the SYSTEM account to the Agent.
1.  System account: SYSTEM (range 10 TK to 10,000 TK)
1.  Agent deposits money to one of the Customers.
1.  Check the Agent's balance.
1.  Then, send money from one Customer to another Customer.(Hint: fromAc: Customer, toAc: Customer)
1.  Withdraw any amount from a Customer to the Agent (range 10 TK to 10,000 TK).
1.  Check the Customer's balance and transaction statement by trnxId.
1.  Make a payment from the second Customer to the Merchant.
1.  The second Customer checks both balance and transaction statement.
1.  The Merchant checks his balance.

## Tools & Technology used:
- Postman
- Newman
## How to Run This Project
- clone this project
- Open with any code editor
- Give following command
  
  ` npm i `

   ` node .\report.js`

## Test Cases for the Project
  [Click to view the Test Case](https://docs.google.com/spreadsheets/d/18nXleDQE4QTW-3-rAbkzLa38XaCrCR0M1AbbCQm-JYs/edit?usp=sharing)
## Bug Report for the Project
  [Click to view the Bug Report](https://docs.google.com/spreadsheets/d/1KS6V5ZrDTt26Ch4FFu3WpP8Xv3k9G_4V11qt4hXTorM/edit?usp=sharing)
  
  
