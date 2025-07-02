# Walmart-Data-Analysis-SQL-Python-Project
This project is an end-to-end data analysis solution designed to extract critical business insights from Walmart sales data. We utilize Python for data processing and analysis, SQL for advanced querying, and structured problem-solving techniques to solve key business questions. The project is ideal for data analysts looking to develop skills in data manipulation and SQL querying.

## 1. Download Walmart Sales Data
Dataset : Walmart Sales Dataset downloaded from kaggle.
Storage: Save the data in the data/ folder for easy reference and access.
## 2. Explore the Data
Goal: Conduct an initial data exploration to understand data distribution, check column names, types, and identify potential issues.
Analysis: Use functions like .info(), .describe(), and .head() to get a quick overview of the data structure and statistics.
## 3. Data Cleaning
1. Remove Duplicates: Identify and remove duplicate entries to avoid skewed results.
2. Handle Missing Values: Drop rows or columns with missing values if they are insignificant; fill values where essential.
3. Fix Data Types: Ensure all columns have consistent data types (e.g., dates as datetime, prices as float).
4. Currency Formatting: Use .replace() to handle and format currency values for analysis.
5. Validation: Check for any remaining inconsistencies and verify the cleaned data.
## 4. Feature Engineering
1. Create New Columns: Calculate the Total Amount for each transaction by multiplying unit_price by quantity and adding this as a new column.
2. Enhance Dataset: Adding this calculated field will streamline further SQL analysis and aggregation tasks.
## 8. Load Data into MySQL and PostgreSQL
1. Set Up Connections: Connect to MySQL load the cleaned data into database.
2. Table Creation: Set up tables in both MySQL to automate table creation and data insertion.
3. Verification: Run initial SQL queries to confirm that the data has been loaded accurately.
## 9. SQL Analysis: Complex Queries and Business Problem Solving
1. Business Problem-Solving: Write and execute complex SQL queries to answer critical business questions, such as:
2. Revenue trends across branches and categories.
3. Identifying best-selling product categories.
4. Sales performance by time, city, and payment method.
5. Analyzing peak sales periods and customer buying patterns.
6. Profit margin analysis by branch and category.
7. Documentation: Keep clear notes of each query's objective, approach, and results.
