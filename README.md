# eCommerce Delivery Performance Analysis

## Project Overview
End-to-end analysis of 99,441 eCommerce orders to uncover delivery performance insights, 
customer retention patterns, and category-level trends — aligned with same-day delivery 
use cases for fashion, beauty, and healthcare brands.

## Tools Used
- **Python** (Pandas, Matplotlib, Seaborn) — data cleaning & analysis
- **SQL** (SQLite) — business queries & insight extraction  
- **Power BI** — interactive dashboard

## Key Findings
- 91.9% overall on-time delivery rate across 96,478 delivered orders
- Average delivery time: 12.6 days — highlighting same-day delivery opportunity
- Beauty & Personal Care has highest order volume (9,465) but worst on-time rate (90.9%)
- Black Friday 2017 peak: 3,008 orders in a single week
- AL state has 23.9% late delivery rate vs 3% for best performing states
- Nearly 0% customer retention — directly linked to poor delivery experience

## Dashboard Preview
![Dashboard](Dashboard.pbix)

## Project Structure
- `analysis.ipynb` — Python analysis notebook
- `Blitz_Delivery_Dashboard.pbix` — Power BI dashboard
- `*.csv` — cleaned datasets for each analysis
