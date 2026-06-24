# Walmart Customer Purchase Analytics

## Business Problem

Walmart wanted to understand customer purchasing behavior and identify the factors that drive higher spending. The objective was to analyze customer demographics, purchasing patterns, and product preferences to uncover actionable insights that could improve customer targeting, marketing effectiveness, and revenue growth. The analysis focused on understanding how factors such as gender, age, marital status, occupation, city category, and product category influence purchase behavior.

---

## Dataset Overview

* **Dataset:** Walmart Customer Purchase Dataset
* **Transactions:** 550,068
* **Unique Customers:** 5,891
* **Features:** 10+
* **Target Variable:** Purchase Amount
* **Key Attributes:**

  * User ID
  * Gender
  * Age
  * Occupation
  * City Category
  * Stay in Current City Years
  * Marital Status
  * Product Category
  * Purchase Amount

---

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Tableau Public
* Statistics
* Central Limit Theorem (CLT)
* Confidence Intervals

---

## Analysis Performed

### Customer Analytics

* Gender Analysis
* Age Group Analysis
* Marital Status Analysis
* Occupation Analysis
* City Category Analysis

### Product Analytics

* Product Category Analysis

### KPI Analysis

* Total Transactions
* Unique Customers
* Average Purchase
* Total Revenue

### Statistical Analysis

* Sampling Distribution Analysis
* Central Limit Theorem Validation
* Confidence Interval Estimation
* Population vs Sample Comparison

---

## Tableau Dashboard

### Executive Overview Dashboard

KPIs:

* Total Transactions
* Unique Customers
* Average Purchase
* Total Revenue

### Customer Insights Dashboard

Includes:

* Gender Analysis
* Age Analysis
* Marital Status Analysis
* Occupation Analysis
* City Category Analysis
* Product Category Analysis

**Tableau Public Link:** **Tableau Public Dashboard:**
https://public.tableau.com/views/WalmartAnalysis_17822994672750/Customer_Insights_Dashboard

---

## Key Insights

### 1. Male Customers Spend More

Male customers have a higher average purchase value than female customers, indicating stronger spending behavior and larger transaction sizes.

### 2. Older Customers Generate Higher Purchase Value

Customers aged 51–55 exhibit the highest average purchase value, making them one of the most valuable customer segments.

### 3. Marital Status Has Limited Impact

Married and unmarried customers show similar spending patterns, suggesting marital status is not a major driver of purchase behavior.

### 4. City Category C Leads Spending

Customers from City Category C have the highest average purchase value, outperforming customers from Categories A and B.

### 5. Product Category 10 Drives Revenue

Product Category 10 generates the highest average purchase value, making it a key category for revenue generation and marketing focus.

---

## Business Recommendations

### 1. Focus on High-Value Customer Segments

Design personalized campaigns targeting male customers and high-spending age groups to maximize customer lifetime value.

### 2. Increase Investment in City Category C

Allocate more marketing resources and promotional campaigns to City Category C where customers demonstrate stronger spending behavior.

### 3. Prioritize High-Performing Product Categories

Improve inventory planning, promotions, and cross-selling strategies for Product Category 10 and other top-performing categories.

---

## Project Learnings

This project strengthened my understanding of both business analytics and statistical inference.

### Central Limit Theorem (CLT)

* Learned how sampling distributions approach normality as sample size increases.
* Understood the importance of random sampling in making population-level inferences.
* Validated purchasing behavior using repeated sampling techniques.

### Confidence Intervals

* Learned how to estimate population spending behavior using sample statistics.
* Understood the relationship between sample size, variability, and confidence levels.
* Applied confidence intervals to determine whether observed spending differences were statistically meaningful.

### Tableau Skills

* Built KPI dashboards.
* Designed customer analytics dashboards.
* Created business-focused visualizations.
* Translated analytical findings into actionable business recommendations.

---

## Repository Structure

```text
Walmart-Customer-Purchase-Analytics/
│
├── data/
│   └── walmart_data.csv
│
├── notebooks/
│   ├── EDA.ipynb
│   ├── CLT_Analysis.ipynb
│   └── Confidence_Interval_Analysis.ipynb
│
├── tableau/
│   └── Walmart_Analytics.twb
│
├── images/
│   ├── Executive_Dashboard.png
│   ├── Customer_Insights_Dashboard.png
│   └── Visualizations/
│
├── reports/
│   └── Walmart_Business_Insights_Summary.pdf
│
├── README.md
│
└── requirements.txt
```

---

## 30-Second Project Summary

Analyzed 550K+ Walmart customer transactions to understand purchasing behavior across demographics, city categories, occupations, and product categories. Built KPI dashboards and customer analytics visualizations using Tableau, while applying statistical concepts such as the Central Limit Theorem and Confidence Intervals to validate findings. The project identified high-value customer segments, top-performing product categories, and actionable recommendations to improve marketing effectiveness and revenue growth.
