📊 Customer Shopping Behavior Analysis

End-to-End Data Analytics Project

Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases to uncover patterns in spending, customer segments, product preferences, and subscription behavior. The objective is to deliver data-driven insights that help improve sales performance, customer engagement, and long-term loyalty.

The project follows a complete analytics lifecycle — from data preparation and SQL analysis to interactive dashboards and executive-level reporting.

Business Problem:

A retail company wants to better understand how customers shop across demographics, product categories, and purchasing behaviors. Leadership is particularly interested in identifying factors such as discounts, reviews, shipping preferences, subscriptions, and customer loyalty that influence purchasing decisions and repeat behavior.

Key Business Question:

How can consumer shopping data be leveraged to identify trends, improve customer engagement, and optimize marketing and product strategies?

Dataset:

Total Records: 3,900 purchases

Columns: 18

Data Type: Transactional retail data

Key Attributes:

Customer demographics (Age, Gender, Location, Subscription Status)

Purchase details (Item Purchased, Category, Amount, Season, Size, Color)

Shopping behavior (Discount Applied, Previous Purchases, Review Rating, Shipping Type)

Missing Data:

37 missing values in the Review Rating column

Tools & Technologies

Python (Pandas) – Data loading, cleaning, and EDA

SQL (MySQL) – Business analysis using structured queries

Power BI – Interactive dashboards and KPIs

Gamma – Executive-style report and presentation creation

Project Workflow:
1. Data Loading & Exploration (Python)

Imported raw dataset using Pandas

Reviewed data structure and summary statistics

Identified missing values and inconsistencies

2. Data Cleaning & Feature Engineering

Imputed missing Review Rating values using median ratings

Standardized column names for readability

Created new features:

Age Groups

Purchase Frequency

Removed redundant fields to ensure data consistency

3. Database Integration

Loaded cleaned data into a relational database

Structured tables to simulate business transactions

4. SQL Analysis

Executed SQL queries to answer key business questions, including:

Revenue comparison by gender

Identification of high-spending customers using discounts

Top-rated products by customer reviews

Impact of shipping type on purchase value

Subscriber vs. non-subscriber spending behavior

Customer segmentation (New, Returning, Loyal)

Revenue contribution by age group

5. Visualization & Dashboarding (Power BI)

Built an interactive dashboard with filters and drill-downs

Designed KPIs to track revenue, customer segments, and behavior trends

6. Reporting & Presentation

Created a structured analytical report summarizing insights

Developed an executive-ready presentation using Gamma to clearly communicate findings and recommendations

Dashboards:

The Power BI dashboard highlights:

Revenue and spending trends

Customer segmentation and loyalty distribution

Subscription and discount impact

Top-performing products and categories

Shipping preference analysis

Key Insights & Results:

Female customers generate slightly higher total revenue than male customers

Subscription customers account for a significant share of revenue and show higher loyalty

Express shipping users spend ~12% more per transaction

High-value customers often combine discount usage with higher-than-average spend

Strong opportunity exists to convert New → Returning → Loyal customers

Business Recommendations:

Promote subscription benefits to increase repeat purchases

Strengthen loyalty programs for high-value customers

Optimize discount strategies to protect margins

Highlight top-rated products in marketing campaigns

Target high-spend segments and express shipping users
