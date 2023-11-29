# Banking-System
# Bank Account System

This project implements a basic bank account system using object-oriented programming concepts in C++. It demonstrates the creation and management of different types of bank accounts, including savings and checking accounts, with operations like deposits, withdrawals, balance inquiries, and interest calculations.

## Features

* **Account creation and management** Create and manage with attributes like account number, account holder name, balance, and account type.

* **Deposit and Withdrawal Operations:** Perform deposit and withdrawal transactions on bank accounts, handling invalid input and insufficient funds

* **Account Balance Inquiries:** display the current balence

* **Transaction History Tracking:** maintain the transaction

* **Savings Account Interest Calculations:** Apply interest accrued over time to savings accounts.

## Usage

To run the code, you will need a C++ compiler and a basic understanding of object-oriented programming concepts.




./bank_account


## Example Usage

The main.cpp file provides an example of how to create and manage different types of bank accounts, perform transactions, and track transaction history.

### Creating Accounts

c++
Account *account1 = new SavingsAccount(123456789, "John Doe", 1000);
Account *account2 = new CheckingAccount(987654321, "Jane Doe", 500);

account1->deposit(200); // Deposit $200 to account 123456789
account1->withdraw(300); // Withdraw $300 from account 123456789

account2->deposit(100); // Deposit $100 to account 987654321
account2->withdraw(50); // Withdraw $50 from account 987654321

account1->calculateInterest(); // Calculate interest for savings account 123456789

account1->getBalance(); // Get the balance of account 123456789
account2->getBalance(); // Get the balance of account 987654321

account1->getTransactionHistory(); // View transaction history for account 123456789
account2->getTransactionHistory(); // View transaction history for account 987654321


