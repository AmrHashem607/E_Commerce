# Egyptian E-Commerce Sales & Customer Analytics | Power BI

## Project Overview

This project focuses on analyzing the Egyptian e-commerce market using Microsoft Power BI. It transforms synthetic e-commerce data into interactive dashboards that provide insights into sales performance, product profitability, customer behavior, and operational efficiency.

The project simulates a real-world business environment to demonstrate how data analytics can support performance monitoring and data-driven decision-making.

**Note:** This project uses synthetic data created to simulate the Egyptian e-commerce market. It does not contain actual company or customer transaction records.

## Project Objectives

* Analyze overall sales and profit performance.
* Identify top-performing products and product categories.
* Understand customer purchasing behavior and repeat purchases.
* Evaluate order statuses, returns, and cancellations.
* Analyze delivery performance and seller revenue.
* Develop interactive dashboards to monitor key performance indicators (KPIs).

## Tools & Technologies

* **Microsoft Power BI** — Dashboard development and data visualization.
* **Power Query** — Data cleaning and transformation.
* **DAX** — Calculated measures and KPI development.
* **Data Modeling** — Establishing relationships between multiple datasets.
* **Business Intelligence** — Performance analysis and business reporting.

## Dataset Overview

The project uses synthetic data designed to represent an Egyptian e-commerce business.

| Dataset     | Records | Description                                           |
| ----------- | ------: | ----------------------------------------------------- |
| Customers   |  50,000 | Customer details and geographic information           |
| Sellers     |   1,000 | Seller information                                    |
| Products    |   5,000 | Product details, categories, and pricing              |
| Orders      | 120,000 | Order dates, statuses, and delivery information       |
| Order Items | 187,560 | Products purchased, quantities, prices, and discounts |
| Payments    | 120,000 | Payment information                                   |
| Reviews     |  86,655 | Customer reviews and ratings                          |

**Date Range:** January 2024 – June 2026
**Market:** Egypt
**Currency:** Egyptian Pound (EGP)

## Dashboard Pages

### 1. Executive Overview

Provides a high-level overview of business performance.

Key metrics and analysis:

* Total Revenue
* Total Orders
* Total Customers
* Total Profit
* Average Order Value
* Revenue trends and category performance

### 2. Sales & Product Analysis

Focuses on product and sales performance.

Key analysis:

* Revenue and profit by product category
* Top 10 products by revenue
* Discount and profitability analysis
* Product performance across governorates

### 3. Customer Analytics

Explores customer behavior and purchasing patterns.

Key analysis:

* Total and new customers
* Returning customers
* Repeat Purchase Rate
* Customer Lifetime Value
* Customer segmentation and revenue analysis

### 4. Operations & Performance

Evaluates order management and operational performance.

Key metrics and analysis:

* Delivered Orders
* Return Rate
* Cancellation Rate
* Average Delivery Time
* Orders by Status
* Delivery performance by governorate
* Seller revenue performance

## Data Preparation & Modeling

The project workflow included:

1. Importing multiple CSV datasets into Power BI.
2. Cleaning and transforming data using Power Query.
3. Preparing tables and establishing relationships within the data model.
4. Creating DAX measures to calculate business KPIs.
5. Designing interactive reports and visualizations.
6. Analyzing business performance across sales, customers, products, and operations.

## Key Skills Demonstrated

* Data Cleaning and Transformation
* Data Modeling and Relationships
* DAX Measures and KPI Development
* Sales and Profitability Analysis
* Customer Behavior Analysis
* Operational Performance Analysis
* Interactive Dashboard Design
* Business Intelligence and Data Visualization

## Repository Structure

```text
Egyptian-Ecommerce-Analytics-PowerBI/
│
├── Dataset/
│   ├── customers.csv
│   ├── sellers.csv
│   ├── products.csv
│   ├── orders.csv
│   ├── order_items.csv
│   ├── payments.csv
│   ├── reviews.csv
│   └── data_dictionary.csv
│
├── Dashboard_Screenshots/
│   ├── Executive_Overview.png
│   ├── Sales_Product_Analysis.png
│   ├── Customer_Analytics.png
│   └── Operations_Performance.png
│
├── Egyptian_Ecommerce_Analytics.pbix
└── README.md
```

*The structure above is a suggested layout. Update filenames and folders to match the files actually uploaded to the repository.*

## Business Value

This project demonstrates how an interactive business intelligence solution can bring together sales, product, customer, and operational data to help stakeholders monitor KPIs, identify performance patterns, and make more informed business decisions.

## Future Improvements

* Add SQL-based analysis for deeper exploration of the data.
* Develop customer segmentation using RFM analysis.
* Expand time-based analysis to identify seasonal trends.
* Improve KPI monitoring and business insight documentation.

## Author

**Amr Hashem**
Computer Engineering Student | Aspiring Data Analyst

**Skills:** Power BI | SQL | Excel | Data Analysis

---

If you find this project useful, feel free to explore the repository and share your feedback.
