# MySQL Zero to Hero

Welcome to **MySQL Zero to Hero**, a complete practical roadmap to learn MySQL from the basics to advanced real-world database skills.

This repository is designed for beginners, students, developers, QA engineers, data analysts, and anyone who wants to understand how relational databases work using MySQL.

## What You Will Learn

- Database fundamentals
- MySQL installation and setup
- SQL basics
- CRUD operations
- Filtering, sorting, and grouping data
- Joins
- Subqueries
- Views
- Stored procedures
- Functions
- Triggers
- Indexing
- Transactions
- Database design
- Normalization
- Backup and restore
- User management
- Real-world database projects
- Interview questions and practice problems

## Who This Repository Is For

This repository is suitable for:

- Complete beginners
- University students
- Software engineering students
- Backend developers
- Full-stack developers
- QA engineers
- Data analysts
- Anyone preparing for SQL interviews

## Repository Structure

```text
mysql-zero-to-hero/
│
├── 01-introduction-to-databases/
├── 02-mysql-installation/
├── 03-sql-basics/
├── 04-database-and-table-operations/
├── 05-crud-operations/
├── 06-filtering-and-sorting/
├── 07-aggregate-functions/
├── 08-joins/
├── 09-subqueries/
├── 10-constraints/
├── 11-views/
├── 12-stored-procedures/
├── 13-functions/
├── 14-triggers/
├── 15-indexes-and-performance/
├── 16-transactions/
├── 17-normalization/
├── 18-backup-and-restore/
├── 19-user-management/
├── 20-real-world-projects/
├── exercises/
├── interview-questions/
├── sample-databases/
└── README.md
```

## Learning Path

### Beginner Level

Start here if you are new to databases.

1. What is a database?
2. What is DBMS and RDBMS?
3. What is MySQL?
4. Installing MySQL
5. Creating databases
6. Creating tables
7. Inserting data
8. Reading data
9. Updating data
10. Deleting data

### Intermediate Level

This section helps you write better queries.

1. WHERE clause
2. ORDER BY
3. GROUP BY
4. HAVING
5. Aggregate functions
6. Joins
7. Subqueries
8. Constraints
9. Views

### Advanced Level

This section focuses on real-world database usage.

1. Stored procedures
2. Functions
3. Triggers
4. Indexing
5. Query optimization
6. Transactions
7. Backup and restore
8. User roles and permissions

### Project Level

Apply everything through practical projects.

1. Student Management Database
2. Library Management Database
3. Sales Management Database
4. Inventory Management Database
5. E-commerce Database
6. Hospital Appointment Database
7. POS System Database

## How to Use This Repository

1. Follow the folders in order.
2. Read the notes.
3. Run the SQL examples.
4. Complete the exercises.
5. Try the projects.
6. Review interview questions.

## Requirements

- MySQL Server
- MySQL Workbench or any SQL client
- Basic computer knowledge

## Recommended Tools

- MySQL Community Server
- MySQL Workbench
- DBeaver
- VS Code
- XAMPP or WAMP for local testing

## Practice Method

For every topic:

1. Read the explanation.
2. Run the example query.
3. Modify the query.
4. Complete the exercise.
5. Try a real-world example.

## Sample Query

```sql
CREATE DATABASE company_db;

USE company_db;

CREATE TABLE employees (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100),
    email VARCHAR(100),
    salary DECIMAL(10,2),
    department VARCHAR(50)
);

INSERT INTO employees (name, email, salary, department)
VALUES 
('John Doe', 'john@example.com', 75000.00, 'IT'),
('Jane Smith', 'jane@example.com', 85000.00, 'HR');

SELECT * FROM employees;


# Full Folder Content Plan

## 01-introduction-to-databases

```markdown
# Introduction to Databases

## Topics

- What is data?
- What is a database?
- What is DBMS?
- What is RDBMS?
- SQL vs MySQL
- Relational database concepts
- Tables, rows, and columns
- Primary key and foreign key basics

## Example

A student database may contain:

- Students table
- Courses table
- Enrollments table

Each table stores related data in rows and columns.

# MySQL Installation

## Topics

- Downloading MySQL
- Installing MySQL Server
- Installing MySQL Workbench
- Creating a local connection
- Testing MySQL installation

## Basic Test Query

```sql
SELECT VERSION();


## 03-sql-basics

```markdown
# SQL Basics

## Topics

- What is SQL?
- SQL syntax
- SQL statements
- SQL keywords
- Comments in SQL
- Case sensitivity
- Common SQL data types

## Example

```sql
SELECT 'Hello MySQL';


## 04-database-and-table-operations

```markdown
# Database and Table Operations

## Topics

- CREATE DATABASE
- SHOW DATABASES
- USE database
- DROP DATABASE
- CREATE TABLE
- SHOW TABLES
- DESCRIBE table
- ALTER TABLE
- DROP TABLE

## Example

```sql
CREATE DATABASE school_db;

USE school_db;

CREATE TABLE students (
    student_id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100),
    age INT,
    email VARCHAR(100)
);
