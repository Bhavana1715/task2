# 📊 Orders Data Analysis with MySQL

This project demonstrates how to work with a customer orders dataset using **MySQL**. It includes table creation, data insertion, complex SQL queries, view creation, performance optimization using indexes, and result analysis using MySQL Workbench.

---

## 🗃️ Dataset Description

The dataset contains customer order data with the following columns:
- `customer_id`
- `customer_status`
- `date_order_placed`
- `delivery_date`
- `order_id`
- `product_id`
- `quantity_ordered`
- `total_retail_price`
- `cost_price_per_unit`

---

## 🛠️ SQL Features Implemented

### ✅ Table & Data Setup
- `CREATE TABLE` with appropriate data types
- `INSERT INTO` statements generated for full dataset

### ✅ Querying
- `SELECT`, `WHERE`, `ORDER BY`, `GROUP BY`
- Aggregate functions: `SUM`, `AVG`, `COUNT`
- `HAVING` clause for grouped filters

### ✅ Subqueries
- Filter orders above average price
- Identify top customers

### ✅ Views
- `monthly_sales`: Monthly order value trends
- `top_customers`: High-value customers ranked by total spend


