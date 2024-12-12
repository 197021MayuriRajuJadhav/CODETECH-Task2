Name: Mayuri Raju Jadhav
Company: CODETECH IT SOLUTION
ID:CT08DS10153
Domain:Java Programming
Duration: november to december 2024

# CODETECH-Task2
Description of the Program
This program implements a Java-based Online Banking System that simulates core banking functionalities. The system is designed to allow users to:

Create Accounts:

Users can create an account with a unique account number and account holder name.
Deposit Funds:

Allows users to deposit money into their account.
Ensures that the deposit amount is valid.
Withdraw Funds:

Users can withdraw money from their account.
Ensures sufficient balance and valid withdrawal amounts.
Transfer Funds:

Facilitates money transfers between two accounts.
Checks for sufficient funds and valid account details.
View Account Details:

Displays the account number, account holder's name, and the current balance.
View Transaction History:

Provides a detailed log of all transactions (deposits, withdrawals, and transfers) for the account.
Update Account Holder Name:

Enables users to update the name associated with their account.
Exit the System:

Gracefully exits the program.
Features
Object-Oriented Design:

The Account class encapsulates account-related properties and operations (like deposit, withdraw, transfer).
The OnlineBankingSystem class manages a collection of accounts and user interactions.
Data Persistence:

The program uses in-memory storage (HashMap) for managing accounts, indexed by unique account numbers.
Interactive Menu:

A console-based interface allows users to perform banking operations through a menu-driven approach.
Transaction History:

Maintains a list of transaction records for each account.
Validation:

Ensures validity for all operations (e.g., deposit/withdrawal limits, non-existent accounts).
