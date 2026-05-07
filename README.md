# Housing Market Analysis (MLS Data)

## Overview
This project analyzes MLS housing data to understand market trends, pricing behavior, and property characteristics. The workflow includes data cleaning, feature engineering, and outlier detection to prepare the data for analysis and visualization.

## What I Did
- Cleaned and prepared raw MLS data (500K+ rows)
- Converted and validated date fields
- Handled missing values and removed invalid records
- Engineered key metrics:
  - Price ratio (ClosePrice / OriginalListPrice)
  - Price per square foot
  - Listing-to-contract days
  - Contract-to-close days
- Created time-based features for trend analysis
- Identified and flagged outliers using the IQR method
- Built filtered datasets for more reliable analysis

## Tools Used
- Python
- Pandas
- Jupyter Notebook

## Project Structure
- `/weeks_2_3` → Data merging (mortgage rates)
- `/weeks_4_5` → Data cleaning and preparation
- `/weeks_6` → Feature engineering and metrics
- `/weeks_7` → Outlier detection and data quality

## Key Insights
- Outlier removal reduced skew in price and size distributions
- Median home prices decreased slightly after filtering extreme values
- Days on market became more consistent after cleaning

## Next Steps
- Build Tableau dashboards for market trends
- Perform deeper segmentation analysis (county, property type)
