# Exploratory Data Analysis & Statistical Insights

## Project Overview
This project performs comprehensive exploratory data analysis on a cleaned retail-sales dataset. The notebook combines descriptive statistics, distribution analysis, anomaly detection, correlation analysis, multivariate visualizations, and formal statistical hypothesis testing.

## Analysis Included
- Mean, median, standard deviation, quartiles and summary statistics
- Histograms and box plots for distribution and anomaly analysis
- IQR-based outlier counts
- Spearman correlation matrix and heatmap
- Discount vs profit-margin multivariate analysis
- Product × region profitability heatmap
- Monthly revenue and profit trend
- Three business-focused hypothesis tests
- Top five management-oriented findings

## Hypotheses Tested
1. **Discount vs profit margin:** Spearman rank correlation
2. **Online vs Store sales:** Mann–Whitney U test
3. **Profit differences across products:** Kruskal–Wallis H test

## Key Results
- Discount percentage showed essentially no relationship with profit margin (Spearman ρ ≈ 0.002; p ≈ 0.846).
- Online vs Store order values were not significantly different (Mann–Whitney p ≈ 0.370).
- Profit distributions differed significantly across products (Kruskal–Wallis H ≈ 8090.90; p < 0.001).
- Laptop and Tablet were the largest total-profit contributors.
- Smartphone had the highest average profit margin among the product categories.

## Files
- `Exploratory_Data_Analysis_Statistical_Insights.ipynb` — completed EDA notebook with charts, statistical tests and markdown insights.
- `clean_retail_sales.csv` — cleaned dataset used by the notebook.
