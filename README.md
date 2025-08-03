# Demand-of-Electricity-in-Future
# Overview
This project aims to forecast hourly electricity demand using historical data and machine learning. Leveraging an XGBoost model, it predicts future demand based on factors like temperature, humidity, and time-based features.

# Goals
  Handle time-series electricity data
  Engineer useful features (e.g., day, holiday, weekend)
  Train an XGBoost regression model
  Evaluate with RMSE and MAE
  Visualize demand patterns

# Tools Used
  Python
  Pandas, NumPy
  Matplotlib, Seaborn
  Scikit-learn
  XGBoost
  Holidays (library)

# Dataset
Includes 5 years of hourly data:
  Columns: datetime, temperature, humidity, demand
  Features extracted: day of week, is weekend, is holiday, etc.

# Outcome
A robust forecasting model with insights into energy consumption trends—useful for energy planning, smart grids, and demand management.
