# E-Commerce Sales Analysis Dashboard (Power BI)

## Overview

This project explores an e-commerce dataset using Power BI to understand sales performance, delivery efficiency, seller performance, and customer review behavior.

The goal of the dashboard is to provide a quick way to explore key business metrics and identify patterns in sales, logistics, and product performance.

The project focuses on transforming raw data into useful insights through data cleaning, modeling, and visualization.

## What This Dashboard Shows
The dashboard highlights several areas of the business:

* Seller performance and revenue contribution
* Delivery time differences across states
* Cities generating the highest sales
* Product category performance
* Relationship between product description length and customer review scores

These insights help identify operational issues and opportunities for improvement in logistics and product presentation.

## Tools Used

* Power BI Desktop
* Power Query (data cleaning and transformation)
* DAX (calculated measures)
* Data modeling
* Interactive visualizations

## Dataset

The analysis uses a multi-table e-commerce dataset that includes information about:

* Customers
* Orders
* Products
* Sellers
* Payments
* Reviews

The tables are connected using relationships to simulate a real transactional e-commerce system.

## Data Preparation

Before building the dashboard, the dataset was cleaned and prepared using Power Query.

Main preparation steps included:

* Handling missing values
* Removing duplicates
* Correcting data types
* Creating delivery time calculations
* Removing unnecessary columns
* Standardizing column names

These steps ensured the data was consistent and ready for analysis.

## Dashboard Components

### KPI Metrics

* Average Delivery Time
* Order Approval Time
* Credit Card Payment Growth

### Performance Analysis

* Top sellers by revenue
* Top cities by sales performance
* Average delivery time by state

### Geographic View

* Freight value by seller state (map visualization)

### Product Insights

* Comparison between product description length and review score

### Interactive Filters

* Product category filter to explore category-specific insights

## Key Observations

* Some states experience noticeably longer delivery times, suggesting possible logistics delays.
* A small number of sellers contribute a large share of total revenue.
* Major cities such as São Paulo account for a large portion of sales activity.
* Product descriptions with more detail tend to receive slightly better review scores.

---

## Dashboard Preview

![Dashboard](images/dashboard.png)

## Repository Structure

project-folder/

data/ → raw dataset files
images/ → dashboard screenshots
dashboard/ → Power BI (.pbix) file
README.md → project documentation

---

## Purpose of This Project

This project was created to practice and demonstrate:

* Data cleaning and preparation
* Building data models
* Writing DAX measures
* Designing clear and interactive dashboards

It is part of a portfolio focused on data analysis and business intelligence using Power BI.

---

## Running the Dashboard

1. Download the `.pbix` file from this repository.
2. Open the file using **Power BI Desktop**.
3. Load the dataset if required.
4. Use the filters and visuals to explore sales trends, delivery performance, and seller insights.

---

## Skills Applied

This project involved several core data analysis tasks:

* Cleaning and transforming raw data using Power Query
* Building relationships between multiple tables
* Creating calculated measures with DAX
* Designing interactive dashboard visuals
* Interpreting business metrics through data visualization

---

## Possible Improvements

Some ideas for extending this project in the future:

* Add time-based sales trend analysis
* Create more advanced DAX metrics for profitability
* Include customer segmentation analysis
* Expand the dashboard with additional KPIs

---

## Author

Suraj
B.Tech (AIML)
Interested in Data Analytics, Machine Learning, and Data Engineering

If you found this project useful or interesting, feel free to star the repository.

