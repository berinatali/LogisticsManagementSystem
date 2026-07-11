
# LogisticsManagementSystem
A relational database project developed with Microsoft SQL Server and T-SQL for managing logistics operations. Includes customer management, employee tracking, vehicle management, stored procedures, triggers, functions, and reporting queries.
Features
Customer Management
Employee Management
Vehicle Tracking
Branch Management
Reporting Queries
Stored Procedures
Functions
Triggers
Transaction Management
Data Analysis Queries

Technologies
Microsoft SQL Server
 T-SQL

Database Structure
Tables
Customers**

  Customer information
  Sender / Receiver management

Employees**

Employee records
Branch assignments

Vehicles**

Vehicle information
Vehicle status tracking

Branches**
Branch information
 Location management

Database Relationships

* One Branch can have many Employees
* One Branch can have many Vehicles
* Customers are managed according to customer type



Reports

The project includes SQL reports such as:

 Branch Performance Report

  Employee count by branch
  Vehicle count by branch

Customer Analysis

  * Customer distribution by city
  Sender / Receiver analysis

Employee Salary Ranking

  Employee salary comparison
  * Branch-based ranking using SQL Window Functions
SQL Features Used

* Primary Key
* Foreign Key
* Constraints
* INNER JOIN
* LEFT JOIN
* GROUP BY
* HAVING
* Subqueries
* CTE (Common Table Expression)
* Window Functions
* Stored Procedures
* Triggers
* Functions
* Transactions
Project Structure

Logistics-Management-System

│── Database
│   ├── CreateTables.sql
│   ├── InsertData.sql
│
│── Procedures
│   └── Procedures.sql
│
│── Triggers
│   └── Triggers.sql
│
│── Reports
│   └── Reports.sql
│
│── README.md
##
Entity Relationship Diagram

![Database Diagram](database_diagram.png)

Installation

1. Create a new database in SQL Server.
2. Run the table creation scripts.
3. Insert sample data.
4. Execute procedures, functions and triggers.
5. Run report queries.

 Project Goal

The goal of this project is to design a relational database system for logistics operations and demonstrate SQL database design, data management and reporting skills.
