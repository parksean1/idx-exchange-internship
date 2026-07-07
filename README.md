# Housing Market Analysis (MLS Data)

## Overview
This project analyzes large-scale MLS housing data (500K+ records) to uncover trends in pricing, demand, and market behavior. The workflow spans data engineering, feature creation, statistical filtering, and dashboard visualization.

The goal was to transform raw real estate transaction data into actionable insights for understanding housing market dynamics.

---

## End-to-End Workflow
1. Data Cleaning & Preparation  
2. Feature Engineering  
3. Outlier Detection & Data Quality  
4. Exploratory Data Analysis  
5. Tableau Dashboard Development  

---

## Key Work & Contributions

### Data Preparation
- Cleaned and validated 500K+ MLS records
- Standardized date formats and handled missing values
- Removed invalid and inconsistent entries

### Feature Engineering
Created key real estate metrics:
- Price Ratio (Close Price / Original List Price)
- Price per Square Foot
- Listing-to-Contract Days
- Contract-to-Close Days
- Time-based features (month, year)

### Data Quality & Outlier Handling
- Applied IQR-based outlier detection
- Flagged extreme values in price, size, and timing metrics
- Built filtered datasets for more reliable downstream analysis

---

## Tableau Dashboards
Developed interactive dashboards to analyze market behavior:

### 1. Market Overview Dashboard
- Median home price trends over time
- Days on market trends
- Market pressure index

### 2. Competitive Analysis Dashboard
- Top agents and brokerages by sales volume and units
- Geographic filtering (city, county, ZIP)

### 3. Market Insights Dashboard
- Price vs. Sales scatterplot (demand vs. pricing)
- Home price distribution histogram
- Top ZIP codes by transaction volume

---

## Key Insights
- Removing outliers significantly reduced skew in pricing and improved interpretability
- High-priced markets do not always correlate with high transaction volume
- Most housing activity is concentrated in mid-price ranges (~$500K–$900K)
- Certain ZIP codes consistently show both high demand and high pricing, indicating strong market competitiveness

---

## Tools & Technologies
- Python (Pandas, NumPy)
- Jupyter Notebook
- Tableau (data visualization & dashboards)

---

## Project Structure
- `/weeks_2_3` → Data merging (mortgage rates)
- `/weeks_4_5` → Data cleaning and preparation
- `/weeks_6` → Feature engineering
- `/weeks_7` → Outlier detection & data quality
- `/tableau` → Dashboard visualizations
