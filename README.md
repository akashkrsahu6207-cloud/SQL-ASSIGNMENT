# 📊 SQL Assignment – E-Commerce & Sakila Database Analysis

## 📌 Overview

This project demonstrates practical usage of SQL concepts including database creation, table design, data insertion, and advanced query writing. It covers both a custom E-Commerce database and analytical queries using the Sakila database.

The goal of this assignment is to build a strong foundation in SQL for real-world data analysis tasks.

---

## 🛠️ Technologies Used

* MySQL
* MySQL Workbench
* SQL (Structured Query Language)

---

## 🗂️ Project Structure

### 🔹 Part 1: E-Commerce Database

* Created a database named **ECommerceDB**
* Designed the following tables:

  * Categories
  * Products
  * Customers
  * Orders
* Applied constraints:

  * Primary Key
  * Foreign Key
  * NOT NULL
  * UNIQUE
* Inserted sample data into all tables

---

### 🔹 Part 2: SQL Concepts Covered

This assignment includes implementation of key SQL concepts:

* DDL, DML, DQL Commands
* SQL Constraints
* LIMIT & OFFSET (Pagination)
* Common Table Expressions (CTE)
* Window Functions (ROW_NUMBER)
* SQL Normalization (1NF, 2NF, 3NF)
* Joins (INNER JOIN, LEFT JOIN)
* Aggregation Functions (COUNT, SUM)

---

### 🔹 Part 3: Query-Based Tasks

#### ✅ Customer Order Report

* Displayed customer name, email, and total number of orders
* Included customers with zero orders using LEFT JOIN

#### ✅ Product & Category Information

* Retrieved product details with category names
* Sorted results alphabetically

#### ✅ Top Products per Category

* Used CTE + ROW_NUMBER() to find top 2 expensive products in each category

---

## 🎬 Part 4: Sakila Database Analysis

Performed real-world business analysis using Sakila database:

### 🔸 Key Insights:

1. Top 5 customers based on total spending
2. Top 3 movie categories by rental count
3. Store-wise inventory and unrented films
4. Monthly revenue analysis for 2023
5. Frequent customers (more than 10 rentals in last 6 months)

---

## ⚠️ Important Note

The Sakila database contains historical data (2005–2006). Therefore, queries using `CURDATE()` may not return results. A fixed reference date was used for accurate analysis.

---

## 📈 Learning Outcomes

* Hands-on experience with SQL queries
* Understanding of relational database design
* Ability to perform real-world data analysis
* Improved problem-solving using SQL

---

## 🚀 Future Improvements

* Add ER diagrams for better visualization
* Create dashboards using Power BI / Tableau
* Optimize queries for performance

---

## 🙌 Conclusion

This assignment provides a comprehensive understanding of SQL fundamentals along with practical implementation. It demonstrates how SQL can be used for both database management and business analytics.

---
