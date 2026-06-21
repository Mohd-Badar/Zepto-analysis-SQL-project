# Zepto SQL Data Analysis Project

## Overview

This project analyzes a Zepto product dataset using SQL. The goal is to explore the data, clean it, and answer business-related questions using SQL queries.

## Tools Used

* PostgreSQL
* SQL
* GitHub

## Dataset Information

The dataset contains information about Zepto products, including:

* Product Name
* Category
* MRP
* Discount Percentage
* Selling Price
* Weight
* Available Quantity
* Stock Status

## Data Exploration

The following checks were performed:

* Total number of records
* Sample data inspection
* Null value detection
* Unique product categories
* In-stock vs out-of-stock products
* Duplicate product names

## Data Cleaning

The dataset was cleaned by:

* Identifying products with zero price
* Removing invalid records
* Converting price values from paise to rupees

## SQL Analysis Performed

### 1. Top Discounted Products

Found the products with the highest discount percentages.

### 2. High MRP Products Out of Stock

Identified expensive products that are currently unavailable.

### 3. Estimated Revenue by Category

Calculated potential revenue using selling price and available quantity.

### 4. Premium Products with Low Discounts

Found products with high prices but low discounts.

### 5. Categories with Highest Average Discount

Compared categories based on average discount percentage.

### 6. Price Per Gram Analysis

Calculated price per gram to identify better-value products.

### 7. Product Weight Classification

Classified products into:

* Low
* Medium
* Bulk

based on their weight.

### 8. Total Inventory Weight by Category

Calculated total inventory weight available in each category.

## Key Learnings

Through this project, I practiced:

* Data Cleaning
* Filtering and Sorting
* Aggregate Functions
* GROUP BY and HAVING
* CASE Statements
* Business-Oriented SQL Queries

## Project Files

* `Zepto_SQL_data_analysis.sql` - SQL queries used in the project
* `zepto_v1.csv` - Dataset file
* `README.md` - Project documentation

## Author

Mohd Badar
