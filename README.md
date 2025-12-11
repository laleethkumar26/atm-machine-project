# 🏧 ATM Machine Simulation System (Python + SQLite)

A console-based **ATM Machine Simulation System** built using **Python**, featuring **OOP concepts, encapsulation, inheritance, and secure PIN storage** using **SHA-256 hashing**.  
This project simulates real-world ATM operations like account creation, authentication, deposits, withdrawals, and balance updates — all stored persistently in a **SQLite database**.

---

## 🚀 Features

### 🔐 **User Authentication**
- Login using **account number + PIN**
- PIN is stored **securely using SHA-256 hashing** (never stored in plain text)

### 🏦 **Core Banking Operations**
- Balance Inquiry  
- Cash Withdrawal  
- Cash Deposit (balance updates in SQLite instantly)  
- Session-based Transaction History  
- PIN Change (secure, hashed update)

### 🧾 **Account Management**
- Create New Account (Account No + PIN)
- New accounts start with **₹0 balance**
- All accounts stored in SQLite DB: `atm_accounts.db`

### 🧱 **Technical Concepts**
- **Encapsulation:** Private balance & PIN (`__balance`, `__pin_hash`)  
- **Inheritance:** `SavingsAccount` extends `Account`  
- **Persistence:** SQLite database with full CRUD operations  
- **Hashing:** PINs stored using SHA-256 for security  

---

## 📂 Project Structure

