# Retail Store Management Database (Oracle SQL)

This project implements a normalized relational database that models the operations of a retail electronics store.

## Technologies
- Oracle SQL
- Relational Database Design
- SQL Queries
- Database Normalization

## Database Structure

The database models the main entities of a retail business:

- Products
- Stores
- Clients
- Employees
- Orders
- Order Items

Key relationships include:
- One store → multiple employees
- One client → multiple orders
- One order → multiple order items
- Many-to-many relationship between orders and products through an order items table.

## Features

- Fully normalized relational schema
- Primary and foreign key constraints
- Data population with sample records
- SQL queries including:
  - JOIN operations
  - Aggregate functions
  - Subqueries
  - GROUP BY and HAVING
  - CASE and DECODE
  - Hierarchical queries

## Author

Radu Zabava Costin  
Business Informatics Student  
Bucharest University of Economic Studies
