Customer Shopping Behavior Analysis
📌 Project Overview

This project analyzes customer shopping behavior using transactional retail data. The workflow includes data preprocessing in Python, storing cleaned data in MySQL, performing SQL-based business analysis, and creating interactive dashboards in Power BI to generate actionable business insights.

The project demonstrates a complete end-to-end data analytics pipeline from raw dataset processing to business intelligence reporting.

📊 Objectives
Analyze customer purchasing behavior and spending patterns
Identify high-value customers and top-performing products
Compare subscriber vs non-subscriber purchase trends
Evaluate the impact of discounts on customer purchases
Visualize insights through interactive Power BI dashboards

🛠️ Technologies Used
Python
Pandas
NumPy
MySQL Connector
MySQL
SQL Queries
Data Analysis
Power BI
Dashboard Creation
Data Visualization

📂 Dataset Information
Source: CSV Dataset
Rows: 3,900
Columns: 18
Main Features
Customer Demographics
Age
Gender
Location
Product Information
Item Purchased
Category
Purchase Amount
Size
Color
Purchase Behavior
Previous Purchases
Frequency of Purchases
Review Rating
Shipping Type
Discount & Subscription Details
Discount Applied
Promo Code Used
Subscription Status

🧹 Data Preprocessing
Performed data cleaning and preprocessing using Python:

Loaded dataset using Pandas
Checked dataset structure and statistics
Handled missing values in Review Rating column
Standardized column names
Created derived columns:
age_group
purchase_frequency_days
Connected Python with MySQL
Inserted cleaned dataset into MySQL database

🗄️ SQL Business Analysis
Performed multiple analytical SQL queries including:

Revenue analysis by gender
High-spending customers using discounts
Top-rated products
Shipping type comparison
Subscribers vs non-subscribers analysis
Top discounted products
Customer segmentation
Top products by category
Repeat buyers & subscription analysis
Revenue contribution by age group

📈 Power BI Dashboard
Created interactive dashboards in Power BI to visualize:

Revenue trends
Customer segmentation
Product performance
Discount impact
Subscriber behavior
Purchase patterns
🔍 Key Insights
Certain product categories generated higher revenue
Discounts increased purchase frequency
Subscribers showed more consistent purchasing behavior
Loyal customers contributed significantly to overall revenue
💡 Business Recommendations
Improve customer loyalty programs
Promote subscription benefits
Optimize discount strategies
Focus marketing on high-value customers
🚀 Project Workflow

CSV Dataset → Python Preprocessing → MySQL Database → SQL Analysis → Power BI Dashboard

📷 Dashboard Preview

Add Power BI dashboard screenshots here

📁 Project Structure
Customer-Shopping-Behavior-Analysis/
│
├── dataset/
├── python/
├── sql_queries/
├── powerbi_dashboard/
├── screenshots/
└── README.md

🎯 Conclusion\
This project demonstrates how Python, MySQL, and Power BI can be integrated to transform raw retail data into meaningful business insights and interactive visual analytics.


