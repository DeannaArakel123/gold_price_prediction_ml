# 🟡 Gold Price Forecasting (INR & USD)

## 📌 Project Overview
This project focuses on forecasting gold prices using machine learning techniques. It analyzes both:

- 🌍 Global gold prices (USD)
- 🇮🇳 Indian gold prices via ETF (INR)

The model predicts the next **30 days of gold prices** and generates structured outputs for analysis.

---

## 🎯 Objectives
- Analyze recent gold price trends
- Build a predictive model using historical data
- Forecast future prices (30 days)
- Compare INR vs USD gold movement
- Quantify expected price changes

---

## 📊 Key Features
- 📥 Data fetched using Yahoo Finance API (`yfinance`)
- 🧠 Feature Engineering:
  - Lag features (1-day, 7-day)
  - Rolling mean and volatility (7-day)
- 🤖 Model:
  - Linear Regression
- 📈 Forecast:
  - 30-day price prediction
- 📉 Confidence Intervals:
  - ±2 standard deviations

---

## 📈 Results & Insights
- The model indicates a **short-term downward trend** in gold prices  
- Estimated decline: **~12% to 14%**  
- Confidence intervals highlight market uncertainty  

---

## 📄 Output Files
The model generates CSV files containing day-by-day forecasts:

- `gold_price_forecast_inr_usd_30days.csv` → Main forecast output  
- `gold_forecast_YYYY-MM-DD.csv` → Date-wise generated forecast  

Each file includes:
- Predicted prices (INR & USD)
- Upper and lower confidence bounds
- 30-day forecast horizon

---

## 🛠️ Tech Stack
- Python
- Pandas & NumPy
- Matplotlib
- Scikit-learn
- yFinance

---

## 📁 Project Structure
