# Superstore SQL Analysis

This repository contains a SQL-based exploratory analysis of the **Superstore sales dataset**.  
The goal is to uncover clear patterns in sales, profit, discount effects, customer behavior, and regional performance using SQL (SQLite).

---

## Dataset Overview

The dataset includes:
- Transaction-level sales and profit data  
- Product, category, and sub-category  
- Customer and region  
- Sales, profit, discount, order date (stored as TEXT)  

Order dates are cleaned by parsing string date formats, and discount values are standardized to support analysis in SQLite.

---

## Analysis Focus

The project explores:
1. **Product Profitability Analysis**  
   Identifying products with sales that do not translate into profit.

2. **Category & Sub-Category Performance**  
   Comparing sales, profit, and profit margin across product groupings.

3. **Discount Impact on Profit**  
   Cleaning and binning discount levels to observe effects on profitability.

4. **Customer Segmentation**  
   Segmenting customers based on purchase frequency and total sales.

5. **Regional Performance Analysis**  
   Ranking cities within regions based on total profit.

6. **Time Series Sales Trend Analysis**  
   Observing trends by parsed order dates.

---

## Key Insights

- Some products generate revenue but still result in **negative profit**, revealing inefficiencies in pricing or cost.  
- Profit margin varies noticeably across categories and sub-categories.  
- Higher discount levels tend to correlate with lower profit margins.  
- Regional performance and top cities by profit differ significantly, showing geographic variation in performance.  
- Time series analysis reveals periodic patterns in sales activity.

---

---
