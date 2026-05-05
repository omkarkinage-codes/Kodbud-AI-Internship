
# Task 4: Stock Price Prediction

## 📌 Description
This project implements a **Linear Regression** model to predict future stock/index prices based on historical trends. It utilizes the `yfinance` API to fetch real-time market data and performs time-series forecasting.

## 🛠️ Technical Workflow
1. **Data Collection:** Fetched historical data for indices like **Google** using the Yahoo Finance library.
2. **Feature Engineering:** -  Converted Timestamps into **Ordinal Integers** to make them mathematically compatible with regression.
3. **Modeling:** Built a Linear Regression model to find the "line of best fit" for price growth.
4. **Evaluation:** Used **R2 Score** and **Mean Squared Error (MSE)** to measure how closely the trend line follows actual market movements.

## 📊 Parameters & Metrics
* **R2 Score:** ~0.66 (Indicates the model explains 66% of the price variance based on time).
* **Future Date:** April 25, 2026.
* **Prediction Engine:** `.predict()` method using transformed ordinal inputs.
