# SQL Portfolio: Retail Sales Analysis 

## Business Context
This project analyzes retail sales data to evaluate profitability, customer behavior, discount impact, regional performance, and sales trends in order to support data-driven business decisions.

## Dataset Overview
The dataset contains transaction-level retail data including product, category, customer, region, sales, profit, discount, and order date.
Order date is stored in DD/MM/YYYY format and was processed using string-based date handling for time series analysis in SQLite.

## Use Case 1–6

### 1. Product Profitability Analysis  
**Insight:** Several products generate high sales volume but contribute negative profit.  
**Conclusion:** These products may require pricing, cost, or discount strategy evaluation.

### 2. Category & Sub-Category Performance  
**Insight:** Profitability varies significantly across categories and sub-categories despite similar sales levels.  
**Conclusion:** Business focus should prioritize categories with healthy profit margins rather than sales volume alone.

### 3. Discount Impact on Profit  
**Insight:** Higher discount levels are associated with declining profit margins.  
**Conclusion:** Excessive discounting reduces overall profitability and should be carefully controlled.

### 4. Customer Segmentation  
**Insight:** A small segment of customers contributes disproportionately to total sales.  
**Conclusion:** Retention and loyalty programs should focus on high-value customers.

### 5. Regional Performance Analysis  
**Insight:** Certain regions outperform others in terms of profit despite similar sales levels.  
**Conclusion:** Regional performance differences indicate potential operational or pricing inefficiencies.

### 6. Time Series Sales Trend Analysis  
**Insight:** Monthly sales show fluctuations with alternating upward and downward trends, indicating seasonality.  
**Conclusion:** Promotional and inventory strategies should align with monthly sales patterns.

## Key Findings
- High sales do not always translate into high profit.
- Discount strategy has a strong impact on profitability.
- Customer and regional contributions are uneven.
- Sales performance fluctuates over time, indicating seasonal behavior.

## Business Recommendation
The company should optimize discount strategies, focus on high-value customers, and align regional and promotional decisions with observed sales trends to improve overall profitability.
