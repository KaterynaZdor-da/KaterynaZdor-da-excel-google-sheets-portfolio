# Global Sales Analysis (Google Sheets Project)

## Project Overview

This project analyzes sales data from a global company operating in both **online and offline channels**.

The dataset contains information about orders, products, and countries across multiple years.
The goal of the analysis was to identify **sales patterns, regional performance, and the most profitable products**.

---

## Dataset

The project uses three datasets:

* **events.csv** — sales transactions
* **products.csv** — product categories and product codes
* **countries.csv** — countries, regions, and subregions

---

## Tools Used

* Microsoft Excel / Google Sheets
* Pivot Tables
* Data Cleaning
* Data Visualization
* ABC Analysis (Pareto Principle)

---

## Data Preparation

Several preprocessing steps were performed:

* Imported three datasets into a single workbook
* Checked data quality and consistency
* Removed missing or incorrect values
* Created calculated metrics:

**Total Revenue**
= Unit Price × Quantity

**Total Cost**
= Unit Cost × Quantity

**Total Profit**
= Revenue − Cost

---

## Key Business Metrics

The following metrics were calculated:

* Total number of orders
* Total revenue
* Total profit
* Number of countries with sales
* Sales distribution by channel (online vs offline)

---

## Sales Analysis

The analysis was performed across multiple dimensions:

### Product Categories

* popularity of product categories
* revenue and profit comparison

### Geographic Performance

Sales were analyzed by:

* countries
* regions
* subregions

### Sales Channels

Comparison between **online** and **offline** sales.

---

## Order Fulfillment Analysis

The time between **order date and shipping date** was analyzed to determine whether longer shipping times impact profit.

The analysis was performed across:

* product categories
* countries
* regions

---

## Time Trends

Sales dynamics were analyzed by:

* year
* month
* product category
* country
* region

This helped identify **seasonal patterns and long-term trends**.

---

## Weekly Sales Pattern

Sales distribution by **day of week** was analyzed using the Excel function:

WEEKDAY()

This helped identify the most active sales days.

---

## ABC Analysis

Products were categorized using **Pareto analysis** based on sales performance during the last year.

Products were grouped into:

* **Category A** — top performing products generating the majority of revenue
* **Category B** — moderately important products
* **Category C** — low impact products

---


---

## Project Files

* `sales_analysis.xlsx` — full Excel analysis
* `events.csv` — transaction data
* `products.csv` — product information
* `countries.csv` — geographic data
