C++ Banking System (OOP)

Overview

This is a Bank Management System built using C++ and Object-Oriented Programming (OOP) principles. The system allows users to manage bank clients, handle financial transactions, and enforce security measures like authentication and logging.

Features

✅ User Authentication

Secure login system with a lockout feature after 3 failed attempts.

Login activities are recorded in LoginRegister.txt.

✅ User Role Management

Different levels of access control for system users.

Some operations are restricted based on user roles.

✅ Client Management

Add, update, delete, find, and list bank clients.

✅ Financial Transactions

Deposit, withdraw, and transfer funds between accounts.

Transactions are logged in TransfersLog.txt.

✅ Security & Logging

Passwords are encrypted before storing in Users.txt.

Timestamps and usernames are recorded for key actions.

Project Structure
BankingSystem/
│── src/                     # Source code files (.cpp)
│   ├── main.cpp             # Entry point
│   ├── clsBankClient.cpp
│   ├── clsUser.cpp
│   ├── clsTransactionsScreen.cpp
│   ├── ...
│── include/                 # Header files (.h)
│   ├── clsBankClient.h
│   ├── clsUser.h
│   ├── clsMainScreen.h
│   ├── ...
│── data/                    # Storage files
│   ├── Clients.txt
│   ├── Users.txt
│   ├── TransfersLog.txt
│   ├── LoginRegister.txt
│── docs/                    # Documentation
│   ├── README.md
│── .gitignore               # Ignore compiled files, logs, etc.
│── LICENSE                  # Open-source license


**Note:
To Login (username:Admin, password:1234)