# 📊 Sales & Demand Forecasting System

## 📌 Overview
This project builds a machine learning–based sales forecasting system using historical business data.

The system predicts future daily sales and helps businesses make informed decisions about:

- 📦 Inventory planning  
- 💰 Cash flow management  
- 👥 Staffing allocation  
- 📈 Demand trend analysis  

This project simulates how real businesses use ML-driven forecasting tools.

---

## ⚙️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Random Forest Regressor

---

## 🧠 Features Implemented

- Data cleaning and preprocessing
- Time-based feature engineering (day, month, year, weekday, week_of_year)
- Lag features (lag_1, lag_7, rolling_mean_7)
- Baseline & Improved forecasting models
- MAE & RMSE evaluation
- Monthly trend analysis
- Feature importance visualization
- 30-day future sales prediction
- Business interpretation of results

---

## 📈 Model Performance

Baseline Model:
- MAE ≈ 1675
- RMSE ≈ 2517

Improved Lag-Based Model:
- MAE ≈ 1593
- RMSE ≈ 2230

The improved model demonstrates enhanced forecasting accuracy using historical lag features.

---

## 🎯 Business Impact

This forecasting system helps organizations:

- Reduce overstocking
- Optimize procurement cycles
- Improve demand planning
- Make data-driven operational decisions

---

## 🚀 How to Run

```bash
pip install -r requirements.txt