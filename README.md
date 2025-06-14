# 🏦 C++ Banking Management System

This project is a fully functional Banking Management System written in C++. It uses advanced OOP principles including **inheritance**, **polymorphism**, **operator overloading**, **templates**, the **Singleton pattern**, and the **Builder design pattern** to simulate real-world banking operations for savings and current accounts.

---

## 🚀 Features

- 🧑 Client profile using the **Singleton pattern**
- 💳 Card generation using the **Builder design pattern**
- 🏦 Two account types:
  - **Savings Account** (with interest rate and balance history)
  - **Current Account** (with transaction limits and fees)
- 💰 Deposit and withdrawal handling
- 📈 Account transaction history
- 📋 Menu-driven user interface in the console
- 🧠 Robust memory management and exception handling

---

## 🛠️ Technologies Used

- **C++17**
- Object-Oriented Programming (OOP)
- STL: `vector`, `unordered_map`

---

## 🧩 Design Patterns Implemented

- **Singleton**: For managing a unique `ClientData` instance
- **Builder**: For modular card creation (`CardPartsBuilder`)
- **Templates**: For generic account management

---

## 🖥️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/codewithaimii/Bank-management-System.git
   cd Banking-System
   //Compile the program:
g++ -std=c++17 -o bank managment system.cpp
