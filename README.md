# Customer_Behavior_Analysis
# README - Customer Shopping Behavior Analysis

---

## Overview
This project analyzes customer shopping behavior data to uncover patterns in purchasing habits, demographics, and preferences. It covers the full pipeline from raw data loading to Power BI dashboard.

---

## Dataset
**File:** customer_shopping_behavior.csv
**Columns:** customer_id, age, gender, item_purchased, category, purchase_amount, location, season, review_rating, subscription_status, discount_applied, frequency_of_purchases

---

## Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- PostgreSQL / MySQL / SQL Server
- Power BI
- Gamma (Report & PPT)

---

## Steps
1. **Load Dataset** – Read CSV using Pandas
2. **EDA** – Shape, nulls, stats, distribution plots
3. **Data Cleaning** – Fix types, handle nulls, create new features
4. **SQL Queries** – Revenue by category, top customers, seasonal trends
5. **Power BI Dashboard** – KPI cards, charts, slicers
6. **Report & PPT** – Generated using Gamma

---

## Dashboard Highlights
- KPI Cards: Total Customers, Avg Purchase Amount, Avg Review Rating
- Charts: Revenue by Category, Sales by Age Group, Subscription Status
- Slicers: Gender, Category, Shipping Type

---

## Key Results
- Clothing is the highest revenue-generating category
- Adult age group contributes most to revenue
- Express shipping is most preferred
- Subscribed customers purchase more frequently

---

## How to Run
```
pip install pandas numpy matplotlib seaborn
jupyter notebook customer_analysis.ipynb
```

---

*Project by Pallavi Khadse | 2026*
