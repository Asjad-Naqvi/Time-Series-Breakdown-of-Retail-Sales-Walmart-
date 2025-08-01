# Time-Series-Breakdown-of-Retail-Sales-Walmart-
This Retail Store sales analysis is a project as per my internship at @Elevvo as a data analyst
Retail Sales Analysis & Forecasting


📌 Project Overview

This project analyzes Walmart retail sales data to uncover trends, seasonality, and store-level performance.
It also demonstrates basic time-series analysis techniques such as moving averages and exponential smoothing for forecasting.

The notebook (Retail_Analysis.ipynb) guides you step by step through:

Exploratory Data Analysis (EDA)

Visualization of trends & seasonal patterns

Revenue breakdown by stores

Simple forecasting approaches

📂 Dataset
Source: Walmart Sales Forecasting Dataset (Kaggle)

File Used: Walmart.csv

Columns:

Store: Store ID

Date: Week of sales (weekly data)

Weekly_Sales: Weekly revenue per store

Holiday_Flag: Indicator for holiday weeks

Temperature, Fuel_Price, CPI, Unemployment: Macroeconomic factors

🛠️ Steps in the Notebook
1. Data Preparation
Load dataset and inspect structure.

Convert Date column into datetime format.

Aggregate weekly sales into monthly totals for time-series analysis.

2. Exploratory Data Analysis (EDA)
Basic statistical summary of sales.

Check store distributions and sales ranges.

3. Sales Trend Analysis
Total monthly sales plotted over time.

Applied 3-month and 6-month rolling averages to smooth fluctuations.

Applied Exponential Smoothing (α=0.3) for trend forecasting.

4. Seasonality Analysis
Average monthly sales across multiple years.

Seasonal bar chart to highlight high/low demand months.

5. Revenue Breakdown
Identified Top 5 stores by revenue.

Plotted their monthly sales individually to compare store performance.

6. Forecasting (Bonus)
Introduced simple rolling mean & exponential smoothing as forecasting baselines.

Provides foundation for advanced models (e.g., ARIMA, SARIMA, Prophet).

📊 Visualizations
The notebook produces:

📈 Line plots of total sales with moving averages & exponential smoothing

📊 Seasonal bar charts of monthly averages

🏬 Store-level monthly sales comparisons for top stores

🚀 How to Run
Clone the repository / open the notebook.

Place Walmart.csv in the working directory.

Open Retail_Analysis.ipynb in Jupyter Notebook or JupyterLab.

Run cells sequentially to reproduce the analysis.

🔮 Future Improvements
Incorporate holiday effect modeling (Holiday_Flag).

Add external regressors (Fuel Price, CPI, Unemployment).

Deploy advanced forecasting models (Holt-Winters, SARIMA, Prophet).

Extend with store clustering to identify sales pattern groups.

📌 Author
Ali Asjad as per my task at @Elevvo
