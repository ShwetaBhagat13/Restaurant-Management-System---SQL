# 🍽️ HotSizzlers – Restaurant Management System Using SQL

## 📌 Project Overview  
This project builds a robust **Restaurant Management System** for **HotSizzlers**, a fictional restaurant, using SQL. It handles order processing, menu management, customer data (including premium discounts), and delivery assignments based on area codes. The system ensures efficient food service operations while maintaining data integrity through a well-designed relational database.

## 🎯 Objective  
To design and implement a comprehensive SQL-based system that enables HotSizzlers to manage customer orders, delivery assignments, premium customer discounts, and menu changes with high accuracy and efficiency.

## 🛠️ Tools & Skills Used  
- SQL (DDL, DML, DQL)  
- Joins, Subqueries, Aggregate Functions  
- Database Normalization & Integrity Constraints  
- Foreign Key Relationships & Cascading Deletes  
- Efficient Data Filtering and Reporting

## 📂 Project Files  
- `Restaurant Management System - SQL Project.pptx` – Project overview, schema diagrams, challenges addressed, and SQL outputs  
  > 📥 To open the PPT: click on it in the repo, then click **`View raw`** – it will auto-download.

## 🧩 Database Design  
The system consists of several interconnected tables:
- `Customers` – Stores customer details and premium membership info  
- `FoodItems` – Contains menu items and their prices  
- `Orders` – Tracks individual customer orders  
- `OrderDetails` – Lists food items within each order  
- `DeliveryBoys` – Manages delivery personnel and assigned area codes  
- `OrderAssignments` – Assigns orders to delivery boys within matching areas  

## 📊 Key Features & Queries  
- ✅ Dynamic Discounting for premium customers  
- ✅ Area-based Delivery Assignment using area code logic  
- ✅ Sales Reports for specific date ranges  
- ✅ Top Ordered Items analytics  
- ✅ Complex Joins to track multi-area orders  
- ✅ Delivery Boy Performance Reports  
- ✅ Safe Deletion using `ON DELETE SET NULL` and `ON DELETE CASCADE` to handle foreign key constraints

## 💡 Key Insights  
- Orders are efficiently tracked and assigned based on delivery area compatibility  
- Premium customers receive appropriate discounts during billing  
- Attempting to delete referenced food items is safely handled through foreign key constraints  
- Real-time performance tracking is possible for delivery staff  
- The system flags and prevents invalid operations, enhancing data integrity
