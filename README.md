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

- Cleaned and validated **500K+ MLS records**
- Standardized date formats and handled missing values
- Removed invalid and inconsistent entries
- Prepared analysis-ready datasets for downstream visualization

### Feature Engineering

Created key real estate metrics including:

- Price Ratio (Close Price / Original List Price)
- Price per Square Foot
- Listing-to-Contract Days
- Contract-to-Close Days
- Month and Year features for time-series analysis

### Data Quality & Outlier Handling

- Applied IQR-based outlier detection
- Flagged extreme values in pricing, square footage, and timing metrics
- Built filtered datasets for more reliable statistical analysis and visualization

---

# Tableau Dashboards

Developed four interactive Tableau dashboards to explore California housing market trends from multiple perspectives.

## 1. Housing Market Trends Dashboard

Features:

- Median home price trends (2024–2026)
- Average days on market
- Average Close-to-Original List Price Ratio
- New listings
- Closed sales
- Interactive filters by county, city, ZIP code, and property subtype

![Housing Market Trends](tableau_images/housing_market_trends.png)

---

## 2. Market Conditions & Pressure Dashboard

Features:

- Market Pressure Index over time
- Median close price trends
- Average days on market
- Interactive filtering by location and property subtype

![Market Conditions & Pressure](tableau_images/market_conditions_pressure.png)

---

## 3. California Housing Market Insights Dashboard

Features:

- Price vs. sales by ZIP code scatterplot
- Home price distribution histogram
- Top ZIP codes by homes sold
- Market demand and pricing relationship analysis

![California Housing Market Insights](tableau_images/california_housing_insights.png)

---

## 4. Real Estate Market Analysis Dashboard

Features:

- Median home prices by ZIP code map
- Homes sold heat map
- Top listing agents by sales volume and transactions
- Top listing offices by sales volume and transactions

![Real Estate Market Analysis](tableau_images/real_estate_market_analysis.png)

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

## Project Structure

```
Week1/
├── Initial exploratory data analysis

Week2-3/
├── Mortgage rate integration
├── Data merging

Week4-5/
├── Data cleaning
├── Data preparation

Week6/
├── Feature engineering

Week7/
├── Outlier detection
├── Data quality analysis

tableau_images/
├── housing_market_trends.png
├── market_conditions_pressure.png
├── california_housing_insights.png
└── real_estate_market_analysis.png
```

---

## Repository Notes

The original MLS dataset and Tableau workbook are **not included** in this repository due to data confidentiality requirements. Dashboard screenshots are provided to showcase the final visualizations while protecting proprietary data.
