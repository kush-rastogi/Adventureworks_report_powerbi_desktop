# Adventureworks_report_powerbi_desktop
# PowerBI Desktop project link: 
https://drive.google.com/file/d/1kHzV8c7MhP6ecVDHo5oginAoRG5vMB8l/view?usp=drive_link
# 🚴 AdventureWorks Sales & Customer Insights Dashboard
This Power BI project provides an end-to-end business intelligence solution for AdventureWorks Cycles, a global bicycle manufacturer. The dashboard offers comprehensive insights into sales performance, customer demographics, product trends, and return rates, enabling data-driven decision-making.

# 📊 Project Overview
Objective: Analyze AdventureWorks' sales and returns data to uncover key business insights.

Tools Used: Microsoft Power BI Desktop

Data Source: AdventureWorks sample dataset provided by Microsoft

# 🔧 Data Preparation
Data Import: Loaded multiple CSV files into Power BI, each representing different tables such as Sales, Returns, Products, Customers, and Geography.

Data Cleaning:

Ensured correct data types for all columns.

Renamed columns for clarity.

Verified data completeness; no missing values found.

Data Modeling:

Established relationships between tables, primarily using one-to-many relationships.

Created a star schema with fact and dimension tables.

# 🧠 DAX Calculations
Implemented various DAX functions to create meaningful metrics:

Key Measures:

Total Revenue

Total Profit

Total Orders

Return Rate

Advanced Calculations:

90-Day Rolling Profit using DATESINPERIOD

Previous Month Comparisons using CALCULATE and DATEADD

Product Return Analysis using RELATED to fetch data across tables

# 📈 Dashboard Pages
Executive Dashboard:

Overview of key performance indicators (KPIs) like revenue, profit, and orders.

Trend analysis over time.

Top-selling products list.

Slicers for year and continent to filter data dynamically.

Geographical Analysis:

Interactive map displaying order distribution by continent.

Insights into regional performance and potential market expansion opportunities.

Product Performance:

Detailed analysis of individual products.

Metrics include monthly revenue, profit, order volume, and return rates.

Identification of underperforming products due to high return rates.

Customer Insights:

Demographic breakdown of customers by occupation and income.

Customer acquisition trends over time.

Top 100 customers by revenue and order volume.

Analysis of customer value and purchasing behavior.

# 📌 Key Insights
The United States leads in total orders, followed by the Pacific region.

Certain products, like the "Road Tire Tube," exhibit high return rates, indicating potential quality issues.

High-value customers contribute significantly to revenue with relatively few orders, highlighting the importance of customer segmentation.

# Screenshot
![Screenshot 1](Screenshots/Screenshot(1).png)
![Screenshot 1](Screenshots/Screenshot(2).png)
![Screenshot 1](Screenshots/Screenshot(3).png)
![Screenshot 1](Screenshots/Screenshot(4).png)
