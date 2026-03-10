# Northwind Sales Performance Dashboard

## Project Overview
This project presents an interactive Power BI dashboard analyzing sales performance for Northwind Traders, a specialty food import/export company.  
The dashboard helps stakeholders monitor revenue trends, identify top-performing products and customers, and evaluate shipping cost efficiency.

## Dashboard Preview
![Dashboard](Northwind%20sales%20dashboard.png.png)

## Business Problem
Northwind Traders manages a diverse catalog of products across global markets. Despite having rich transactional data, the company lacked a unified dashboard to answer key business questions such as:

- Are sales increasing or declining over time?
- Which products generate the most revenue?
- Who are the most valuable customers?
- Are shipping providers cost efficient?
- How does performance change across categories, countries, or years?

## Goal of the Dashboard
The goal of this project was to build a **single-page interactive dashboard in Power BI** that provides a clear overview of sales performance and enables users to explore data using filters.

The dashboard helps:
- Track overall business performance using KPIs
- Identify revenue trends over time
- Discover top-performing products and customers
- Analyze shipping costs by provider
- Detect revenue from discontinued products

## Dataset Overview

| Table | Description |
|------|-------------|
| orders | 830 orders placed between July 2013 – May 2015 |
| order_details | Line items including price, quantity, and discount |
| customers | 91 customers across multiple countries |
| products | 77 products across 8 categories |
| categories | Product category information |
| shippers | 3 shipping providers |

Dataset: **Northwind Traders dataset**

## Key Dashboard Metrics

- **Total Revenue:** $1.27M  
- **Total Orders:** 830  
- **Total Customers:** 91  
- **Average Shipping Cost:** $78.24  

## Key Visualizations

**1. Monthly Revenue Trend**  
Line chart showing revenue trends across months to identify growth or seasonal dips.

**2. Top Products by Revenue**  
Bar chart highlighting the highest revenue generating products.

**3. Top Customers by Revenue**  
Treemap visual showing customers contributing the most to total revenue.

**4. Average Shipping Cost by Provider**  
Comparison of shipping providers to evaluate cost efficiency.

**5. Revenue from Discontinued Products**  
Highlights revenue generated from discontinued products to identify replacement opportunities.

## Key Insights

- Côte de Blaye generates approximately **11% of total revenue**, making it the top-performing product.
- A small group of customers contributes a large portion of total sales.
- Certain discontinued products previously generated significant revenue.
- Some shipping providers have higher average freight costs than others.

## Tools Used

- **Power BI Desktop** – Dashboard development and visualization  
- **Power Query** – Data cleaning and transformation  
- **DAX** – KPI calculations and measures  
- **CSV files** – Northwind dataset

## Skills Demonstrated

- Data cleaning and transformation
- Data modeling in Power BI
- DAX calculations
- Business data analysis
- Interactive dashboard design
