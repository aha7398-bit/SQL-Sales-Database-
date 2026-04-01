# SQL-Sales-Database-
This will be a SQL database where you can write queries for "Total Revenue" or "Monthly Sales Trends".
**Overview**

This project focuses on analyzing sales data using SQL to generate meaningful business insights. A relational database was designed to store customer, product, and order information, allowing for efficient querying and analysis of sales performance, customer behavior, and product trends.

The goal of this project is to demonstrate core data analytics skills using SQL, including data modeling, querying, and extracting actionable insights.

**Dataset**

The dataset consists of simulated sales data, including:

Customer information (name, region)
Product details (name, category, price)
Orders and transaction data (order date, quantity purchased)

The data is structured across multiple related tables to reflect a real-world business environment.

**Database Structure**

The project uses a relational database with the following tables:

customers – stores customer details
products – stores product information and categories
orders – stores order-level data (date, customer)
order_details – stores product-level transaction details (quantity, product per order)

These tables are connected using primary and foreign keys to ensure data integrity.

**Business Questions Answered**

This project answers key business questions such as:

What is the total revenue generated?
How do sales trends change over time (monthly revenue)?
Which products and categories perform the best?
Who are the top customers based on total spending?
Which regions generate the most revenue?

**Key SQL Skills Demonstrated**

Joins (INNER JOIN across multiple tables)
Aggregations (SUM, COUNT, AVG)
Grouping & Filtering (GROUP BY, ORDER BY, WHERE)
Subqueries & CTEs
Window Functions (RANK, ROW_NUMBER)
Conditional Logic (CASE WHEN)

**Key Insights**

Identified top-performing products and categories contributing the most revenue
Analyzed monthly sales trends to understand seasonality
Ranked customers based on total spending to highlight high-value customers
Evaluated regional performance to identify strong and weak markets  

**Tools Used**

SQL (MySQL / PostgreSQL / SQLite)
Excel (for initial dataset preparation)
(Optional) Tableau / Power BI for visualization

**Future Improvements**

Integrate real-world datasets for deeper analysis
Build a fully interactive dashboard
Add predictive analytics (sales forecasting)
Connect to a live database instead of static data

**How to Run**

Create the database using the provided SQL schema
Import or insert the dataset into the tables
Run the SQL queries in the queries.sql file
(Optional) Connect to a visualization tool for dashboard creation

**Project Purpose**

This project was created to showcase SQL and data analysis skills for entry-level data analyst roles. It highlights the ability to work with structured data, answer business questions, and communicate insights effectively.
