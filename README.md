# Sales Description:
Yummiee_Pizza Pvt. Ltd. has demonstrated consistent sales growth driven by a customer-centric approach, strategic marketing initiatives, and an expanding footprint through dine-in, takeaway, and online delivery channels. Monthly and quarterly sales reflect strong demand across both classic and premium pizza categories, supported by combo deals, seasonal offers, and loyalty programs.

# Day - 1 Task

Objective:  Learn to create databases, tables, and define relationships.
 Tools:MySQL Workbench / pgAdmin / SQLiteStudio.
 Deliverables:  SQL script to create schema and ER diagram
 
| Tools and Laguage   | Desciption       |
| ------------------- | -----------------|
| Tools               | MySQL Workbench  |
| Language            | MySQL            |


 1.Choose a domain (e.g., Library, E-commerce)
     Domain: E-Commerce (Yummiee Pizza)
     
 2.Identify entities and relationships
  Table Relationship:

  1. 
   pizzas ↔ pizza_types
   Relationship: Many-to-One
   Foreign Key: pizzas.pizza_type_id → pizza_types.pizza_type_id

  2.   
   orders ↔ order_details_details
   Relationship: One-to-Many
   Foreign Key: order_details_details.order_id → orders.order_id

  3.   
   order_details_details ↔ pizzas
   Relationship: Many-to-One
   Foreign Key: order_details_details.pizza_id → pizzas.pizza_id

 3.Create tables using CREATE TABLE
    create table yummiee_pizza;
    
 4.Define primary and foreign keys
    foreign key: pizza_type_id,
    foreign key: order_id

Task Goal Understand how to build a simple database system and upload it to GitHub.
Internship Task 1 completed.

![Uploading Entity Relationship Diagram.jpg]()
