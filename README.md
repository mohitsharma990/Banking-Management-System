# Banking Management System

## Overview
The **Banking Management System** is a comprehensive project designed to simulate the core functionalities of a banking system. It provides role-based access for customers, employees, managers, and administrators, ensuring secure and efficient operations. The system emphasizes data consistency, security, and proper handling of concurrency using file management, locking mechanisms, and process synchronization.

## Features

### Customer
- Secure Login (One session per user)
- View Account Balance
- Deposit Money
- Withdraw Money
- Transfer Funds
- Apply for a Loan
- Change Password
- Add Feedback
- View Transaction History
- Logout/Exit

### Bank Employee
- Secure Login (One session per user)
- Add New Customer
- Modify Customer Details
- Process Loan Applications
- Approve/Reject Loans
- View Assigned Loan Applications
- View Customer Transactions (Passbook feature)
- Change Password
- Logout/Exit

### Manager
- Secure Login (One session per user)
- Activate/Deactivate Customer Accounts
- Assign Loan Applications to Employees
- Review Customer Feedback
- Change Password
- Logout/Exit

### Administrator
- Secure Login (One session per user)
- Add New Bank Employees
- Modify Customer/Employee Details
- Manage User Roles
- Change Password
- Logout/Exit

## Technical Specifications
- **Socket Programming:** The server handles the database and serves multiple clients concurrently.
- **System Calls:** System calls are used for process management, file management, file locking, semaphores, multithreading, and inter-process communication.

## Evaluation Criteria
1. Blueprint/Class Diagram
2. Working Code for Each Module
3. Concurrency, Synchronization, and ACID Properties

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Banking-Management-System.git
