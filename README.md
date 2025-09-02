# 🛒 Demand Forecasting Using Hierarchical Time-Series Forecasting

**📌 Overview**

This project implements hierarchical time series forecasting on Walmart’s M5 competition dataset, focusing on 28-day ahead demand prediction across multiple aggregation levels (item, store, state, and total). The goal is to enhance demand planning accuracy using advanced statistical and machine learning models with forecast reconciliation techniques.

**⚙️ Features**

- Data Processing: Cleaned and structured 30,000+ time series across items, stores, and states.

- Forecasting Models: Implemented ARIMA and Ridge Regression for short-term forecasts.

- Hierarchical Aggregation: Created forecasts at multiple levels – item, store, state, and total.

- Reconciliation Methods: Applied Bottom-Up (BU) and Minimum Trace (MinT) to improve forecast consistency across hierarchy levels.

- Evaluation: Compared performance using RMSE and MAPE across levels.

**📊 Key Results**

- Generated 28-day ahead forecasts for all hierarchy levels.

- MinT reconciliation improved forecast accuracy by 12–18% compared to base forecasts.

- Large outlets showed stronger forecast stability, while smaller outlets had higher variance.

- Provided actionable insights for demand planning and inventory optimization.

**🚀 Tech Stack**

- Python (Pandas, NumPy, Scikit-learn, Statsmodels)

- Forecasting: ARIMA, Ridge Regression

- Visualization: Matplotlib, Seaborn

- Forecast Reconciliation: Bottom-Up, MinT
