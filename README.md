Superstore Sales Analysis using SQL 

Project Overview 

This project analyzes the Sample Superstore dataset using MySQL. The goal is to explore sales performance, profitability, customer segments, and regional trends using SQL queries. 

 

Dataset 

Sample Superstore Dataset 

Total Records: 9994 

Database: MySQL 

 

Skills Used 

SQL 

MySQL Workbench 

Aggregate Functions 

GROUP BY 

ORDER BY 

WHERE 

HAVING 

CASE 

LIMIT 

LIKE 

 

SQL Concepts Covered 

Data Exploration 

Data Filtering 

Sorting 

Aggregation 

Business Analysis 

Conditional Statements 

 

Business Questions Solved 

Total number of orders 

Total sales 

Total profit 

Average sales 

Highest sale 

Lowest sale 

Sales by region 

Profit by category 

Sales by state 

Top 10 states by sales 

Top products by sales 

High-value orders 

Loss-making orders 

California sales analysis 

Consumer segment analysis 

Sales by category 

Profit by region 

Average profit by state 

Categories with high sales 

Products with highest profit 

Cities starting with 'S' 

Profit/Loss classification 

Top profitable products 

Least profitable products 

Category-wise quantity sold 

Sales greater than 1000 

Technology category analysis 

Region-wise sales ranking 

State-wise sales comparison 

Top 5 profitable orders 

 

Sample Query 

SELECT Region, 
      SUM(Sales) AS Total_Sales 
FROM superstore 
GROUP BY Region 
ORDER BY Total_Sales DESC; 
 

 

Project Outcome 

Identified high-performing regions. 

Compared category-wise profitability. 

Found top-selling products. 

Analyzed customer segments. 

Generated business insights using SQL. 

 

Tools Used 

MySQL Workbench 

Microsoft Excel 

 

Author 

Nikhil R  

 
