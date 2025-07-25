# 🛒 Amazon Sales Analysis — SQL Project

## 📌 Overview

This project is a comprehensive SQL-based analysis of an **Amazon-style eCommerce dataset** using **SQLite**. It explores real-world sales performance, customer behavior, product profitability, and return patterns.

The dataset includes key entities like:
- **Orders**
- **Products**
- **Customers**
- **Returns**
- **Sellers**

Using SQL, I’ve answered 30+ business and data-driven questions across various difficulty levels, covering everything from simple aggregations to advanced window functions and subqueries.

---

## 📊 What’s Included in the Analysis?

### 🔹 Basic – Data Selection & Aggregation (GROUP BY, COUNT, AVG)
1. List all unique product categories.
2. Show the total number of orders placed per state.
3. Find the average quantity ordered per category.
4. Display the top 5 customers who made the highest profits.
5. List the total revenue per seller.
6. Find the product with the highest price.
7. Count the total number of returns for each product.
8. Show number of orders placed per month.

---

### 🔹 Intermediate – JOINs, CASE, Subqueries
9. Identify the top 5 products that generated the highest revenue.
10. Display customers who have placed more than 5 orders.
11. List all sellers who haven’t had any returns.
12. Find the average sales amount per order per customer.
13. Display all orders that were returned.
14. Determine the most frequently returned product.
15. List products with a sale price lower than the average price of their category.

---

### 🔹 Advanced – Window Functions & Complex Subqueries
16. Calculate the running total of sales per seller.
17. Find the first order date for each customer.
18. Rank the top 3 customers by total revenue within each state.
19. Determine the product with the highest month-over-month revenue increase.
20. Identify orders where sale was higher than any previous order by the same seller.

---

### 🔹 Analytical – Profitability & Business Metrics
21. Calculate profit per order: `sale - (quantity * cogs)`.
22. Calculate profit margin percentage for each sale.
23. Find the top 5 products whose revenue decreased compared to the previous year.
24. Identify the highest profitable sub-category.
25. Calculate the percentage contribution of each sub-category to total revenue.
26. List sellers with the highest return rate (returns/orders).
27. Determine the month with the highest number of orders.
28. Identify the top 2 categories that received maximum returns and their return percentage.
29. Display the difference in monthly revenue per category from the previous month.
30. Find customers who returned more than 50% of their orders.

---

## 🧠 Skills & Concepts Demonstrated

- ✅ SQL JOINS (INNER, LEFT, etc.)
- ✅ GROUP BY & Aggregations (SUM, COUNT, AVG)
- ✅ Subqueries & CTEs
- ✅ Window Functions: `RANK()`, `LAG()`, `SUM() OVER`
- ✅ Filtering using `HAVING` and `WHERE`
- ✅ CASE statements
- ✅ Revenue & Profitability Analysis
- ✅ Trend Analysis with Time Functions

---

## 🛠 Tech Stack

- **SQLite** (DB Browser for SQLite)
- **SQL** for querying and analysis
- **Git & GitHub** for version control

---
