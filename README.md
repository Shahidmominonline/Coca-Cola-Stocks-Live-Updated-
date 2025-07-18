# Coca-Cola Stock Price Analysis & Forecasting

## Project Overview

This project analyzes historical Coca-Cola (KO) stock data to:

* Decompose price trends using time-series models.

* Forecast future prices using ARIMA and ML models (XGBoost, Random Forest).

* Evaluate model performance with RMSE, MAE, and MAPE.

## Dataset
**Name**: Coca-Cola Stocks(Live and Updated)

**Time Period**: 2015–Present

**Columns**: Date, Open, High, Low, Close, Volume, Dividends, stock_split

## Tech Stack

* Pandas, Numpy, matplotlib, statsmodels, yfinance, scikiy-learn

---

## Code Structure
**1. Data Preprocessing**

* Handles timezone issues, missing values, and split-adjusted pricing.

* Converts dates to datetime and sets frequency for time-series modeling.

**2. Exploratory Data Analysis (EDA)**

* Visualizations: Line Plots, volume-price correlation and yield calculation.

Statistical Analysis: Skewness (1.38), kurtosis (1.17), variance (225.98).

**3. Time-Series Decomposition**

* Trend, Seasonality, Residuals plotted separately.

* Moving averages-SMA and EMA

**4. Forecasting Models**

* ARIMA for baseline predictions.

* Machine Learning (XGBoost, Random Forest) for enhanced accuracy.

**5. Model Evaluation**

* Metrics: RMSE, MAE, MAPE.

* Visualization: Actual vs. Predicted prices with confidence intervals.

## Key Findings
* CAGR: 12.35% (2015–Present).

* Price-Volume Correlation: 0.46 (moderate positive relationship).

* Best Model: SARIMA outperformed XGBoost for 30-day forecasts.








