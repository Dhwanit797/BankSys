# 🏦 PyBank — Python Terminal-Based Bank Management System

## 📌 Description

**PyBank** is a terminal-based banking system built using Python that simulates basic banking operations such as account management and financial transactions.

The system allows users to create accounts, store personal information, and perform simple banking operations like deposits and withdrawals through a command-line interface.

It demonstrates **file handling**, **modular programming**, and **user interaction logic** using pure Python.

---

## 🚀 Features

### 👤 Account Management

* User login system
* Create new accounts
* Store personal details:

  * Name
  * Password
  * Age
  * City
* View stored account information

### 💰 Transaction System

* Withdraw money
* Deposit funds
* Balance calculations
* Transaction exit handling

### 📁 File-Based Storage

* User information saved in text files
* Bank balances logged to separate file
* Persistent data storage between sessions

---

## 🧱 Project Structure

```
PyBank/
│
├── main.py
├── info.py
├── user_control.py
├── user_info.txt
├── user_bank_balance.txt
│
└── README.md
```

---

## ⚙️ Requirements

* Python 3.x
* No external libraries required (uses built-in Python modules only)

---

## ▶️ How to Run

```bash
python main.py
```

Menu Flow:

```
1. User Account
2. User Transactions
```

### User Account

* Login or create new account
* Enter or view user details

### User Transactions

* Withdraw money
* Deposit money
* Exit transaction system

---

## 🧠 Concepts Demonstrated

* File handling (read/write operations)
* Modular Python programming
* CLI-based user interfaces
* Conditional logic & loops
* Input validation
* Simple financial calculations
* Persistent data storage

---

## ⚠️ Notes

* This is a learning project — not a real secure banking system.
* Passwords are stored in plain text.
* Balance is manually entered by the user.
* No authentication encryption implemented.
* No database integration.
* Transaction history is basic text logging.

---

## 🔮 Future Improvements (Ideas)

* Secure password hashing
* Database integration (SQLite / MySQL)
* Automatic balance tracking
* Transaction history system
* Account deletion feature
* Admin dashboard
* Multi-user authentication
* Input validation improvements
* GUI version using Tkinter or PyQt
* REST API backend for real banking simulation

---

## 👨‍💻 Author

**Dhwanit**
Python Developer & Student

---
