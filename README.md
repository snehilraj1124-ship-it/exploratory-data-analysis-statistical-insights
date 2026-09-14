# Exploratory Data Analysis & Statistical Insights

## Project Overview

This project performs comprehensive Exploratory Data Analysis (EDA) on a retail sales dataset to uncover important business patterns, relationships, anomalies, and statistical insights.

The analysis focuses on descriptive statistics, data distributions, correlation analysis, anomaly detection, multivariate visualizations, and formal statistical hypothesis testing.

## Objectives

- Calculate descriptive statistics including mean, median, standard deviation, and quartiles.
- Analyze distributions of important business variables.
- Detect potential anomalies using histograms and box plots.
- Examine relationships between numerical variables using correlation analysis.
- Create multivariate visualizations to identify business patterns.
- Formulate and test three business-focused statistical hypotheses.
- Summarize the most important findings and business implications.

## Dataset

The analysis uses a cleaned retail sales dataset containing transaction-level information.

Key variables include:

- Order ID
- Order Date
- Customer ID
- Product
- Region
- Sales Channel
- Quantity
- Unit Price
- Discount Percentage
- Sales Amount
- Cost Amount
- Profit
- Profit Margin Percentage

## Analysis Performed

### 1. Descriptive Statistics

Summary statistics are calculated for major numerical variables, including:

- Quantity
- Unit Price
- Discount Percentage
- Sales Amount
- Cost Amount
- Profit
- Profit Margin Percentage

The analysis includes count, mean, median, standard deviation, minimum, maximum, and quartiles.

### 2. Distribution & Anomaly Analysis

Histograms are used to understand the distribution of sales, profit, and profit margins.

Box plots are used to identify potentially unusual observations. An IQR-based method is also applied to quantify potential outliers.

### 3. Correlation Analysis

A Spearman correlation matrix is generated to examine relationships between:

- Quantity
- Unit Price
- Discount
- Sales
- Cost
- Profit
- Profit Margin

A correlation heatmap provides a visual representation of these relationships.

### 4. Multivariate Analysis

Multiple visualizations are created to explore business patterns across different dimensions.

These include:

- Discount vs Profit Margin by Sales Channel
- Product vs Region Profit Margin Heatmap
- Monthly Revenue and Profit Trends

## Statistical Hypothesis Testing

Three business hypotheses are tested using a significance level of α = 0.05.

### Hypothesis 1: Discount and Profit Margin

**Null Hypothesis (H₀):** Discount percentage has no monotonic relationship with profit margin.

**Alternative Hypothesis (H₁):** Discount percentage is negatively associated with profit margin.

**Statistical Test:** Spearman Rank Correlation

### Hypothesis 2: Online vs Store Sales

**Null Hypothesis (H₀):** Order-level sales distributions are the same for Online and Store channels.

**Alternative Hypothesis (H₁):** Order-level sales distributions differ between Online and Store channels.

**Statistical Test:** Mann–Whitney U Test

### Hypothesis 3: Product Profitability

**Null Hypothesis (H₀):** All product categories have the same profit distribution.

**Alternative Hypothesis (H₁):** At least one product category has a different profit distribution.

**Statistical Test:** Kruskal–Wallis H Test

## Key Business Insights

The analysis evaluates:

1. Whether higher discounts are associated with lower profit margins.
2. Whether Online and Store channels show different sales behavior.
3. Whether profitability varies significantly across product categories.
4. Which variables are strongly related to revenue and profitability.
5. Whether unusual transactions require further business or data-quality investigation.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

## Project Files

- `Exploratory_Data_Analysis_Statistical_Insights.ipynb` — Complete EDA notebook with analysis, visualizations, statistical tests, and findings.
- `clean_retail_sales.csv` — Cleaned retail sales dataset used for the analysis.
- `README.md` — Project documentation.

## Conclusion

This project demonstrates an end-to-end exploratory data analysis workflow for retail sales data. The combination of descriptive statistics, visualization, correlation analysis, anomaly detection, and hypothesis testing provides a structured approach to transforming transaction data into actionable business insights.

The notebook is designed to be reproducible and can be rerun using the provided dataset.
