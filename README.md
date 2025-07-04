# Statistics-Project

# Retail Insights Dashboard

Retail Insights Dashboard is a Streamlit application that performs end-to-end analysis of retail sales data—generating synthetic data, computing key statistics, running hypothesis tests, and producing interactive visualizations.

## Key Components:

### Data Generation & Ingestion

Simulates sales for 20 products across 4 categories (Electronics, Clothing, Home, Sports) using a Poisson distribution (λ=20) for units sold and a 20-day date range (2023-01-01 to 2023-01-20). 

## Statistical Analysis

### Descriptive statistics:

Count: 20

Mean units sold: 18.8

Median: 18.5

Mode: 17

Std Dev: 3.30

## Category breakdown:

Home (Total: 181; Avg: 20.11; SD: 3.72)

Sports (Total: 101; Avg: 16.83; SD: 2.71)

Electronics (Total: 73; Avg: 18.25; SD: 2.22)

Clothing (Total: 21; Avg: 21.00; SD: N/A)

## Inferential statistics:

95% confidence interval for mean units sold: (17.25, 20.35)

One-sample t-test vs. target mean of 20: t = –1.63, p = 0.1206 (fail to reject H₀) 

## Interactive Visualizations

Histogram with KDE overlay, annotated with mean/median/mode

Boxplots of units sold by category

Bar chart of total units sold per category

All rendered live in the Streamlit UI using Matplotlib and Seaborn ding sales patterns.”
