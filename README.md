**Project Overview**

This project is an end-to-end Retail Business Intelligence (BI) solution developed to analyze sales, profit, customer behavior, and discount impact using industry-standard BI tools.

The goal of this project is to demonstrate hands-on experience in data cleaning, SQL-based data modeling, KPI development, and interactive dashboard creation using Power BI and PostgreSQL.

Industry & Domain

Industry: Retail

Domain: Business Intelligence / Data Analytics

Field: Information Technology (IT)

**Tools & Technologies**

Power BI – Data modeling, DAX measures, dashboards, visualization

PostgreSQL – Data storage, transformations, star schema modeling

Advanced Excel – Data cleaning, validation, preprocessing

**Dataset**

Source: Superstore Retail Dataset

Data Type: Orders, customers, products, sales, profit, discounts

Data Cleaning & Preparation

Removed duplicate and invalid records

Handled missing values and inconsistent categories

Standardized date and text formats

Created derived date fields (Year, Month, Quarter)

Reduced dataset size by removing unused columns

Database Design (PostgreSQL)

Implemented a Star Schema to support scalable BI reporting.

**Fact Table**
fact_sales – Sales, profit, quantity, discount

**Dimension Tables**

dim_customer – Customer details and segments
dim_product – Product, category, sub-category
dim_date – Date, month, quarter, year
dim_geo – City, state, region, country
dim_ship_mode – Shipping modes

**KPIs & Metrics**

Total Sales
Total Profit
Profit Margin (%)
Sales Year-over-Year (YoY %)
Average Order Value (AOV)
Top Products by Sales
Loss-Making Products
Discount Impact on Profit
Power BI Dashboards

1️⃣ Executive Summary

Sales, profit, margin, orders
Monthly sales trends
Region-wise performance

2️⃣ Product Performance

Category and sub-category analysis
Top and low-performing products
Sales vs profit comparison

3️⃣ Customer Insights

Segment-wise sales analysis
Top customers
Order frequency trends

4️⃣ Discount & Profitability Analysis

Discount band performance
Loss-making categories
Profit distribution by region

**Performance Optimization**

Used SQL for heavy transformations instead of Power BI
Applied star schema for efficient filtering
Used DAX measures instead of calculated columns
Loaded only required fields into Power BI

**Key Outcomes**

Built a complete BI reporting pipeline from raw data to insights
Demonstrated strong understanding of SQL, data modeling, and Power BI
Created reusable, scalable dashboards suitable for business users

**Future Enhancements**

Add Row-Level Security (RLS) in Power BI
Implement inventory dataset for stock optimization
Publish dashboards to Power BI Service

Volume: Optimized and laptop-friendly (Intel i5 compatible)

