# Market Performance Analysis 

## Project Overview

This project analyzes market performance across four key Latin American countries: Brazil, Chile, Colombia, and Mexico.

The analysis focuses on understanding customer demographics, product performance, and sales trends across a three-year period (2020–2022). The goal is to transform raw business data into a clear and interactive dashboard that supports data-driven decision-making.

## Project Objectives

- Provide a high-level overview of business performance using key KPIs
- Analyze customer demographics by age group, gender, income group, and country
- Identify top-performing and underperforming products
- Understand sales distribution across regions
- Track sales trends over time (yearly, quarterly, monthly)
- Enable detailed product-level analysis through drill-through functionality

## Data Model

The analysis uses a star schema structure:

Sales (Fact Table) → Date (Dimension)
Sales (Fact Table) → Customer (Dimension)

A date table was created to support time-based analysis including Year, Quarter, and Month.

## Dashboard Preview

### Executive Summary
![Executive Summary](screenshots/key_performance_indicators.png)

### Customer Demographics
![Customer Demographics](screenshots/customer_demographic.png)

### Sales Performance
![Sales Performance](screenshots/sales_performance.png)

### Time Series Trends
![Time Series Trends](screenshots/time_series.png)

## Key Insights

- Total sales reached $311.27M across 44K orders and 1,000 customers.
- Medium-income customers contribute the largest share of revenue.
- Customer demographics are relatively balanced across age groups and gender.
- Home and lifestyle product categories generate the strongest sales performance.
- Colombia and Chile show slightly stronger regional sales performance.
- Sales declined slightly in 2021 but recovered strongly in 2022.

## Recommendations

- Use seasonal sales patterns to plan promotions and inventory.
- Focus marketing on high-performing product categories.
- Improve sales for underperforming products through targeted promotions.
- Increase order frequency through bundles and promotional offers.
- Continue focusing on medium-income customers while maintaining high-value segments.

## Tools Used

Power BI – Data modeling and dashboard visualization

## Project Structure

Market-performance-analysis

├── data – dataset used for analysis

├── powerbi – Power BI dashboard file

├── screenshots – dashboard preview images

├── presentation – project presentation slides

└── README.md – project documentation

