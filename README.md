# ChocoScope: Retail Intelligence & Revenue Forecasting for a Global Chocolate Brand

## Description

**ChocoScope** is a comprehensive data analysis project that explores sales data for a global chocolate brand. The project covers the entire data science pipeline: data cleaning, feature engineering, exploratory analysis, and predictive modeling to forecast revenue. The goal is to derive actionable business insights and build accurate revenue forecasting models to support strategic decision-making.

The analysis leverages multiple datasets—sales, customers, products, stores, and calendar—to understand customer behavior, product performance, store effectiveness, and the impact of discounts on profitability.

## Features

- **Data Integration**: Merges five distinct CSV files into a single, enriched dataset.
- **Feature Engineering**: Creates time-based features (month, quarter, weekday), customer tenure, discount-adjusted price, profit margins, and basket-level aggregations.
- **Exploratory Data Analysis (EDA)**: Visualizes revenue trends, category performance, store rankings, customer segmentation, and correlation analysis.
- **Predictive Modeling**: Builds and compares three regression models (Linear Regression, Random Forest, Gradient Boosting) to predict revenue.
- **Model Evaluation**: Uses MAE, RMSE, and R² to assess model performance; Random Forest achieves near-perfect accuracy.
- **Statistical Testing**: Performs t-tests to compare revenue between loyalty and non-loyalty customers, and OLS regression to quantify the effect of discount and quantity on revenue.

## Dataset Overview

The analysis uses the **Chocolate Sales Dataset (2023–2024)** from Kaggle, which contains five tables:

- **sales.csv** (1,000,000 rows): Order-level transactional data including order ID, date, product ID, store ID, customer ID, quantity, unit price, discount, revenue, cost, profit.
- **customers.csv** (50,000 rows): Customer demographics (age, gender, loyalty membership, join date).
- **products.csv** (200 rows): Product details (name, brand, category, cocoa percentage, weight).
- **stores.csv** (100 rows): Store metadata (name, city, country, type).
- **calendar.csv** (731 rows): Date attributes (year, month, day, week, day of week).

## Technologies Used

- **Python 3**
- **Data Manipulation**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn, Plotly
- **Statistical Analysis**: SciPy, Statsmodels
- **Machine Learning**: Scikit-learn (Linear Regression, Random Forest, Gradient Boosting, pipelines, preprocessing)
- **Environment**: Jupyter Notebook / Google Colab

## Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/NazeerAman/ChocoScope.git
   cd chocoscope
