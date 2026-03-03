# Pharmaceutical Shop Database System

## Project Overview

This project is a structured relational database system designed to manage the operations of a pharmaceutical retail shop. 

It models real-world entities such as medicines, suppliers, customers, transactions, and inventory, and provides SQL scripts for database initialization, data insertion, and query execution.

The goal of this project was to design a normalized schema, enforce relational integrity, and demonstrate efficient querying of business-critical data.

---

## Objectives

- Design a well-structured relational database schema
- Implement primary and foreign key constraints
- Ensure data integrity and normalization
- Support inventory management and sales tracking
- Enable efficient retrieval of operational insights using SQL queries

---

## Database Design

The database includes the following core entities:

- Medicines
- Suppliers
- Customers
- Transactions
- Inventory

The schema ensures:
- Proper normalization
- Referential integrity using foreign keys
- Logical relationship mapping between entities

ERD and schema diagrams are included in this repository.

---

## Files Included

- `Proj-INIT.sql` – Database creation and table definitions
- `Proj-INSERT.sql` – Sample data insertion scripts
- `Proj-QUERY.sql` – SQL queries for retrieving business insights
- `ERD.png` – Entity Relationship Diagram
- `Schema.png` – Database schema diagram

---

## Key Features

- Inventory tracking for medicines
- Sales and transaction management
- Supplier management
- Customer record maintenance
- Analytical queries for:
  - Stock availability
  - Sales summaries
  - Customer transaction history

---

## Sample Query Use Cases

- Retrieve low-stock medicines
- Calculate total sales over a period
- Identify top-selling medicines
- Track supplier-wise inventory
- View customer purchase history

---

## Technical Concepts Applied

- Relational Database Design
- Normalization
- Primary & Foreign Keys
- SQL (DDL, DML, Queries)
- Data Integrity Constraints
- Query Optimization Basics

---

## How to Run

1. Execute `Proj-INIT.sql` to create the database and tables.
2. Run `Proj-INSERT.sql` to populate the tables with sample data.
3. Use `Proj-QUERY.sql` to test analytical and operational queries.

This project can be executed in MySQL / Oracle / any standard SQL-compatible database system.

---

## Future Improvements

- Add stored procedures and triggers
- Implement indexing for performance optimization
- Integrate with a frontend application
- Add role-based access control

---

## Author

Tanya Mediratta  
B.Tech Computer Science
