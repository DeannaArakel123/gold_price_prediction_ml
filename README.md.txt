# 🟡 Gold Price Forecasting (INR & USD)

## 📌 Overview
This project analyses and forecasts gold prices using machine learning techniques.  
It compares gold price trends in both **USD (Global Market)** and **INR (Indian Market via ETF)**.

---

## 📊 Features
- Historical data fetched using Yahoo Finance
- Feature engineering:
  - Lag features (lag_1, lag_7)
  - Rolling mean & standard deviation
- Model used:
  - Linear Regression
- 30-day price forecast
- Confidence intervals (±2σ)
- Comparison between INR & USD gold trends

---

## 📈 Output
- Actual vs Predicted price plots
- Confidence intervals visualisation
- Expected percentage fall calculation
- Day-by-day forecast exported as CSV

---

## 🧠 Key Insights
- Model predicts a **short-term downward trend** in gold prices
- Estimated decline:
  - ~12–14% (based on current data)
- Highlights volatility using statistical confidence intervals

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Matplotlib
- Scikit-learn
- yFinance API

---

## 📁 Files
- `gold_forecast.py` → Main script
- `Gold_Forecast_YYYY-MM-DD.csv` → Forecast output
- `plots/` → Visualization outputs

---

## 🚀 How to Run
```bash
pip install yfinance pandas numpy matplotlib scikit-learn
python gold_forecast.py