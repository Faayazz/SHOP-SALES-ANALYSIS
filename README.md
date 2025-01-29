# Power BI Project: Shop Sales Analysis

This project provides a detailed analysis of shop sales data, exploring various dimensions and key metrics.

## Project Overview

*   **Purpose:** This project aims to analyze shop sales data to gain insights into sales performance, customer behavior, and product profitability. The goal is to create an interactive report that helps stakeholders understand sales patterns and make data-driven decisions.

## Data Source(s)

*   The data for this project comes from a shop sales dataset. The dataset includes the following key fields:
    *   `Row ID`: Unique identifier for each row.
    *   `Order ID`: Unique identifier for each order.
    *   `Order Date`: Date when the order was placed.
    *   `Ship Date`: Date when the order was shipped.
    *   `Ship Mode`: Shipping method used for the order.
    *   `Customer ID`: Unique identifier for each customer.
    *   `Customer Name`: Name of the customer.
    *   `Segment`: Customer segment (Consumer, Corporate, Home Office).
    *   `Country/Region`: Country or region of the customer.
    *   `City`: City of the customer.
    *   `State`: State of the customer.
    *   `Postal Code`: Postal code of the customer.
    *   `Region`: Region of the customer (South, West, East, North, Central).
    *   `Product ID`: Unique identifier for each product.
    *   `Category`: Product category.
    *   `Sub-Category`: Product sub-category.
    *   `Product Name`: Name of the product.
    *   `Sales`: Sales amount for the order.
    *   `Quantity`: Quantity of products ordered.
    *   `Discount`: Discount applied to the order.
    *   `Profit`: Profit made on the order.
    * If dataset is in the repository mention it e.g., "The dataset is located in the `shop_sales_data.csv` file".

## Data Analysis and Visualizations

The project utilizes the following DAX functions and visualizations:

*   **DAX Functions:**
    *   `SUM()` is used to calculate the sum of sales, discount, profit and quantity.
*   **Visualizations:**
    *   **Pie Chart:** Used to visualize the sum of sales across different customer segments.
    *   **Funnel Chart:** Used to visualize the sum of sales by product sub-category.
    *   **Map:** Used to show sales distribution by country/region.
    *   **Donut Chart:** Used to visualize the sum of sales by region.
    *   **Card Visuals:** Used to display key metrics:
        *   Sum of Discount
        *   Sum of Quantity
        *   Sum of Sales
        *   Sum of Profit
    *   **Line Chart:** Used to show the trend of sum of sales by order date.

## Key Learnings

*   This project provided valuable experience in using data to understand business performance and sales trends. I learned how to analyze data from different perspectives to identify patterns, understand customer behavior, and evaluate the overall profitability of different products and regions.


## Usage

*   This report is designed to help sales managers, product managers, and other stakeholders understand the sales trends, regional sales performance, customer behavior, and product profitability, so that they can make data-driven decisions.
