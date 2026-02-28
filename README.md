# Supermarket-Sales-Profit-Dashboard-Power-BI
# 📌 Project Overview

This project presents an interactive Power BI dashboard built using a Supermarket Sales dataset.
The objective is to transform raw transactional data into actionable business insights that support data-driven decision-making.

The dashboard focuses on:

1. Sales performance
2. Profitability analysis
3. Store comparison
5. Product group insights
4. Discount impact evaluation

# 🎯 Business Objectives

1. Identify top and bottom performing product groups,
   
3. Analyze monthly sales and profit trends
4. Compare store-level performance
5. Understand customer purchase behavior by price & quantity
6. Evaluate the impact of discounts on revenue and profit

# 🧰 Tools & Technologies Used

1. Microsoft Excel – Initial data handling
2. Power BI Desktop
3. Power Query (Data Cleaning & Transformation)
4. DAX (Data Analysis Expressions)
5. Data Modeling
6. Interactive Visualizations

# 📊 Dashboard Sections

1️⃣ Super Market Dashboard – Sales & Profit Insights

1. Profit by price and quantity
2. Profit trends by value
3. Sales performance across product groups
4. Discount impact analysis

2️⃣ Retail Pulse – Store & Sales Performance

1. Store-wise monthly sales comparison
2. Day-wise sales trends
3. Product group performance by store
4. KPI tracking

3️⃣ Sales & Profit Intelligence Hub

1. Net sales & profit by category
2. Sales by month (M1, M2, M3)
3. Quantity distribution analysis
4. Value vs discount insights

# 🔍 Key Features

✔ Sales & Profit Analysis

1. Track performance by:
2. Product group (SGRP)
3. Store code
4. Month (M1, M2, M3)
5. Unit price

✔ Top & Bottom Performers

Quickly identify: 

1. High-profit items
2. Low-performing categories
3. Stores with declining sales

✔ Customer Purchase Trends

Analyze:

1. Buying behavior across price ranges
2. Quantity-based purchasing patterns
3. Value contribution distribution

✔ Discount & Value Impact

Understand:

1. How discounts affect total sales value
2. Profit variation due to promotional strategies

✔ Store Performance Insights

Compare:

1. Store-wise total sales
2. Monthly store trends
3. Contribution to overall revenue

# 📈 Key Metrics Used

1. Total Sales Value
2. Net Sales
3. Profit Amount
4. Quantity Sold
5. Discount Amount
6. Store Code Count
7. Product Group Count

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

1. Advanced data transformation using Power Query
2. Writing optimized DAX measures
3. Building a structured data model
4. Designing clean and interactive dashboards
5. Converting data into strategic business recommendations

# 📷 Dashboard Preview

<img width="1275" height="719" alt="Screenshot 2026-02-28 160027" src="https://github.com/user-attachments/assets/c452cd32-0200-4f26-a647-fe1dcce9d258" />
<img width="1277" height="716" alt="Screenshot 2026-02-28 160110" src="https://github.com/user-attachments/assets/431b5c59-3567-4bcf-90e6-d0521889a842" />
<img width="1280" height="719" alt="Screenshot 2026-02-28 160148" src="https://github.com/user-attachments/assets/b9672af6-0776-4504-81a4-0d806f2e5287" />

# 📂 How to Use

1.Download the .pbix file
2.Open in Power BI Desktop
3.Use slicers to filter:
  * Month
  * Store
  * Product Group
  * Price range
    
4.Explore interactive visuals

# 📬 Contact

If you’d like to discuss this project or collaborate:

LinkedIn: www.linkedin.com/in/r-madhu-sudhanan1711

Email: madhusudhananr2000@gmail.com
