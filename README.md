## 👥 User Roles

### 🧑‍💼 Client
Clients can:
- Log in securely  
- View their current balance (solde)  
- Perform transactions (deposit, withdraw, transfer depending on your implementation)  
- View their own transaction history  

### 👨‍✈️ Admin
Admins can:
- Log in as administrator  
- View the list of all clients  
- View each client’s balance  
- View all transactions across the system  
- Manage client accounts (optional features depending on your implementation)

---

## 🔧 Features
- Clean Java desktop application (or console depending on your design)  
- Role-based authentication (Client/Admin)  
- SQLite database for storing:
  - Clients
  - Balances (soldes)
  - Transactions  
- JSON used for configuration or logs (depending on your setup)  
- Secure transaction handling  
- Clear and organized project structure  

---

## 🛠️ Technologies Used
- **Java** (main programming language)  
- **SQLite** (database for clients, balances, and transactions)  
- **JSON** (storing settings, logs, or temporary data)  
- **JDBC** (Java Database Connectivity for SQLite)  
- **Visual Studio Code / IntelliJ / NetBeans** (your IDE)  

---
## 🚀 How to Run the Application

### 1. Clone the repository
`git clone https://github.com/yourusername/bank-application.git`

### 2. Add SQLite JDBC Driver
Download the SQLite JDBC driver and place it in the **lib/** folder.  
Make sure to add it to your classpath.

### 3. Open the project in your IDE
Import as a Java project.

### 4. Run the main file

---

## 🎯 Purpose of the Project
This Java project was created to practice:
- Database integration with SQLite  
- User authentication and role management  
- Transaction handling in a banking system  
- Data storage using JSON  
- Clean structuring of a Java application  

It simulates how real banking systems separate client and admin functionalities.

---

## 📝 License
This project is for educational purposes. You may extend, modify, or reuse it freely.
