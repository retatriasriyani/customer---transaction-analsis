# Customer Transaction Analysis (SQL Portfolio)

## 📌 Project Overview
This project analyzes customer purchasing behavior using SQL to extract insights related to revenue drivers, customer segmentation, subscription effectiveness, discount impact, and potential churn risk.

The analysis is designed to demonstrate analytical thinking, business understanding, and practical SQL skills.

---

## 🎯 Objectives
The objectives of this analysis are:
- To understand overall customer purchasing behavior
- To identify key factors influencing revenue (subscription and discount)
- To segment customers based on value and purchase behavior
- To generate actionable insights for customer retention and revenue growth

---

## 🗂 Dataset Description
**Table:** `customer_transactions_final`

Each row represents a **customer-level record**, including:
- Demographics: age, gender, age_group
- Purchase behavior: purchase_amount, previous_purchases, frequency_of_purchases_days
- Product attributes: category, season
- Business attributes: subscription_status, discount_applied, review_rating

---

## ⚠️ Assumptions & Limitations
- The dataset is **customer-level**, not transaction-level.
- Actual transaction frequency per customer is not available.
- Purchase frequency is analyzed using behavioral proxies:
  - `previous_purchases`
  - `frequency_of_purchases_days`

---

## ❓ Business Questions & Analysis Scope

| No | Business Question | Query Reference |
|----|------------------|-----------------|
| 1 | What is the overall customer and revenue overview? | Query 1 |
| 2 | Which product categories generate the highest revenue? | Query 2 |
| 3 | How does product performance vary by season? | Query 3 |
| 4 | Do subscribed customers contribute higher revenue? | Query 4 |
| 5 | How are customers distributed across value segments? | Query 5 |
| 6 | How does purchase frequency differ across customers? | Query 6 |
| 7 | Does discount impact purchase behavior? | Query 7 |
| 8 | Does discount influence repeat purchase behavior? | Query 8 |
| 9 | Are there high-value customers with low satisfaction? | Query 9 |

---

## 📊 Analysis & Key Insights

### Data Understanding
The dataset shows relatively stable average purchase values across customers. This indicates that revenue growth is more strongly driven by purchase frequency and customer retention rather than higher transaction values.

---

### Exploratory Analysis
Revenue contribution is uneven across product categories, with a small number of categories dominating total sales. Product performance also varies across seasons, indicating the presence of seasonal purchasing patterns.

---

### Business Insights
- Subscribed customers generate higher total revenue than non-subscribed customers.
- A small group of high-value customers contributes a significant share of overall revenue.
- Discounts influence purchase volume and repeat behavior, but do not consistently increase average transaction value.
- High-value customers with low satisfaction ratings represent a potential churn risk.

---

## 🎯 Recommendations
- Prioritize retention strategies for high-value customers.
- Expand and optimize subscription programs for mid-to-high value customers.
- Apply discounts selectively instead of broad mass promotions.
- Proactively engage high-value customers with low satisfaction to reduce churn risk.

---

```
## 📁 Repository Structure
sql-customer-analysis/
│
├── customer_analysis.sql -- SQL queries
├── README.md -- Project documentation
├── outputs/
│ ├── tables/ -- Query result tables (CSV)
│ └── charts/ -- Visualization outputs
└── ppt/
└── Customer_Analysis_Portfolio.pptx
```

---

## 🛠 Tools & Skills
- SQL (CTE, Window Functions, Aggregation)
- Customer Segmentation
- Business & Data Analysis
- Data-driven Decision Making

---

## 👤 Author
**Reta Tri Asriani**  
Background: Mathematics | Data & Financial Analysis  

