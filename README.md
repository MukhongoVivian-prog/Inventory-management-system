# Inventory Management System

## Description

The Inventory Management System is a relational database built using MySQL that helps manage products, categories, suppliers, inventory levels, customers, and orders for a small to medium-sized business. It provides a structured way to track stock, process customer orders, and ensure smooth inventory operations.

## Features

- Categorization of products
- Supplier tracking and contact information
- Real-time inventory updates
- Customer and order management
- Many-to-many relationship handling between orders and products

## How to Setup

1. **Install MySQL**
   - Ensure MySQL Server is installed on your machine.

2. **Create the Database**
   - Open MySQL Workbench or any SQL client.
   - Create a new database:
     ```sql
     CREATE DATABASE inventory_db;
     USE inventory_db;
     ```

3. **Import the SQL File**
   - Import the provided `inventory_management.sql` file which contains all the `CREATE TABLE` statements with proper constraints.

4. **Optional**
   - You may add test data or extend the schema with views, procedures, or triggers based on your use case.

## Entity Relationship Diagram (ERD)

You can view the ERD using MySQL Workbench.




