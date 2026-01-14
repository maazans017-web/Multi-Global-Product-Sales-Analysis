🌍 Global Sales Analysis | End-to-End Power BI & SQL Project
📌 Project Overview

The Global Sales Analysis project is an end-to-end business intelligence and analytics solution developed using SQL and Power BI. The objective of this project is to analyze multi-country sales data to identify regional performance, customer contribution, revenue trends, and market demand patterns that support strategic decision-making and business expansion.

This project demonstrates the complete analytics workflow — from raw data preparation and modeling to advanced DAX calculations, interactive dashboards, and executive-level insights.

🎯 Business Objective

The key business questions addressed in this project are:

Which countries and regions generate the highest revenue?

Which customers contribute the most to total sales?

How does sales performance vary across markets over time?

Which regions show the highest demand and growth potential?

The objective is to help leadership:

Identify high-performing markets

Plan regional expansion strategies

Focus on high-value customers

Improve marketing and sales targeting

🗂️ Data Source

The dataset used represents a global retail business, similar to enterprise-scale sales systems.

📄 Dataset Includes:

Order ID

Order Date

Customer ID and Customer Segment

Product ID, Product Category, Sub-Category

Sales Amount, Quantity, Profit

Country, Region, Market

📌 Data Type: Structured CSV files
📌 Granularity: Transaction-level sales data

🧹 Data Cleaning & Preparation

Data preparation was performed to ensure accuracy, consistency, and usability.

Key Steps:

Removed duplicate transaction records

Handled null values in customer and geographic fields

Validated revenue, quantity, and profit values

Standardized region and country names

Verified row counts before and after transformation

This ensured high-quality, analysis-ready data.

🛠️ Tools & Technologies Used

SQL – Data extraction, joins, aggregation, and validation

Power BI Desktop – Data modeling, visualization, and reporting

DAX (Data Analysis Expressions) – KPI calculations and dynamic metrics

Excel / CSV – Raw data storage

🧩 Data Modeling

An enterprise-level Star Schema was designed to support scalable reporting and efficient analytics.

⭐ Data Model Structure:

Fact Table:

Sales Transactions

Dimension Tables:

Date

Customer

Product

Geography (Country, Region, Market)

Segment

📌 This model supports:

Fast query performance

Simplified DAX logic

Scalability for large datasets

📐 DAX Measures Used

The following DAX measures were created to calculate key performance indicators:

Total Revenue
SUM(Sales[Sales Amount])

Total Orders
DISTINCTCOUNT(Sales[Order ID])

Total Customers
DISTINCTCOUNT(Customer[Customer ID])

Revenue by Region / Country
CALCULATE([Total Revenue], Geography Filters)

Top Customers by Revenue
RANKX(ALL(Customer), [Total Revenue])

Average Revenue per Customer
DIVIDE([Total Revenue], [Total Customers])

Time-Based Analysis
Monthly and yearly revenue trends using Date hierarchy

📊 Dashboard & Visualizations

An executive-level Power BI dashboard was created to provide a clear overview of global sales performance.

Visuals Included:

KPI Cards:

Total Revenue

Total Orders

Total Customers

Map Visual:

Revenue and demand by country and region

Bar Charts:

Top Countries by Revenue

Top Customers by Revenue

Line Charts:

Revenue trends over time

Box Plot / Distribution Visuals:

Revenue distribution across regions

Slicers:

Date

Region

Customer Segment

📌 All insights are accessible in a single-page executive dashboard.

🔍 Key Insights

A small number of regions and customers contribute a large portion of total revenue

Certain markets show consistently higher demand and growth potential

Revenue follows clear seasonal and regional patterns

Customer contribution varies significantly by region

📈 Business Impact

Based on the analysis:

High-performing regions can be prioritized for expansion

Marketing strategies can be tailored to high-value customer segments

Sales efforts can focus on profitable markets

Leadership can make data-driven investment decisions

✅ Conclusion

This project demonstrates the ability to:

Analyze large, multi-dimensional datasets

Design scalable data models

Build dynamic DAX measures

Deliver executive-ready dashboards

Translate global sales data into strategic business insights

The Global Sales Analysis project highlights strong capabilities in Business Intelligence, Customer Analytics, and Strategic Reporting, making it highly relevant for enterprise analytics and customer engagement roles.
