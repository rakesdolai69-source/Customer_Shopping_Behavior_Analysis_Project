# 🛒 Customer Shopping Behavior Analysis – End-to-End Data Analytics Project

📌 Overview : 
This project analyzes customer shopping behavior using transactional data from 3,900 purchases across various product categories.

The goal is to uncover insights related to:
Spending patterns
Customer segmentation
Product preferences
Subscription behavior

These insights help support strategic business decisions, improve customer targeting, and optimize product performance.

📁 Dataset

Source: Transactional purchase dataset
Records: 3,900 transactions

Contains:
Customer details
Product categories
Purchase amounts
Subscription status
Transaction dates

Purpose: Understand how customers shop and what factors influence spending and product choices

🛠 Tools & Technologies Used

Python – Data loading, EDA, cleaning
PostgreSQL – SQL-based analysis
Power BI – Dashboard & data visualization
Excel – Quick checks & data review
Gamma AI – Final PPT/report creation

🔍 Project Steps
1. Data Loading (Python)

Imported dataset using Pandas
Checked structure, null values, duplicates, and column types
Conducted initial observations on customer and product distribution

2. Exploratory Data Analysis (EDA)

Summary statistics for numerical and categorical variables
Spending patterns and category-wise trends
Customer segmentation indicators
Visualizations: histograms, bar charts, boxplots, correlation matrix

3. Data Cleaning

Handled missing data appropriately (median/mode/drop)
Treated outliers using IQR
Standardized formats (dates, categories, column names)
Removed duplicates and inconsistent records
Created new derived features to support deeper analysis

4. SQL Analysis (PostgreSQL)

Loaded the cleaned dataset into PostgreSQL to perform deeper queries:
Customer-level aggregation
Category-wise performance
High-value customers
Monthly spending trends
Subscription-based segmentation
Ranking and window functions for comparative insights

5. Power BI Dashboard

Created an interactive business dashboard including:
KPIs (total revenue, total customers, avg purchase value, subscription rate)
Category-wise performance visuals
Customer segmentation
Monthly and weekly spending trends
Filters for category, subscription type, and customer group

6. Final Report & PPT (Gamma AI)

Generated a clean business presentation
Highlighted major insights, KPIs, and recommendations
Explained customer segments and behavior patterns
Included actionable strategies based on trends


✅ Key Insights & Results

(Update with your actual findings — sample points added)
Customers with active subscriptions spend higher on average
Electronics and home essentials are the top performing categories
Weekends show higher purchase volume
A small group of high-value customers contributes a major portion of revenue
Younger customers (18–30 age range) tend to purchase more frequently
