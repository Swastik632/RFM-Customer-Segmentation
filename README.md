# RFM-Customer-Segmentation
End-to-end RFM analytics pipeline ; Python, SQLite, Power BI

# RFM Customer Segmentation & Analytics Pipeline

## Overview
End-to-end customer segmentation pipeline built on UK Online Retail II dataset (Kaggle).

## Stack
- Python (Jupyter Notebook) - data cleaning, RFM calculation, segmentation
- SQLite - data storage and SQL analysis
- Power BI - 3-page interactive dashboard

## Dataset
- Source: UK Online Retail II - Kaggle
- Raw rows: 1,067,371
- Clean rows: 805,549
- Unique customers: 5,878

## Key Insights
- Champions = 22% of customers, 68.35% of revenue
- At Risk segment holds £1.5M at risk
- Lost customers avg 568 days since last purchase
- Need Attention = largest segment at 25.81%

## Project Structure
- rfm_pipeline.ipynb - full Python pipeline
- rfm_database.db - SQLite database
- rfm_final.csv - final RFM output
- segment_distribution.csv - segment counts
- segment_metrics.csv - avg R, F, M per segment
- segment_revenue.csv - revenue by segment

## Dashboard Pages
1. Overview - KPI cards (total customers, revenue, avg R/F/M)
2. Segment Analysis - bar charts + summary table
3. At-Risk Customers - high value at-risk table + scatter plot
