# AccountFinalProject
Project Outline
1. Core Class Definitions:
Account (Abstract Class)
Attributes: account_id, balance, interest
Methods: init, str, and other shared methods (deposit, withdraw)
Checking Class (Inherits Account)
Savings Class (Inherits Account)
Credit Class (Inherits Account)
Additional Attribute: credit_limit
2. Customer Class:
Attributes: username, checking, savings, credit
Methods: str
3. Data Management Functions:
Import Data from CSV:
Create account and customer objects
Store customers in a global list
View Customers:
Display all customers and their accounts
Deposit and Withdrawal Functions:
Implement as methods in Account (not usable by Credit)
Credit Card Transaction Functions:
Charge and payment methods in Credit class
4. Interface Functions:
Menu-driven interface using input()
Functions include: Import, View Customers, Deposit, Withdraw, Credit Card Charge, Credit Card Payment, Exit (Save to CSV)
5. Utilities:
Type checking and exceptions
Lookup function for retrieving Customer objects by username
 
Task Assignments

Khang:
Overview and Coordination:
Ensure that all components integrate seamlessly.
Maintain the master file and repository.
Write the main interface loop and ensure it integrates all components.
Credit Class:
Implement the Credit class with methods for charging and payment.
Ensure type checking and exception handling are robust.

Cassidy:
Account and Derived Classes:
Implement the Account, Checking, and Savings classes.
Include methods for deposits and withdrawals, ensuring that they cannot be used directly by the Credit class.
Data Import Function:
Write the function to import data from CSV, creating appropriate objects and storing them.

Tristan:
Customer Class:
Implement the Customer class with appropriate string formatting and methods.
View Customers and Exit Functions:
Implement the functionality to view all customers and their account details.
Implement the exit function to save current data back to a CSV file.

Collaboration and Tools
Use Git repository.

Deadlines
11:30pm Apr26: Review progress, integrate components, and test the interface.
11:30pm Apr29: Finalize documentation, perform comprehensive testing, and prepare for submission.







![image](https://github.com/hoanglekhang/AccountFinalProject/assets/112513812/69080d05-61aa-423a-8e4b-10d5e75d1b26)
