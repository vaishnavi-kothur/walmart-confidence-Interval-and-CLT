# Walmart Customer Purchase Analysis using Confidence Intervals & Central Limit Theorem

## Project Overview

Walmart serves millions of customers globally and generates a massive volume of retail transactions daily.

This project analyzes customer purchase behavior during Black Friday sales to understand spending patterns across different customer segments and determine whether factors such as Gender, Marital Status, and Age influence purchase amounts.

The analysis leverages statistical techniques such as the Central Limit Theorem (CLT) and Confidence Intervals to estimate population spending behavior and support data-driven business decisions.

---

## Business Problem

The Walmart management team wants to understand:

- Do women spend more on Black Friday than men?
- Are spending patterns significantly different across genders?
- Does marital status affect customer spending?
- Which age groups contribute the highest revenue?
- How can Walmart improve customer targeting and promotional strategies?

Using Confidence Intervals and CLT, estimate the average spending behavior of Walmart's customer population.

---

## Dataset Information

The dataset contains transactional records of customers who made purchases during Black Friday sales.

### Features

| Feature | Description |
|----------|-------------|
| User_ID | Customer ID |
| Product_ID | Product ID |
| Gender | Male/Female |
| Age | Customer age group |
| Occupation | Occupation category |
| City_Category | City Type (A/B/C) |
| StayInCurrentCityYears | Years spent in current city |
| Marital_Status | Married/Unmarried |
| ProductCategory | Product category |
| Purchase | Purchase amount |

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Statistical Concepts Applied

### Central Limit Theorem (CLT)

Used CLT to analyze how sample means behave as sample size increases.

Sample Sizes Tested:
- 30
- 100
- 500
- 1000

### Confidence Intervals

Constructed:

- 90% Confidence Interval
- 95% Confidence Interval
- 99% Confidence Interval

for:

- Gender
- Marital Status
- Age Groups

---

## Data Preprocessing

Performed:

- Missing value detection
- Duplicate record checks
- Data type validation
- Outlier detection using boxplots
- Statistical summary analysis

---

## Exploratory Data Analysis

### Univariate Analysis

- Purchase Distribution
- Gender Distribution
- Age Distribution
- Marital Status Distribution
- Product Category Distribution

### Bivariate Analysis

- Gender vs Purchase
- Age vs Purchase
- Marital Status vs Purchase
- Product Category vs Purchase

### Correlation Analysis

- Correlation Heatmap
- Pairplot Analysis

---

## Key Questions Answered

### 1. Do Women Spend More Than Men?

Calculated:

- Average Male Purchase
- Average Female Purchase

Constructed confidence intervals for both groups and compared overlap.

### 2. Gender-Based Confidence Intervals

Estimated population mean spending using:

- 90% CI
- 95% CI
- 99% CI

Observed how interval width changes with confidence level.

### 3. Married vs Unmarried Spending

Analyzed:

- Average spending
- Confidence intervals
- Spending distribution

to identify purchasing differences.

### 4. Age-Based Spending Analysis

Compared:

- 0–17
- 18–25
- 26–35
- 36–50
- 51+

to determine which customer groups generate the highest spending.

---

## Key Insights

### Gender Analysis

- Male customers contributed a larger share of total purchases.
- Average purchase amount differed between genders.
- Confidence interval comparison helped estimate population spending behavior.

### CLT Findings

- Sample means approached a normal distribution as sample size increased.
- Larger sample sizes produced narrower and more reliable confidence intervals.

### Marital Status Analysis

- Spending behavior showed measurable differences between married and unmarried customers.
- Married customers demonstrated stronger purchasing consistency.

### Age Analysis

- Customers aged 26–35 represented the highest spending segment.
- Younger and older age groups exhibited lower average purchase values.

---

## Business Recommendations

### 1. Target High-Spending Age Segments

Focus marketing campaigns on:

- 26–35 years
- 36–50 years

These groups contribute significantly to overall revenue.

### 2. Personalized Gender-Based Promotions

Use purchase behavior insights to design more effective product recommendations and promotional campaigns.

### 3. Customer Segmentation Strategy

Create targeted offers based on:

- Gender
- Age Group
- Marital Status

to improve conversion rates.

### 4. Optimize Black Friday Campaigns

Increase promotions for customer groups with higher average spending and strong purchasing consistency.

### 5. Improve Revenue Forecasting

Use confidence intervals to estimate customer spending ranges and improve inventory planning during major sales events.

---

## Project Structure

Walmart-Confidence-Interval-CLT/

├── Dataset/
│   └── Walmart_data.csv

├── Notebook/
│   └── Walmart_CLT_Analysis.ipynb

├── Images/
│   ├── Purchase_Distribution.png
│   ├── Gender_Analysis.png
│   ├── Confidence_Intervals.png
│   ├── Age_Analysis.png
│   └── CLT_Distribution.png

├── Reports/
│   └── Walmart_Analysis_Report.pdf

└── README.md

---

## Results

The analysis demonstrated how statistical techniques such as Confidence Intervals and the Central Limit Theorem can be used to estimate customer spending behavior and support business decision-making.

The findings provide actionable insights for customer segmentation, targeted marketing, inventory planning, and revenue optimization.

---

## Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Central Limit Theorem (CLT)
- Confidence Intervals
- Data Visualization
- Business Analytics
- Customer Segmentation
- Python Programming

---

## Author

Vaishnavi Kothur

QA Engineer | Aspiring Data Analyst

GitHub: https://github.com/vaishnavi-kothur
LinkedIn: https://linkedin.com/in/your-profile
