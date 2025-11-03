# 🏪 Walmart Sales Forecasting

This project analyzes Walmart's weekly sales data to uncover trends, correlations, and forecast future sales using ARIMA time series modeling.

## 📊 Project Overview
- Cleaned and explored Walmart sales dataset
- Analyzed correlations between sales and factors like:
  - Unemployment
  - CPI (Consumer Price Index)
  - Temperature
- Identified top and worst performing stores
- Forecasted weekly sales using the ARIMA model

## ⚙️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels (ARIMA)

## 📁 Files Included
- `walmart_project.ipynb` → Google Colab notebook version  
- `walmart_project.py` → Python script version  

## 🧠 Key Insights
- Unemployment has a **negative correlation** with sales.
- CPI impacts sales differently across stores.
- Seasonal patterns affect weekly sales.

## 🔮 Forecasting
Used ARIMA to predict the next 12 weeks of sales for each store.

## 🚀 How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/walmart-sales-forecasting.git
   cd walmart-sales-forecasting
