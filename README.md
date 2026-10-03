# Diwali Sales Analysis 🪔

Exploratory Data Analysis (EDA) on Diwali sales data to uncover customer buying patterns and identify which customer segments and product categories drive the most sales — insights that can help a business plan inventory, marketing, and stock better for the festive season.

## Objective

- Clean and prepare raw sales transaction data for analysis
- Explore customer demographics (gender, age, marital status, occupation, location) against purchasing behavior
- Identify top-selling product categories and products
- Translate the findings into practical, business-relevant conclusions

## Dataset

- **File:** `Diwali Sales Data.csv`
- **Contents:** Customer-level transaction data including Age, Gender, Marital Status, State, Occupation, Product Category, Product ID, Orders, and Amount

## Tools & Libraries

- Python
- Pandas, NumPy — data cleaning and manipulation
- Matplotlib, Seaborn — data visualization
- Jupyter Notebook

## Approach

1. **Data Cleaning** — dropped irrelevant/unnamed columns, removed null values, fixed data types
2. **Exploratory Data Analysis** — analyzed sales across:
   - Gender
   - Age Group
   - State
   - Marital Status
   - Occupation
   - Product Category & top-selling products
3. **Insights** — summarized patterns from each breakdown into actionable observations

## Key Findings

- Female customers made up the majority of buyers and also showed higher total purchasing amount than male customers
- The 26–35 age group (especially women) was the most active buyer segment
- Uttar Pradesh, Maharashtra, and Karnataka generated the highest number of orders and total sales
- Married customers, particularly married women, showed higher purchasing power than unmarried customers
- Customers working in IT, Healthcare, and Aviation sectors contributed the most to sales
- Food, Clothing, and Electronics were the top-selling product categories

**Overall:** Married women aged 26–35, from Uttar Pradesh, Maharashtra, and Karnataka, working in IT, Healthcare, or Aviation, are the most likely to purchase — primarily from Food, Clothing, and Electronics categories. This customer profile can guide targeted marketing and inventory planning for future sales events.

## How to Run

```bash
pip install pandas numpy matplotlib seaborn
jupyter notebook Diwali_Sales_Analysis.ipynb
```

Make sure `Diwali Sales Data.csv` is in the same folder as the notebook (or update the file path accordingly).

## Learnings

- Practiced end-to-end data cleaning: handling nulls, dropping irrelevant columns, correcting data types
- Applied groupby and aggregation techniques to uncover patterns across multiple categorical dimensions
- Practiced translating raw visualizations into clear, written business insights
- Strengthened understanding of using Seaborn/Matplotlib for count plots and bar plots with labeled bars

## Note

This project was built by me, coded independently, based on the concepts and workflow taught in this tutorial: [Diwali Sales Analysis — Python Project](https://www.youtube.com/watch?v=KgCgpCIOkIs). I wrote and ran the analysis myself as a way to strengthen my EDA skills.
