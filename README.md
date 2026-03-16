# SQL Data Analysis Project

## Project Overview

This project demonstrates how SQL can be used to perform **exploratory data analysis and business intelligence reporting** on a sales dataset.

The objective of the project is to analyze **customer, product, and sales data** to extract meaningful insights that support **data-driven decision making**.

The analysis includes multiple SQL techniques such as **data exploration, trend analysis, ranking, cumulative calculations, performance evaluation, and reporting**.

---

# Dataset Description

The project uses a structured dataset containing **customer, product, and sales information**.

| Table             | Description                                                                          |
| ----------------- | ------------------------------------------------------------------------------------ |
| **dim_customers** | Contains customer demographic information such as customer ID and other attributes.  |
| **dim_products**  | Stores product-related information including product names and categories.           |
| **fact_sales**    | Contains transactional sales data such as order details, quantity, and sales amount. |

These tables allow analysis of **customer behavior, product performance, and overall sales trends**.

---

# Project Structure

```
datasets/
    flat-files/
        dim_customers.csv
        dim_products.csv
        fact_sales.csv

docs/
    Project Roadmap.pdf
    Project Roadmap.png

scripts/
    01_database_exploration.sql
    02_dimension_exploration.sql
    03_date_range_exploration.sql
    04_measures_exploration.sql
    05_magnitude_analysis.sql
    06_ranking_analysis.sql
    07_change_over_time_analysis.sql
    08_cumulative_analysis.sql
    09_performance_analysis.sql
    10_data_segmentation.sql
    11_part_to_whole_analysis.sql
    12_report_customers.sql
    13_report_products.sql
```

---

# Key SQL Analysis Performed

### Database Exploration

Initial exploration of the database to understand the structure, tables, and available columns.

### Dimension Exploration

Analysis of **customer and product dimensions** to understand available attributes.

### Date Range Analysis

Examining the **time span of the dataset** and identifying the earliest and latest transactions.

### Measures Exploration

Analyzing key metrics such as:

* Total sales
* Total orders
* Total quantity sold

### Magnitude Analysis

Evaluating the **scale and distribution of sales** across products and customers.

### Ranking Analysis

Ranking products and customers based on **sales performance**.

### Change Over Time Analysis

Analyzing how sales change across **months and years**.

### Cumulative Analysis

Computing **running totals and cumulative sales metrics** over time.

### Performance Analysis

Measuring business performance using **aggregated sales indicators**.

### Data Segmentation

Grouping customers or products into **different segments based on behavior or sales patterns**.

### Part-to-Whole Analysis

Determining the **contribution of individual products or customers** to total sales.

### Customer Report

Generating a **summary report of customer performance**.

### Product Report

Generating a **detailed report of product sales performance**.

---

# Skills Demonstrated

This project demonstrates practical SQL skills including:

* Data Exploration
* Aggregation Functions
* Window Functions
* Ranking Functions
* Cumulative Calculations
* Business Reporting Queries
* Analytical SQL Techniques

---

# Tools Used

* **SQL**
* **Relational Databases**
* **Data Analysis Techniques**
* **GitHub for Version Control**

---
