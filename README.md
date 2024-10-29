
# JavaBank - ATM Simulator

JavaBank is a Java-based ATM simulator that replicates the core features of an Automated Teller Machine (ATM) to manage banking operations efficiently. Designed with a user-friendly graphical interface (using Java Swing), it allows users to securely log in, view their account details, perform transactions, and check transaction history. Additionally, the project features an admin module for managing user accounts and monitoring activity, making it a comprehensive banking simulation tool.

## Project Overview

The JavaBank ATM Simulator is divided into two main modules:

1. **Admin Module**  
   The admin module is designed for managing user accounts and overseeing transactions. Admins can securely log in to access features such as:
   - **Account Management**: Create, update, or delete user accounts.
   - **Transaction Monitoring**: View transaction records of all users to ensure account integrity.

2. **User Module**  
   The user module provides individual users with the ability to log in securely with a PIN and access various banking operations, including:
   - **Account Operations**: Users can perform basic banking functions like deposits, withdrawals, and transfers.
   - **Transaction History**: Each user can view their own transaction history, including recent deposits, withdrawals, and balance.

## Key Features

- **Secure Access**: The simulator has separate login protocols for admin and users, with admin features restricted to ensure system security.
- **Comprehensive Banking Operations**: Supports common banking transactions like deposits, withdrawals, transfers, and checking transaction history.
- **User-Friendly Interface**: Designed with Java Swing, the interface provides a straightforward and realistic ATM experience.
- **MySQL Database Integration**: All account and transaction information is securely stored in a MySQL database, allowing for persistent data management and retrieval.

## Technologies Used

- **Java (Swing & AWT)**: Used to build the graphical user interface and handle core functionality.
- **MySQL**: Database management for storing user information, account details, and transactions.

## Conclusion

JavaBank is a functional ATM simulation, demonstrating how a Java application can interact with a database to provide secure, real-time banking operations. This project serves as a practical example of using Java for GUI development and MySQL for backend data storage, offering a simple yet effective approach to understanding banking operations in software form.

---
