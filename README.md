# Zomato-food-delivery

### **Project Title: Food Delivery Database Management System**

#### **Project Description:**

This project involves the design and implementation of a comprehensive **Food Delivery Database Management System** using PostgreSQL. It simulates the backend architecture of a real-world food ordering platform such as Zomato or Swiggy. The system is designed to manage customers, restaurants, menus, orders, payments, delivery partners, disputes, and invoices in a normalized, relational schema.

The project includes:

* **Database Schema Design**:
  Implemented using DDL statements, the database schema consists of well-structured, interrelated tables such as `Customer`, `Menu`, `Restaurants`, `Orders`, `Cart`, `Cart_Items`, `Delivery_Partner`, `Premium`, `Invoice`, and `Disputes`. Proper normalization and referential integrity have been maintained using primary and foreign keys with cascade operations.

* **Sample Data Insertion**:
  A large volume of realistic test data for customers, restaurants, and menu items was inserted to simulate real-world operations and facilitate testing of queries and stored procedures.

* **Stored Procedures and Functions**:
  Multiple PL/pgSQL functions have been developed to support complex operations such as:

  * Searching restaurants by food item, cuisine type, name, rating, availability, and discount.
  * Retrieving customer cart details and total billing.
  * Managing orders, delivery locations, invoices, and disputes.
  * Providing analytics for restaurants like active orders, revenue performance, and poor ratings from customers.

* **Use Cases Covered**:

  * **Customer Perspective**: View menus, place orders, track carts, and set delivery addresses.
  * **Restaurant Perspective**: Track orders, analyze customer feedback, and update menu items with discounts.

* **Highlights**:

  * City-wise search and filters to simulate localized service availability.
  * Rating and invoice tracking for both individual orders and premium subscriptions.
  * Flexible functions for both read and update operations, enhancing modularity and scalability.

#### **Technologies Used**:

* **PostgreSQL** for database schema, functions, and data manipulation.
* **PL/pgSQL** for advanced logic and stored procedure handling.
* **ERD and Schema Diagrams** for conceptual and logical data modeling.


