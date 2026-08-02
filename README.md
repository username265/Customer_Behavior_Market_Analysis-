# Customer_Behavior_Market_Analysis-
Customer Shopping Behavior Analysis — end-to-end retail analytics project using Python (data cleaning &amp; feature engineering), PostgreSQL (business-question SQL analysis), and Power BI (interactive dashboard) to uncover trends in customer demographics, spending, and loyalty, with actionable marketing recommendations.


# Project Overview

End-to-end analysis of retail customer shopping behavior, built to help a retail company understand purchasing patterns, boost customer engagement, and optimize marketing and product strategy. The project covers the full data pipeline: Python for data cleaning and feature engineering, SQL (PostgreSQL) for structured business-question analysis, and Power BI for an interactive stakeholder dashboard.

# Business question: How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?

# Dataset
3,900 customer transactions across 18 columns
Demographics: Age, Gender, Location, Subscription Status
Purchase details: Item Purchased, Category, Purchase Amount, Season, Size, Color
Behavioral signals: Discount Applied, Promo Code Used, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type
Pipeline

# 1. Data Preparation (Python / pandas)

Cleaned and explored the raw dataset (df.info(), df.describe())
Imputed 37 missing Review Rating values using category-level medians
Standardized column names to snake_case
Engineered age_group (binned) and purchase_frequency_days
Dropped redundant promo_code_used column
Loaded the cleaned dataset into PostgreSQL

# 2. Data Analysis (SQL / PostgreSQL)
Answered 10 structured business questions, including:

Revenue by gender, subscription status, and age group
High-spending discount users
Top-rated and discount-dependent products
Customer segmentation (New / Returning / Loyal)
Repeat buyer and subscription correlation
Top products per category, shipping type comparison

# 3. Visualization (Power BI)
Interactive dashboard featuring:

KPI cards: total customers, avg purchase amount, avg review rating
Subscription status breakdown (donut chart)
Revenue and sales by category and age group
Slicers for Subscription Status, Gender, Category, and Shipping Type

# Key Findings
Male customers generated significantly more revenue than female customers
Young Adults are the highest-revenue age group, though the gap across age groups is relatively narrow
Loyal customers make up the vast majority of the base (3,116 of 3,900)
Only 27% of customers are subscribers, despite subscribers showing comparable average spend to non-subscribers

# Recommendations
Boost subscription enrollment through targeted incentives
Build loyalty programs to convert Returning/New customers into Loyal
Reassess discount policy to protect margins on discount-dependent products
Feature top-rated and best-selling products in marketing campaigns
Focus targeted marketing on high-revenue age groups and express-shipping users

# Tech Stack
Python (pandas) · PostgreSQL · Power BI




