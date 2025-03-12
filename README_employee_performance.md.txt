# Employee Performance & Salary Analysis (HR Industry)

## 📌 Overview
This project analyzes employee salaries, performance, and promotions to determine trends and key insights.

## 🗂 Dataset
- **Columns:** `employee_id`, `employee_name`, `department`, `salary`, `performance_score`, `last_promotion_date`
- **Insights:** 
  - Average salary per department
  - Top-performing employees

## 🚀 SQL Queries
- `AVG(salary) AS avg_salary` grouped by department
- `ORDER BY performance_score DESC` to find top employees

## 📤 How to Use
1. Run `employee_performance_analysis.sql` in MySQL.
2. Import `employee_performance.csv` into `employee_performance` table.
3. Execute queries to analyze employee performance and salaries.
