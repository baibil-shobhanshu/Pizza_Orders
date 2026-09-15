# 🍕 Pizza Orders — SQL Data Analysis Project

## Overview

This project focuses on analyzing **pizza orders data using MySQL**.

The objective is to use SQL queries to explore order patterns, pizza performance, revenue, customer ordering behavior, and sales trends.

The project contains **14 SQL analysis questions**, covering basic to advanced SQL concepts such as aggregations, joins, grouping, subqueries, window functions, and common table expressions.

---

## Dataset

The project uses a pizza sales dataset containing information about:

* Orders
* Order dates and times
* Pizza types
* Pizza categories
* Pizza sizes
* Pizza prices
* Quantity ordered
* Revenue generated

The dataset is divided into multiple related tables, which are joined together where required to perform the analysis.

---

## Tool Used

* **MySQL**
* **SQL**

### SQL Concepts Used

* `SELECT`
* `WHERE`
* `GROUP BY`
* `ORDER BY`
* `HAVING`
* Aggregate Functions
* `JOIN`
* `CASE`
* Subqueries
* CTEs
* Window Functions
* Date and Time Functions
* `SUM()`
* `COUNT()`
* `AVG()`
* `MAX()`
* `RANK()`
* `SUM() OVER()`

---

## Business Questions & SQL Analysis

The following questions were solved using MySQL queries:

### 1. Total Number of Orders

Retrieve the total number of orders placed.

### 2. Total Revenue

Calculate the total revenue generated from pizza sales.

### 3. Highest-Priced Pizza

Identify the pizza with the highest price.

### 4. Most Common Pizza Size

Determine the most frequently ordered pizza size.

### 5. Top 5 Most Ordered Pizza Types

Identify the top 5 pizza types based on the total quantity ordered.

### 6. Total Quantity by Pizza

Join the necessary tables to determine the total quantity ordered for each pizza.

### 7. Total Quantity by Pizza Category

Analyze the total quantity of pizzas ordered for each pizza category.

### 8. Orders by Hour

Determine the distribution of orders throughout the day by analyzing the order hour.

### 9. Category-Wise Pizza Distribution

Join the relevant tables to analyze the distribution of pizzas across different categories.

### 10. Average Pizzas Ordered per Day

Group orders by date and calculate the average number of pizzas ordered per day.

### 11. Top 3 Pizza Types by Revenue

Identify the top 3 pizza types generating the highest revenue.

### 12. Pizza Contribution to Total Revenue

Calculate the percentage contribution of each pizza type to the overall revenue.

### 13. Cumulative Revenue Over Time

Analyze how revenue accumulates over time using SQL window functions.

### 14. Top 3 Pizza Types by Revenue Within Each Category

Determine the top 3 revenue-generating pizza types within each pizza category.

---

## Key Analysis Performed

The project analyzes several important business metrics, including:

* Total orders
* Total revenue
* Pizza prices
* Order quantities
* Popular pizza sizes
* Best-selling pizza types
* Category performance
* Hourly order patterns
* Daily order trends
* Revenue by pizza type
* Revenue contribution
* Cumulative revenue
* Top-performing pizzas within each category

---

## SQL Techniques Demonstrated

This project demonstrates practical SQL skills that are commonly used in **Data Analyst roles**.

### Data Aggregation

Used functions such as:

```sql
COUNT()
SUM()
AVG()
MAX()
```

to calculate business metrics.

### Joins

Used joins to combine information from multiple pizza-related tables and perform meaningful analysis.

### Grouping & Sorting

Used:

```sql
GROUP BY
ORDER BY
HAVING
```

to summarize and rank sales data.

### Date & Time Analysis

Used MySQL date/time functions to analyze:

* Orders by date
* Orders by hour
* Daily pizza volume

### Window Functions

Window functions were used for advanced analysis such as:

* Ranking pizzas
* Calculating cumulative revenue
* Finding top-performing pizzas within each category
* Calculating revenue contribution

---
## Results

The analysis provides insights into pizza sales performance, customer ordering patterns, and revenue distribution.

The project helps identify:

* The overall volume of pizza orders
* Total revenue generated
* Most popular pizza sizes
* Best-selling pizza types
* Highest-revenue pizza types
* Best-performing pizza categories
* Peak ordering hours
* Daily order patterns
* Revenue contribution by pizza type
* Cumulative revenue growth
* Top pizzas within each category

These insights can help a business understand **customer preferences, sales performance, and revenue drivers**.

---

## Skills Demonstrated

* SQL
* MySQL
* Data Analysis
* Data Aggregation
* Data Cleaning through SQL
* Joins
* Subqueries
* CTEs
* Window Functions
* Date & Time Analysis
* Business Problem Solving
* Analytical Thinking

---

## Conclusion

The **Pizza Orders SQL Analysis Project** demonstrates an end-to-end analytical workflow using MySQL.

By solving 14 business-oriented questions, the project showcases the ability to transform raw sales data into meaningful insights using SQL.

This project is particularly relevant for a **Data Analyst portfolio** because it demonstrates practical SQL skills along with the ability to solve real-world business questions.
