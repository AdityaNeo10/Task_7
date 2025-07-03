# Task_7
Task 7 – Created SQL views for data abstraction, reporting, and security using an e-commerce database schema.
This task was focused on creating and using SQL Views to demonstrate data abstraction, simplify complex queries, and enhance security and reusability.

 Tools Used
MySQL Workbench

SQL (MySQL syntax)

 What I Did
Using the existing ecommerce_db schema, I created several views to:

Simplify commonly used queries

Summarize payment and order data

Hide sensitive information (like passwords)

Provide readable product stock statuses

Improve report-building efficiency

 Files Included
task7_views.sql: Full SQL script including all view definitions and example usage queries

(Optional) Screenshots of outputs from view executions in MySQL Workbench

 Views Created & Purpose
View Name	Description
DeliveredOrders	Lists delivered orders along with customer names and order dates
ProductInventory	Shows stock levels of products with human-readable status labels
OrderPayments	Summarizes total payments made per order with customer details
OrderSummary	Displays total items and value per order
UserPublicInfo	Returns public user details while hiding sensitive data like passwords
