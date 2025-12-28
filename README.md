# SQL Portfolio: Retail Sales Analysis 

## Dataset Overview
The dataset contains transaction-level retail data including product, category, customer, region, sales, profit, discount, and order date.
Order date is stored in DD/MM/YYYY format and was processed using string-based date handling for time series analysis in SQLite.

## Use Case

### 1. Product Profitability Analysis  
Identifies products with high sales volume but negative or low profit to highlight revenue–profit trade-offs and loss-driving products

### 2. Category & Sub-Category Performance  
Compares category and sub-category performance based on sales, profit, and profit margin using multi-level aggregation.

### 3. Discount Impact on Profit  
Analyzes the relationship between discount levels and profitability by cleaning and binning discount values into defined categories.

### 4. Customer Segmentation  
Segments customers based on purchase frequency and total sales by comparing individual metrics against the average customer behavior.

### 5. Regional Performance Analysis  
Identifies the top-performing city in each region based on total profit using ranking window functions.

### 6. Time Series Sales Trend Analysis  
Segments customers based on purchase frequency and total sales by comparing individual metrics against the average customer behavior.
