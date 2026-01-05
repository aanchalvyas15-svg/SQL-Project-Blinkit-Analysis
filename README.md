# SQL Project – Blinkit Database Analysis

## 📌 Project Introduction
Blinkit (formerly Grofers) is an Indian quick-commerce platform that delivers groceries and daily essentials within minutes.  
This project demonstrates how SQL can be used to design, manage, and analyze a real-world e-commerce database.

The project covers database creation, data manipulation, and advanced querying to extract meaningful business insights related to customers, orders, products, inventory, and delivery performance.

---

## 🛠 Tools & Technologies Used
- MySQL
- SQL (DDL, DML, DQL)
- GitHub (Project Hosting & Documentation)

---

## 🗂 Database Design
**Database Name:** Blinkit  

### Tables Used:
- Customer
- Products
- Orders
- Order Details
- Inventory
- Delivery Performance

### Key Relationships:
- Customers → Orders (1:M)
- Orders → Order Details (1:M)
- Products → Order Details (1:M)
- Products → Inventory (1:1 / 1:M)
- Orders → Delivery Performance (1:1)

---

## 📊 Key Analysis Performed

### 1️⃣ Customer Segmentation Analysis
- Identified high-value customers
- Analyzed total orders and average order value

### 2️⃣ Product Insights
- Identified products with highest margin percentage
- Compared MRP vs selling price to analyze discounts

### 3️⃣ Inventory Analysis
- Monitored stock trends
- Identified inefficiencies in inventory management

### 4️⃣ Revenue & Sales Reports
- Analyzed sales trends over time
- Identified peak order days

---

## 🧠 SQL Concepts Covered
- Database & table creation (DDL)
- Data insertion, update, delete (DML)
- Data querying using SELECT (DQL)
- WHERE, GROUP BY, HAVING, ORDER BY
- Joins (Inner, Left, Right, Full)
- Subqueries (Single & Multiple Row)
- Aggregate functions
- String, Date, and Math functions
- Views

---

## 📄 Project Documentation
👉 **Complete SQL queries with screenshots and outputs:**  
[View Project PDF](Sql%20Project%20of%20Blinkit.pdf)
---

## 🎯 Conclusion
This project demonstrates practical SQL skills required for data analysis in an e-commerce environment.  
The insights obtained can help improve customer engagement, inventory control, and delivery efficiency.

---

**Created by:** Aanchal Vyas  # SQL-Project-Blinkit-Analysis
SQL analysis project using Blinkit dataset
