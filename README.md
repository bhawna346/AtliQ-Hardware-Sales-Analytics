# AtliQ-Hardware-Sales-Analytics
Interactive Power BI dashboard for AtliQ Hardware sales analysis, featuring revenue, sales quantity, customer, product, market, and time-based insights using SQL data.
# AtliQ Hardware Sales Analytics Dashboard | Power BI

## 1. Project Overview

The **AtliQ Hardware Sales Analytics Dashboard** is an interactive business intelligence project developed using Microsoft Power BI. It provides insights into sales performance, revenue generation, customer behavior, product performance, and market-wise sales distribution.

The dashboard helps transform raw sales data into meaningful visual insights, enabling businesses to monitor key performance indicators (KPIs) and make data-driven decisions.

## 2. Business Problem

Businesses need a clear understanding of their sales performance across different markets, customers, products, and time periods. Analyzing raw data manually can make it difficult to identify trends, compare performance, and recognize growth opportunities.

This project addresses these challenges by presenting sales data through an interactive dashboard with visualizations and filters.

## 3. Project Objectives

* Analyze overall revenue and sales quantity.
* Compare sales performance across different markets.
* Identify top-performing customers.
* Analyze product-wise revenue and sales trends.
* Track revenue over time.
* Compare revenue and sales quantity across year-quarter periods.
* Enable interactive exploration using date and year filters.

## 4. Tools and Technologies

* **Microsoft Power BI Desktop** – Dashboard development and data visualization.
* **Power Query** – Data transformation and preparation.
* **DAX (Data Analysis Expressions)** – Measures and calculations.
* **SQL / MySQL** – Database and source data.
* **Data Modeling** – Organizing data tables and relationships.

## 5. Dashboard Features

### KPI Cards

* Total Revenue
* Total Sales Quantity

### Market Analysis

* Revenue by market
* Sales quantity by market
* Comparison of market-wise performance

### Customer Analysis

* Top 5 customers by revenue
* Identification of high-value customers

### Product Analysis

* Top 5 products by revenue
* Product-wise sales performance

### Time-Based Analysis

* Revenue trends by year, quarter, month, and day
* Revenue and sales quantity comparison by year-quarter
* Year and date slicers for interactive filtering

### Market Distribution

* Visualization of product-code counts across markets

## 6. Dataset and Database

The project uses a sales database containing information related to customers, dates, products, markets, and sales transactions.

The SQL database export is provided in `db_dump.sql`.

The database includes tables such as:

* **customers** – Customer codes, customer names, and customer types.
* **date** – Dates, calendar year, month names, and date labels.

Additional sales-related tables provide data for revenue, sales quantity, products, and market analysis.

## 7. Key Performance Indicators

The dashboard focuses on the following metrics:

* Total Revenue
* Total Sales Quantity
* Market-wise Revenue
* Market-wise Sales Quantity
* Customer-wise Revenue
* Product-wise Revenue
* Revenue Trends Over Time

## 8. Repository Contents

* `Atlik hardware PowerBI.pbit` – Power BI dashboard template.
* `db_dump.sql` – SQL database export.
* `README.md` – Project documentation.

## 9. How to Use the Project

1. Clone or download this repository.
2. Import `db_dump.sql` into a compatible MySQL environment.
3. Open the `.pbit` file using Power BI Desktop.
4. Configure the required data source connection.
5. Refresh the data after connecting to the database.
6. Explore the dashboard using the available slicers and visualizations.

**Note:** The Power BI template may require database connection details and parameter configuration before it can load data.

## 10. Learning Outcomes

Through this project, I explored:

* Building interactive Power BI dashboards.
* Creating KPI cards and analytical visualizations.
* Transforming data using Power Query.
* Working with DAX measures.
* Connecting Power BI with SQL databases.
* Analyzing sales performance and business trends.
* Presenting data-driven insights through visual storytelling.

## 11. Conclusion

The AtliQ Hardware Sales Analytics Dashboard demonstrates how business intelligence tools can transform sales data into actionable insights. By combining SQL data with Power BI visualizations, the project provides an interactive way to explore revenue, customer performance, product trends, and market-level sales.

---

**Project Category:** Data Analytics | Business Intelligence

**Tools:** Power BI, Power Query, DAX, SQL, MySQL
