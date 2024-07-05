# Bank Database System

This project implements a Bank Database System using SQL, leveraging key concepts of Database Management Systems (DBMS).

## Description

- **Database Design**: The system is designed to handle various banking operations efficiently.
- **Functionality**: Includes modules for managing accounts, transactions, customers, and other banking-related data.
- **Implementation**: Uses SQL for creating, manipulating, and querying the database.

## Features

- **Account Management**: Create, update, and delete bank accounts.
- **Customer Management**: Manage customer details and their banking relationships.
- **Transaction Handling**: Record and track deposits, withdrawals, and transfers.
- **Reports**: Generate reports on account statements, transaction history, and more.

## Database Structure

- **Tables**: 
  - `Customers`: Stores customer details.
  - `Accounts`: Stores account details.
  - `Transactions`: Logs all transactions.
  - `Branches`: Information about bank branches.

- **Relationships**: 
  - Customers can have multiple accounts.
  - Accounts can have multiple transactions.
  - Each account and transaction is linked to a specific branch.

## Usage

1. **Setup Database**:
   - Import the provided SQL script to set up the database schema.
   - Ensure your SQL server is running and accessible.

2. **Run Queries**:
   - Use the provided SQL queries to interact with the database.
   - Customize queries as needed for different operations.

3. **Generate Reports**:
   - Use SQL SELECT statements to generate various reports.
   - Modify the provided report templates to fit specific requirements.

