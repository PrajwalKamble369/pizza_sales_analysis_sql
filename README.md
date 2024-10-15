# Pizza Sales Analysis

## Overview
This project analyzes pizza sales data using SQL to uncover key insights into orders, revenue, and customer preferences. By leveraging SQL queries, we explore trends in sales performance, top-selling pizzas, customer behaviors, and order patterns. The analysis aims to provide actionable insights for optimizing sales strategies and enhancing business growth.

## Table of Contents
1. [Project Description](#project-description)
2. [Technologies Used](#technologies-used)
3. [Key Insights](#key-insights)
4. [Database Structure](#database-structure)
5. [SQL Queries](#sql-queries)
6. [Setup Instructions](#setup-instructions)
7. [Conclusion](#conclusion)

## Project Description
This project delivers a comprehensive analysis of pizza sales data with a focus on identifying:
- Top-selling pizzas and sizes
- Daily and cumulative revenue trends
- Customer preferences across various pizza categories
- Order patterns by time of day
- Performance of different pizza categories (Classic, Supreme, Veggie, Chicken)

## Technologies Used
- **SQL**: Structured Query Language for querying the database
- **MySQL**: Relational database management system used to store and manage sales data
- **MySQL Workbench**: SQL client for running queries and analyzing results

## Key Insights
- **Total Orders**: 21,350 orders were placed, generating a total revenue of $817,860.05.
- **Top-Selling Pizzas**: The most ordered pizzas were Classic Deluxe, Barbecue Chicken, Hawaiian, Pepperoni, and Thai Chicken.
- **Popular Sizes**: The most popular sizes ordered were S, M, L, XL, and XXL.
- **Order Timing**: Insights into the time of day orders are placed, helping optimize staffing and operations.
- **Revenue Breakdown**: Analysis of pizza category contributions to overall sales, with a focus on Classic, Supreme, Veggie, and Chicken pizzas.

## Database Structure
The database consists of the following tables:
- **Orders**: Contains details of each order placed (order ID, date, customer ID).
- **Pizzas**: Includes pizza types, sizes, and prices.
- **Order Details**: Links orders to pizzas (order ID, pizza ID, quantity).
- **Customers**: Information about the customers (customer ID, name, location).

## SQL Queries
Key SQL queries used in the analysis include:
1. **Top-Selling Pizzas**: Query to identify the most frequently ordered pizzas.
2. **Revenue by Day**: Query to show daily sales performance.
3. **Customer Preferences**: Query to analyze customer order patterns based on pizza categories.
4. **Revenue Breakdown**: Query to calculate total and category-wise revenue.


## Conclusion
This project demonstrates how SQL can be effectively used to analyze sales data, identify trends, and provide actionable business insights. The results help optimize sales strategies, improve customer satisfaction, and boost revenue for a pizza chain.


