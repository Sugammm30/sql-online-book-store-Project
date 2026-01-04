# 📚 Bookstore Management System – SQL & Excel Project

## 📌 Project Overview

This project is a **Bookstore Management System** built using **SQL (PostgreSQL)** for data storage and querying, along with **Microsoft Excel** for data inspection and basic analysis.
The project simulates a real-world bookstore database containing information about **Books, Customers, and Orders**, and answers multiple business-related questions using SQL queries.

---

## 🛠️ Tools & Technologies Used

* **SQL (PostgreSQL)** – Database creation, relationships, and data analysis
* **Microsoft Excel** – Viewing, validating, and analyzing query outputs

**References:**

* PostgreSQL Official Documentation: [https://www.postgresql.org/docs/](https://www.postgresql.org/docs/)
* SQL Concepts (W3Schools): [https://www.w3schools.com/sql/](https://www.w3schools.com/sql/)
* Microsoft Excel Documentation: [https://support.microsoft.com/excel](https://support.microsoft.com/excel)

---

## 🗂️ Database Schema

The project contains **three tables**:

### 1️⃣ Books Table

Stores information about books available in the bookstore.

* Book_ID (Primary Key)
* Title
* Author
* Genre
* Published_Year
* Price
* Stock

### 2️⃣ Customers Table

Stores customer details.

* Customer_ID (Primary Key)
* Name
* Email
* Phone
* City
* Country

### 3️⃣ Orders Table

Stores order transactions.

* Order_ID (Primary Key)
* Customer_ID (Foreign Key)
* Book_ID (Foreign Key)
* Order_Date
* Quantity
* Total_Amount

**Reference:**
Database normalization & relational design: [https://www.geeksforgeeks.org/database-normalization/](https://www.geeksforgeeks.org/database-normalization/)

---

## 🎯 Project Objectives

This project aims to:

* Practice **SQL CRUD operations**
* Use **JOINs, GROUP BY, HAVING, ORDER BY**
* Perform **business analysis queries**
* Understand **real-world relational databases**
* Integrate SQL output with **Excel analysis**

---

## 📊 SQL Queries & Analysis

The project answers **20 real-world business questions**, including:

* Retrieving books by genre and year
* Finding customers by country
* Analyzing orders by date and amount
* Calculating total revenue and stock
* Identifying top-selling books and authors
* Finding high-spending customers
* Computing remaining stock after sales

These queries demonstrate:

* Aggregate functions (`SUM`, `AVG`, `COUNT`)
* Filtering with `WHERE` & `HAVING`
* Table relationships using `JOIN`
* Data grouping and sorting

**Reference:**
SQL Aggregate Functions: [https://www.w3schools.com/sql/sql_count_avg_sum.asp](https://www.w3schools.com/sql/sql_count_avg_sum.asp)

---

## 📈 Excel Usage

Microsoft Excel was used to:

* Verify SQL query results
* View tabular data clearly
* Perform basic sorting and filtering
* Present outputs in a readable format

**Reference:**
Excel data analysis basics: [https://support.microsoft.com/excel-data-analysis](https://support.microsoft.com/excel-data-analysis)

---

## 📂 Project Structure

```
📦 Bookstore-Management-System
 ┣ 📜 bookstore.sql
 ┣ 📊 Excel_Output.xlsx
 ┗ 📘 README.md
```

---

## 🚀 How to Run the Project

1. Install PostgreSQL
2. Create a new database
3. Run the `bookstore.sql` file
4. Execute queries using pgAdmin or SQL Shell
5. Export results to Excel for analysis

**Reference:**
PostgreSQL Installation Guide: [https://www.postgresql.org/download/](https://www.postgresql.org/download/)

---

## 📌 Key Learnings

* Real-world SQL querying experience
* Hands-on relational database design
* Business-focused data analysis
* SQL + Excel integration

---

## 👤 Author

**Sugam Shivaji Kamble**
🎨 Artist turned Data Analyst
📊 SQL | PostgreSQL | Excel

---

