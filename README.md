# SQL-Business-Analytics-Project

## Overview
This project analyzes the Sakila DVD/CD rental dataset, which represents sales and rental transactions of a rental store operating with two branches. The objective of this project is to extract business insights from transactional data using SQL, focusing on revenue trends, customer behavior, store performance, and category-level demand.

## Data Source
Sakila dataset
https://dev.mysql.com/doc/index-other.html


## Key Analyses Performed
- Store Performance
- Top Customers & Revenue Contribution
- Ranked customers by revenue
- Customer concentration
- Time-Based Revenue Trend
- Revenue grouped by month/year
- Data gaps identified due to limited operational months
- Category Demand Insight


## Tools Used
- SQL (MySQL)
- Joins (INNER, LEFT)
- Aggregations (SUM, COUNT, AVG)
- Subqueries
- CTEs
- Window Functions
- RANK(), ROW_NUMBER()
- LAG() for MoM change
- Time-based grouping (YEAR(), MONTH())

## Usage
- Load the Sakila dataset in MySQL
- Execute SQL queries from the notebook
- Review outputs and insights section

```bash
 pip install ipython-sql mysql-connector-python
