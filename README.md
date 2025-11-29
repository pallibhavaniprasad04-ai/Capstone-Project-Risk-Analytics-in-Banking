#  📊 End-to-End Risk-Analytics-in-Banking Project – Python | MySQL | Power BI
## 📌 Project Overview

"This project is an end-to-end Data Analytics solution designed for the **Banking Domain**, focusing on **customer financial behavior, savings/checking patterns, risk categories, and loan insights**. The workflow includes data cleaning & EDA using Python, database design and SQL analysis in MySQL, and interactive dashboard development in Power BI."
*The goal is to transform raw banking data into actionable business insights that support decisions related to **customer risk profiling, financial product performance, and customer segmentation.**


![image alt](https://github.com/pallibhavaniprasad04-ai/Zepto---Sales-Profits-Analysis--Power-BI/blob/main/Screenshot%202025-10-29%20220520.png)


## 🎯 Objectives
- #### 📊 Track Sales & Profit Trends – Analyze year-wise performance and identify growth patterns.
- ##### 🛒 Evaluate Product Categories – Find out which categories contribute the most to sales and profit.
- ##### 💰 Measure Profitability – Understand profit margin and profitability by category and city.
- ##### 📈 Calculate YoY Growth – Measure how the business performs year-over-year.
- ##### 📍 Support Decision-Making – Provide insights to management for better marketing, operations, and inventory planning.

## 🧰 Tools & Techniques
- **Tool Used:** Power BI  
- **Dataset:**  Sales Dataset (Sample / Kaggle)  
- **Domain:** Sales & Business Intelligence
- **PowerPoint** – for presentation and storytelling

## ⚙️ Project Workflow
### 1️⃣ **Import Data to Power BI**
Gathered Zepto sales data (2020–2024) including Order Date, Category, Product, Sales Amount, and Profit.


### 2️⃣ **Edit Data in Power Query Editor**
- Performed data cleaning and transformation.
  Removed duplicates, corrected missing values, formatted dates, and calculated total profit fields.

### 3️⃣ **Create Columns & Measures (DAX)**
- Created calculated measures for:
  - **Total Sales**  
  - **Total Profit**  
  - **Profit % = (Profit / Sales) × 100**
  - **YOY Growth = DIVIDE([Total Sales]-[Previous Year Sales],[Previous Year Sales],0) * 100**

 ### 4️⃣ **Create Visuals**
  - ##### Built visuals for:
 - ##### Line Chart (Sales Trend),
 - #####  Pie Chart (Category Share),
 - #### Bar Chart (Top Products),
 - #### Table (City Wise Sales&Profits)
  - ##### Line&Column Chart (Region over Sales & Profits) 
  - #### and KPI Cards.


 ## 📊 Key Performance Indicators (KPIs)
 | KPI | Description |
 |------|--------------|
 |**Total Sales** –| total revenue across all years.|
 |**Total Profit** – |total net earnings|
 |**Profit Margin %** – |how efficiently we convert sales into profit.|
 |**YoY Growth %** – | measures business growth year over year.|
 |**Average Order Value**– | average sale per order.”|

 
## 📈 Dashboard Insights 
   
-   **Yearly Growth**:  Sales show a steady upward trend from 2020 to 2024, with noticeable spikes post-2022 indicating recovery and expansion.
-  **Product Category Impact**: Grocery and Dairy categories generate the largest portion of total sales, while Personal Care items yield the highest profit margins.    
-   **Profitability Insight**: Profit margin averages between 18–25% across years, showing stable operational efficiency.
-   **Top Products**: Top-performing products contribute the most total profit.
-   **YoY Growth**: Average YoY growth rate ranges between 12–18%, with 2023–2024 being the strongest performing year.
-  **Customer Buying Pattern**: Customers tend to buy daily-use items (like milk, snacks, and groceries) repeatedly.


## 🚀 Business Impact

- #### 1. Focus on high-performing categories (Grocery, Dairy, Personal Care)-- continue promoting combo offers or subscription models..
- #### 2. Optimize pricing strategies and discounts to improve margins.
- #### 3. Strengthen presence in top-performing cities and expand to Tier-2 markets.
- #### 4. Improve inventory and supply chain planning using forecasting models.
- ##### 5. Monitor YoY growth and address sales dips through data-driven campaigns.
- #### 6. Improve Customer Experience Offer loyalty rewards or cashback to returning customers.
- #### 7. Marketing Improvements Run category-specific ads — for example, “Best Dairy Deals” or “Personal Care Offers.”
**In Short: Grow Profits where sales are booming , grow sales where profits are strong, fix systemic damage issues, and leverage seasonality.**


---
👤 Author

- Bhavaniprasad Palli
- Data Analyst | Power BI | Excel | SQL | Python
- 📧 pallibhavaniprasad04@gmail.com

- 🔗 www.linkedin.com/in/palli-bhavaniprasad



#
📌 Overview


#*

# 🚨 Problem Statement

** Banks generate large volumes of customer and transaction data, but struggle to identify risk segments, understand customer behavior, and monitor financial product usage effectively.*
**Without a structured analytics pipeline, insights remain hidden in raw datasets, making it difficult to improve customer targeting, reduce risk, and support financial decisions.*

# This project solves the problem by:

*1.Cleaning and preparing raw banking data*
*2.Performing EDA to understand patterns and correlations*
*3.Storing structured tables in MySQL for efficient querying*
*4.Building Power BI dashboards for easy business interpretation*

# 🛠️ Tech Stack

*Python: Pandas, NumPy, Matplotlib, Seaborn*
*MySQL: Database design, SQL CRUD, Aggregations, Joins*
*Power BI: Data modeling, DAX, Visualizations, KPIs*
*Tools: Jupyter Notebook, Power BI Desktop, MySQL Workbench*

# 🔍 Key Features

*Cleaned & processed banking dataset with Python*
*Univariate, bivariate & multivariate analysis*
*SQL queries for customer segmentation & risk analysis*
*Power BI dashboard for interactive financial insights*
*Relationship modeling between banking products*
*Data storytelling with KPIs and visuals*

# 📊 Key Insights

**Majority of customers fall under Risk Rating 1 & 2, showing a low-to-moderate risk profile.*
**Strong correlation identified between Savings Accounts and Checking Accounts.*
**High-income customers show higher product engagement, including loans and foreign currency accounts.*
**Younger customers have lower savings but higher credit card usage.*
**Certain customer segments exhibit higher loan-to-income ratios, indicating potential risk.*

# 💡 Recommendations

**Target mid-income customers for cross-sell opportunities (cards, loans, savings).*
**Improve risk-scoring models using derived metrics like Loan-to-Income Ratio.*
**Provide personalized offers for younger customers to improve savings engagement.*
**Monitor high-risk customers' credit behavior more closely.*
