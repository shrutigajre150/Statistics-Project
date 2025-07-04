# Statistics-Project

# Retail Insights Dashboard

### 📊 Project Overview
Retail Insights Dashboard is an interactive Streamlit application that provides a comprehensive statistical analysis of retail sales data. It’s designed to help retail managers and data analysts quickly explore sales performance across product categories, identify trends, and make data-driven decisions.

### 🔑 Key Features
#### Descriptive Statistics

Calculates count, mean, median, mode, standard deviation, and quartiles for units sold.

Breaks down total, average, and variability of sales by category.

Implemented in app.py using Pandas and NumPy for fast, in-memory computation. 

#### Inferential Statistics

Computes a 95% confidence interval for the mean units sold.

Performs a one-sample t-test against a target mean (e.g., 20 units) to determine statistical significance.

Powered by SciPy’s statistical functions to deliver reliable hypothesis testing. 

#### Interactive Visualizations

Histogram with KDE overlay, annotated with mean, median, and mode.

Boxplot showing distribution and outliers of units sold by category.

Bar Plot summarizing total units sold per category.

Built with Matplotlib and Seaborn and seamlessly embedded into the dashboard. 

#### Synthetic Data Generation

Simulates a realistic retail dataset of 20 products across four categories (Electronics, Clothing, Home, Sports) using a Poisson distribution.

Ensures reproducibility with a fixed random seed.

Defined in the generate_data() function of the Streamlit app. 

#### Business Context 

Clear business use case: “Optimize inventory and marketing by understanding sales patterns.”
