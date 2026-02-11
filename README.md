📊 Sales & Customer Analytics – SQL Project
🔎 Project Overview

This project analyzes transactional sales data using SQL to extract business insights about:

Sales performance over time

Product yearly performance comparison

Customer segmentation (VIP / Regular / New)

Customer lifetime metrics

Recency & average order value analysis

The final output is a structured analytical view:
gold.report_customers

🧠 Business Questions Answered

How do total sales and customer count change over time?

Which products outperform their historical average?

How do products perform compared to previous year?

Who are our VIP customers?

What is customer lifetime value and recency?

🛠 Technologies Used

PostgreSQL

Window Functions (LAG, AVG OVER, SUM OVER)

CTEs

Date functions (AGE, EXTRACT, DATE_TRUNC)

GitHub Pages (project presentation)

📈 Key Features
1️⃣ Change Over Time Analysis

Yearly sales trend

Monthly sales breakdown

Unique customer growth

2️⃣ Cumulative Analysis

Running total sales

Yearly cumulative revenue

3️⃣ Product Performance

Sales vs historical product average

Year-over-year comparison

Growth/decline classification

4️⃣ Customer Segmentation

Customers are classified as:

Segment	Condition
VIP	12+ months lifespan & > $5000 spent
Regular	12+ months & ≤ $5000 spent
New	< 12 months
📊 Final Analytical View

The gold.report_customers view includes:

Age group

Customer segment

Recency (months since last purchase)

Total orders

Total sales

Average order value (AOV)

Average monthly spend

Customer lifespan (months)

📂 Dataset

Dataset used: sales_dataset.csv

Contains:

Orders

Customers

Products

Sales amounts

Dates

🚀 How to Run

Create schema gold

Import dataset

Execute SQL files in order

Query:

SELECT * FROM gold.report_customers;

📌 Sample Insights

X% of revenue comes from VIP customers

Products with consistent YoY growth identified

Customer recency helps detect churn risk

📎 Author

Dmitruz Ruzhytskyi
Data Analyst | SQL | Financial & Product Analytics
