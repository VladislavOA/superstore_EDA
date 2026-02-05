# Superstore Exploratory Data Analysis

This Jupyter notebook performs comprehensive exploratory data analysis (EDA) on the Superstore sales dataset. It covers data loading, cleaning, statistical summaries, correlation analysis, and visualizations across regions, states, categories, segments, and time trends.

## Dataset
- **Source**: Superstore.csv (latin1 encoding)
- **Key columns**: Order Date, Ship Date, Region, State, City, Segment, Category, Sub-Category, Sales, Quantity, Discount, Profit, Postal Code
- **Time period**: 2014-2017 (extracted from Order Date)
- **Rows/Columns**: ~10k rows, 21 columns [based on notebook code]

## Analysis Overview
- **Data preparation**: Date parsing, missing values check, descriptive stats
- **Visualizations**:
  - Correlation heatmap
  - Histograms for numeric features (Sales, Profit, Quantity, Discount, Postal Code)
  - Pairplots by Sub-Category
  - Regional sales/profit pies and trends
  - State/City-wise bar charts (top/bottom performers)
  - Segment, Category, Sub-Category comparisons
  - Discount vs Profit scatterplots
- **Key metrics**: Pivot tables, groupby sums for Sales/Profit/Quantity

## Key Findings
- High discounts correlate with profit losses
- Technology category leads in profit; Office Supplies lags
- Copiers, Phones, Bookcases show highest margins
- Regional trends: Steady sales growth except South region dip
- Home Office segment outperforms Consumer/Corporate

See the **Conclusion** section in the notebook for detailed insights.

## Requirements
Python 3.12+ with:
