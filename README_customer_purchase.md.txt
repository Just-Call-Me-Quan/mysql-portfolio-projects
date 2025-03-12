# Customer Purchase Analysis (Retail Industry)

## 📌 Overview
This project analyzes customer purchases for a retail company, including total sales, top customers, and product trends.

## 🗂 Dataset
- **Columns:** `purchase_id`, `customer_name`, `product`, `quantity`, `price`, `purchase_date`
- **Insights:** 
  - Total revenue calculation
  - Top customers by spending
  - Best-selling products

## 🚀 SQL Queries
- `SUM(price * quantity) AS total_revenue`
- `GROUP BY customer_name` to find top customers

## 📤 How to Use
1. Run `customer_purchase_analysis.sql` in MySQL.
2. Import `customer_purchases.csv` into `customer_purchases` table.
3. Execute queries to analyze customer behavior.
