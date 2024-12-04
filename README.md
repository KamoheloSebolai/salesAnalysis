# Sales Analysis

# Project Overview

This project uses Python to analyze a sales dataset containing information on product sales, discounts, costs, and profits across different segments, countries, and time periods. The goal is to extract meaningful insights that could help improve sales strategies, optimize profits, and identify trends in product and regional performance.

# Data Overview
The dataset contains the following columns:

- Segment: Business segment (e.g., Government).
- Country: The country where the sale occurred.
- Product: The product sold.
- Discount Band: Discount category applied to the sale (e.g., Low, None).
- Units Sold: Number of units sold.
- Manufacturing Price: Cost to manufacture each unit.
- Sale Price: Sale price per unit.
- Gross Sales: Total sales before discounts.
- Discounts: Total discounts applied to sales.
- Sales: Total sales after discount application.
- COGS (Cost of Goods Sold): Cost to produce the goods sold.
- Profit: Profit made after subtracting COGS and discounts.
- Date: Date of the sale.
- Month Number: Numeric representation of the month (1-12).
- Month Name: Name of the month (e.g., January).
- Year: Year of the sale.

## **Installation** 
To run this project, you need to have Python installed along with the following libraries:

- pandas
- matplotlib
- seaborn
- You can install the required libraries using pip: pip install pandas matplotlib seaborn


# Analysis
## Summary Statistics
The summary statistics provide an overview of the total units sold, total gross sales, total discounts, total sales, total COGS, total profit, average manufacturing price, and average sale price.

## Profit Margin Analysis
This analysis calculates the profit margin for each product to understand which products are the most profitable.

## Sales Trend Analysis
This analysis examines the sales trend over time to identify any seasonal patterns or trends.

## Cost Analysis by Product
This analysis compares the cost of goods sold (COGS), sales, and profit for each product to understand the cost structure and profitability.

## Discount Impact Analysis
This analysis evaluates the impact of different discount bands on sales and profit to understand how discounts affect revenue and profitability.

## Country-wise Analysis
This analysis provides insights into the total units sold, total sales, total profit, and average profit margin by country.

## Product-wise Analysis
This analysis provides insights into the total units sold, total sales, total profit, and average profit margin by product.

# Visualizations
The project includes various visualizations to help understand the data better:

Bar plots for profit margin by product, cost analysis by product, discount impact on sales and profit, total units sold by country, total sales by country, total profit by country, and average profit margin by country.
Line plots for sales trend over time and sales and profit trends by country.
