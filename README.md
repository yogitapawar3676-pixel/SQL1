📁 Task 1: Database Setup and Schema Design
🎯 Objective
Design and implement a relational database schema to manage a simple ecommercedb. This task involves creating the necessary tables, defining relationships, and visualizing the entity-relationship model.# SQL1
###  Tools Used
- **Database:** MySQL
- **IDE:** MySQL Workbench
- **Diagram Tool:** MySQL Workbench ER Model 

---

### Schema Overview

#### Tables:
- `Customer` – Stores customer details
- `Categories` – Product categories
- `Product` – Product information
- `Orders` – Customer orders
- `OrderItems` – Products within orders
- `Payment` – Payment information for each order

#### Key Relationships:
- Each **Customer** can place multiple **Orders**
- Each **Order** includes multiple **Products** via **OrderItems**
- Each **Product** belongs to a **Category**
- Each **Order** may have a related **Payment**

---

###  SQL Script
You can find the full SQL schema in the file [`ecommerce_schema.sql`](./ecommerce_schema.sql)

---

###  ER Diagram
![ER Diagram](https://github.com/yogitapawar3676-pixel/SQL1/blob/main/ER%20diagram.png) <!-- Update path if needed -->
