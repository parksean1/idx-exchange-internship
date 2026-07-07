# Housing Market Analysis (MLS Data)

## Overview

This project analyzes over **500,000 MLS housing records** to uncover trends in pricing, demand, and market behavior across California. The workflow spans data cleaning, feature engineering, outlier detection, exploratory data analysis (EDA), and interactive Tableau dashboard development.

The goal was to transform raw real estate transaction data into actionable insights that help explain housing market dynamics and support data-driven decision making.

---

## End-to-End Workflow

1. Data Collection & Integration
2. Data Cleaning & Preparation
3. Feature Engineering
4. Outlier Detection & Data Quality
5. Exploratory Data Analysis (EDA)
6. Tableau Dashboard Development

---

## Key Work & Contributions

### Data Preparation

- Cleaned and validated over **500,000 MLS housing records**
- Standardized date formats and handled missing values
- Removed invalid and inconsistent entries
- Prepared analysis-ready datasets for visualization and modeling

### Feature Engineering

Created key real estate metrics including:

- Close Price / Original List Price Ratio
- Price per Square Foot
- Listing-to-Contract Days
- Contract-to-Close Days
- Month and Year features for time-series analysis

### Data Quality & Outlier Handling

- Applied IQR-based outlier detection
- Identified and removed extreme values in pricing, square footage, and timing metrics
- Built filtered datasets for more reliable statistical analysis and visualization

---

# Tableau Dashboards

Developed four interactive Tableau dashboards to analyze California housing market trends from multiple perspectives.

## 1. House Market Insights

Features:

- Price vs. Sales by ZIP Code
- Home Price Distribution
- Top ZIP Codes by Homes Sold
- Relationships between pricing and housing demand

![House Market Insights](tableau_images/House%20Market%20Insights.png)

---

## 2. Market Analysis

Features:

- Median home price trends (2024–2026)
- Average days on market
- Close-to-original list price ratio
- New listings
- Closed sales
- Interactive filters by county, city, ZIP code, and property subtype

![Market Analysis](tableau_images/Market%20Analysis.png)

---

## 3. Market Conditions & Pressure Analysis

Features:

- Market Pressure Index over time
- Median close price trends
- Average days on market
- Interactive filtering by location and property subtype

![Market Conditions & Pressure Analysis](tableau_images/Market%20Conditions%20%26%20Pressure%20Analysis.png)

---

## 4. Real Estate Market Analysis

Features:

- Median home prices by ZIP code map
- Homes sold heat map
- Top listing agents by sales volume and transaction count
- Top listing offices by sales volume and transaction count

![Real Estate Market Analysis](tableau_images/Real%20Estate%20Market%20Analysis.png)

---

## Key Insights

- Cleaned and transformed over **500,000 MLS records** into an analysis-ready dataset.
- Removing outliers significantly reduced pricing skew and improved analytical reliability.
- Most housing activity occurred within the **$500K–$900K** price range.
- High-priced markets did not always correspond to the highest transaction volumes.
- Market conditions shifted between 2024 and 2026, with noticeable changes in inventory, market pressure, and days on market.
- Geographic analysis identified ZIP codes, listing agents, and brokerages consistently leading in transaction activity.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Jupyter Notebook
- Tableau
- Git
- GitHub

---

## Repository Notes

The original MLS dataset, CSV files, and Tableau workbook are **not included** in this repository due to data confidentiality requirements from the internship. Dashboard screenshots are provided to showcase the final visualizations while protecting proprietary data.
