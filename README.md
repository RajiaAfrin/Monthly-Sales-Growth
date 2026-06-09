# Monthly Sales Growth Analysis

## Project Background

Sales performance is one of the most important indicators of business success. Monitoring sales trends, profitability, product performance, and regional contributions helps organizations identify growth opportunities, optimize operations, and improve decision-making.

This end-to-end analytics project analyzes monthly sales performance using data cleaning, SQL analysis, and interactive Power BI visualizations. The goal is to understand sales growth patterns, evaluate profitability across regions and products, and identify key business drivers.

# Dataset
-<a href="">Dataset</a>

Insights and recommendations are provided on the following key areas:

- Sales Performance Overview
- Monthly Sales Growth Trends
- Regional Profitability Analysis
- Product Performance
- Profit Margin Analysis

This project was created using **Python, SQL, Power BI, and Microsoft Excel**.

## Data Structure & Initial Checks

The project follows a complete analytics workflow:

Raw Excel Data → Python Data Cleaning → SQL Analysis → Power BI Dashboard

The cleaned dataset contains **482 sales records** and includes:

- Order_ID
- Order_Date
- Customer
- Region
- Product
- Sales
- Cost
- Profit
- Year
- Month

### Initial Data Checks

The project began with:

- Data cleaning using Python
- Missing value validation
- Date formatting
- Profit calculation verification
- Sales and cost validation
- SQL-based exploratory analysis
- Data preparation for Power BI reporting

# Dashboard Interaction
-<a href="">Dashboard</a>

## Executive Summary

### Overview of Findings

The analysis generated approximately **20 million** in total sales and **5 million** in total profit, resulting in an average profit margin of **25.09%**.

Sales performance peaked in **March**, while **April** recorded the lowest sales activity. Regional analysis revealed that the **North** region generated the highest profit, while **West** produced the lowest.

Product performance analysis showed that **Printer** was the highest-selling product, followed by **Tablet** and **Laptop**.

## Insights Deep Dive

## 1. Sales Performance Overview

The dashboard highlights the following key business metrics:

- Total Sales: **20M**
- Total Profit: **5M**
- Average Profit Margin: **25.09%**

These metrics provide an overall view of revenue generation and business profitability.

## 2. Monthly Sales Growth Analysis

Monthly sales trends revealed significant fluctuations throughout the year.

Key findings include:

- Highest Sales Month: **March**
- Lowest Sales Month: **April**

Sales increased steadily leading into March before experiencing a sharp decline in April and stabilizing during the remaining months.

This pattern may indicate seasonal demand fluctuations or promotional activity during the first quarter.

## 3. Regional Profitability Analysis

Profitability varied across regions.

Regional profit ranking:

| Region | Performance |
|----------|-------------|
| North | Highest Profit |
| South | Second Highest |
| East | Third Highest |
| West | Lowest Profit |

The North region emerged as the strongest contributor to overall profitability.

## 4. Product Performance Analysis

The highest-selling products were:

| Product | Sales |
|----------|---------:|
| Printer | 4,562,567 |
| Tablet | 3,990,632 |
| Laptop | 3,967,919 |
| Monitor | 3,744,366 |
| Mobile | 3,544,151 |

Printer generated the highest sales revenue among all products.

## 5. Sales Distribution by Region

Regional sales contributions were relatively balanced.

| Region | Sales |
|----------|---------:|
| South | 5,176,309 |
| North | 5,138,427 |
| West | 4,819,905 |
| East | 4,674,994 |

The South region generated the highest total sales, while the North region generated the highest profit.

This suggests differences in regional profitability despite similar revenue levels.

# Dashboard screenshot
<img width="1166" height="658" alt="image" src="https://github.com/user-attachments/assets/e3e165ec-3c48-4c63-bf30-9354caeb257a" />

## Recommendations

Based on the findings, I would recommend the following:

### 1. Investigate March Sales Performance

March significantly outperformed other months and should be analyzed further to identify successful campaigns, promotions, or seasonal factors that can be replicated.

### 2. Improve Performance During Low-Sales Periods

April recorded the lowest sales volume and may require targeted promotions or demand-generation initiatives.

### 3. Focus on High-Profit Regions

The North region generated the highest profit and may offer opportunities for further expansion and investment.

### 4. Strengthen Top-Selling Product Lines

Products such as Printer, Tablet, and Laptop contribute a significant portion of revenue and should remain a priority for inventory planning and marketing efforts.

### 5. Monitor Regional Profit Margins

While regional sales volumes are relatively balanced, profit performance differs across regions. Margin optimization strategies should be evaluated at the regional level.

## Assumptions and Caveats

- Sales and profit values are based on the cleaned dataset used in the analysis.
- Monthly sales trends reflect historical transaction data and may not represent future performance.
- Regional performance is evaluated using the available sales and profit records.
- Product rankings are based on total sales revenue.
- Additional business factors not included in the dataset may influence performance.

## Tools Used

- Python
- Pandas
- SQL
- Power BI
- Microsoft Excel
- Data Cleaning
- Data Analysis
- Data Visualization
