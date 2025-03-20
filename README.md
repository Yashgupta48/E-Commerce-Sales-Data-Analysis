# E-Commerce-Sales-Data-Analysis

Overview

This project analyzes an E-commerce sales dataset to extract meaningful insights about revenue trends, customer segments, product categories, and profitability. The analysis involves data cleaning, exploratory data analysis (EDA), visualization, and hypothesis testing to make data-driven recommendations.

## Summary

## Situation:

An E-commerce business needed insights into its sales performance to optimize revenue, improve customer targeting, and enhance profitability.

# Task:

The goal was to analyze the dataset to identify key trends in sales, profits, customer segments, and product categories. Additionally, hypothesis testing was conducted to validate business decisions.

# Action:

1. Data was cleaned by handling missing values and ensuring proper data types.

2. Exploratory data analysis (EDA) was performed to uncover sales patterns.

3. Sales and profit trends were examined by region, category, and customer segment.

4. Visualizations were created to represent findings clearly.

5. Hypothesis testing (T-test, ANOVA, Chi-Square) was used to validate key insights.

Recommendations were made for optimizing pricing, discount strategies, and inventory management.

# Result:

1. Total Sales: $2,297,200.86, Total Profit: $286,397.02 (12.47% profit margin).

2. Top-selling month:  November, Highest profit month: December.

3. Technology had the highest sales; Phones were the most profitable.

4. Office Supplies had the lowest sales; Tables were the least profitable.

Consumers were the most profitable segment, while Home Office had the lowest sales-to-profit ratio.

No significant difference in profit between weekends and weekdays (p = 0.86), but discount levels significantly affected profit (p < 0.001).

# Dataset

1. The dataset includes details on orders, customers, sales, profit, discounts, and shipping dates.

2. Data source: Sample - Superstore.csv.zip

3. Contains 9,994 records with 21 columns including:

4. Order ID, Order Date, Ship Date, Ship Mode

5. Customer ID, Customer Name, Segment, Region

6. Product ID, Category, Sub-Category, Product Name

7. Sales, Quantity, Discount, Profit

# Objectives

1. Perform data cleaning (handling missing values, duplicates, and data types).

2. Conduct exploratory data analysis (EDA) to uncover patterns and trends.

3. Analyze sales performance by region, category, sub-category, and customer segment.

4. Investigate monthly sales trends and profitability insights.

5. Conduct hypothesis testing to validate business assumptions.

6. Provide data-driven recommendations for strategic decisions.

# Tools Used

1. Python: Pandas, NumPy, Matplotlib, Seaborn, Scipy

1. Jupyter Notebook

# Key Insights & Findings

1. Sales and Profit Trends

2. Total Sales: $2,297,200.86

3. Total Profit: $286,397.02

4. Profit Margin: 12.47%

5. Top-selling month: November

6. Highest profit month: December

# 2. Category & Sub-Category Analysis

1. Technology category had the highest sales.

2. Office Supplies had the lowest sales.

3. Phones were the most profitable sub-category.

4. Tables were the least profitable sub-category.

# 3. Customer Segment Insights

1. Consumers generated the highest revenue.

2. Home Office segment had the lowest sales-to-profit ratio.

3. Top 5 most profitable customers identified.

# 4. Shipping & Delivery Performance

1. Average delivery time: ~4 days

2. Standard Class shipping was the most used mode.

# 5. Statistical Hypothesis Testing

1. No significant difference in profit between weekends and weekdays (T-test: p = 0.86)

2. No significant difference in revenue between customer segments (ANOVA: p = 0.70)

3. Discount levels significantly affect profit (Chi-Square Test: p < 0.001)

# Visualizations

1. Monthly Sales and Profit Trends

2. Category-wise and Sub-category-wise Sales Distribution

3. Customer Segment-wise Sales and Profit

4. Correlation Matrix Heatmap

5. Sales and Profit Boxplots for Outlier Detection

# Recommendations

1. Focus on high-profit categories like Technology and sub-categories like Phones.

2. Reduce heavy discounting on low-profit items like Tables.

3. Improve shipping efficiency to reduce delivery time.

4. Target high-value customers with loyalty programs.

5. Consider pricing optimization strategies for low-profit products.

