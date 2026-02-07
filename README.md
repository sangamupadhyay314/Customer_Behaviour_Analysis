# Customer Shopping Behavior Analysis
# Project Overview

This project focuses on analyzing customer shopping behavior using Python, SQL, and Power BI.
The goal is to clean raw customer data, perform exploratory and SQL-based analysis, and build an interactive dashboard to extract meaningful business insights such as revenue trends, customer preferences, and purchasing patterns.

# Dataset Information

File: customer_shopping_behavior.csv
Rows: 3900
Columns: 18

Key Columns:

Customer ID

Age

Gender

Item Purchased

Category

Purchase Amount (USD)

Location

Season

Review Rating

Subscription Status

Shipping Type

Discount Applied

Promo Code Used

Payment Method

Frequency of Purchases

# Tools & Technologies Used

Python (Pandas, sqlalchemy)

SQL (MySQL / SQLite)

Power BI

Jupyter Notebook

GitHub

# Data Cleaning (Python)

Performed in Data_Cleaning_Customer_Behavior.ipynb

Steps:

Removed duplicates

Handled missing values

Standardized column names

Checked data types

Cleaned categorical values

Exported clean dataset for SQL & Power BI

# SQL Analysis

Performed using:

Customer.sql

SQL Queries On Customer Behaviour Analysis.txt

Sample Business Questions Answered:

What is the total revenue generated?

Which product categories generate the highest revenue?

Top 5 most purchased products

Average review rating by product category

Customer distribution by location and gender

Impact of discounts and promo codes on purchases

Subscription vs non-subscription customer behavior

# Power BI Dashboard

Dashboard created using cleaned dataset to visualize:

Key Visuals:

Total Revenue KPI

Top Products by Sales

Category-wise Revenue

Customer Distribution by Gender & Location

Seasonal Purchase Trends

Payment Method Analysis

Subscription Status Comparison

Dashboard File: Customer_Behaviour_Dashboard.zip

📂 Project Structure
Customer-Shopping-Behavior-Analysis/
│
├── customer_shopping_behavior.csv
├── Data_Cleaning_Customer_Behavior.ipynb
├── Customer.sql
├── SQL Queries On Customer Behaviour Analysis.txt
├── Customer_Behaviour_Dashboard.zip
└── README.md

# How to Run the Project
1️1. Python Analysis
pip install pandas,sqlalchemy
jupyter notebook


Open:

Data_Cleaning_Customer_Behavior.ipynb

2️. SQL Analysis

Import CSV into SQL database

Run queries from:

SQL Queries On Customer Behaviour Analysis.txt

3️. Power BI Dashboard

Extract Customer_Behaviour_Dashboard.zip

Open .pbix file in Power BI Desktop

Refresh data source if needed

# Key Insights (Example)

Clothing and Footwear categories generate the highest revenue

Subscription customers purchase more frequently

Seasonal trends affect product demand

Promo codes increase purchase volume

Credit Card & PayPal are the most used payment methods

# Future Improvements

Add predictive analysis (ML model)

Customer segmentation (RFM analysis)

Automate dashboard refresh

Add more KPIs (CLV, churn rate)

Deploy dashboard online

# Author

Sangam Upadhyay
Data Analyst

# Acknowledgment

This project was created for learning and practicing:

Data Cleaning

SQL Analysis

Power BI Visualization

End-to-End Data Analytics Workflow
