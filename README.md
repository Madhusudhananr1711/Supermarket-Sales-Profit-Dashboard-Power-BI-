# Supermarket-Sales-Profit-Dashboard-Power-BI
# 📌 Project Overview

This project presents an interactive Power BI dashboard built using a Supermarket Sales dataset.
The objective is to transform raw transactional data into actionable business insights that support data-driven decision-making.

The dashboard focuses on:

1. Sales performance
> Profitability analysis
> Store comparison
> Product group insights
> Discount impact evaluation

# 🎯 Business Objectives

> Identify top and bottom performing product groups
> Analyze monthly sales and profit trends
> Compare store-level performance
> Understand customer purchase behavior by price & quantity
> Evaluate the impact of discounts on revenue and profit

# 🧰 Tools & Technologies Used

> Microsoft Excel – Initial data handling
> Power BI Desktop
> Power Query (Data Cleaning & Transformation)
> DAX (Data Analysis Expressions)
> Data Modeling
> Interactive Visualizations

# 📊 Dashboard Sections

1️⃣ Super Market Dashboard – Sales & Profit Insights

> Profit by price and quantity
> Profit trends by value
> Sales performance across product groups
> Discount impact analysis

2️⃣ Retail Pulse – Store & Sales Performance

> Store-wise monthly sales comparison
> Day-wise sales trends
> Product group performance by store
> KPI tracking

3️⃣ Sales & Profit Intelligence Hub

> Net sales & profit by category
> Sales by month (M1, M2, M3)
> Quantity distribution analysis
> Value vs discount insights

# 🔍 Key Features

✔ Sales & Profit Analysis

> Track performance by:
> Product group (SGRP)
> Store code
> Month (M1, M2, M3)
> Unit price

✔ Top & Bottom Performers

Quickly identify: 

> High-profit items
> Low-performing categories
> Stores with declining sales

✔ Customer Purchase Trends

Analyze:

> Buying behavior across price ranges
> Quantity-based purchasing patterns
> Value contribution distribution

✔ Discount & Value Impact

Understand:

> How discounts affect total sales value
> Profit variation due to promotional strategies

✔ Store Performance Insights

Compare:

> Store-wise total sales
> Monthly store trends
> Contribution to overall revenue

# 📈 Key Metrics Used

> Total Sales Value
> Net Sales
> Profit Amount
> Quantity Sold
> Discount Amount
> Store Code Count
> Product Group Count

# 🧮 Sample DAX Measures

Total Sales = SUM(Supermarket[VALUE])

Total Profit = SUM(Supermarket[PROFIT_AMOUNT])

Total Quantity = SUM(Supermarket[QTY])

Total Discount = SUM(Supermarket[DISCOUNT_AMOUNT])

Profit Margin % = 
DIVIDE([Total Profit], [Total Sales], 0)

# 🧹 Data Preparation Steps

1.Removed null and duplicate values
2.Standardized column names
3.Created calculated columns for:

  > Month grouping
  > Profit margin

4.Built relationships between fact and dimension tables
5.Created DAX measures for KPIs

# 🚀 What I Learned

> Advanced data transformation using Power Query
> Writing optimized DAX measures
> Building a structured data model
> Designing clean and interactive dashboards
> Converting data into strategic business recommendations

# 📷 Dashboard Preview

<img width="1275" height="719" alt="Screenshot 2026-02-28 160027" src="https://github.com/user-attachments/assets/c452cd32-0200-4f26-a647-fe1dcce9d258" />
<img width="1277" height="716" alt="Screenshot 2026-02-28 160110" src="https://github.com/user-attachments/assets/431b5c59-3567-4bcf-90e6-d0521889a842" />
<img width="1280" height="719" alt="Screenshot 2026-02-28 160148" src="https://github.com/user-attachments/assets/b9672af6-0776-4504-81a4-0d806f2e5287" />

# 📂 How to Use

1.Download the .pbix file
2.Open in Power BI Desktop
3.Use slicers to filter:
  Month
  Store
  Product Group
  Price range
4.Explore interactive visuals

# 📬 Contact

If you’d like to discuss this project or collaborate:

LinkedIn: www.linkedin.com/in/r-madhu-sudhanan1711

Email: madhusudhananr2000@gmail.com
