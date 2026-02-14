Energy Consumption Forecasting 📊

Task 3: Time Series Forecasting of Household Energy Usage

Author: Dua Ilyas
Date: February 2026

🎯 Objective

Forecast short-term household energy usage using historical time-based patterns.
Gain insights into daily and weekly consumption trends and compare the performance of multiple forecasting models.

📂 Dataset

Household Power Consumption Dataset
Source: UCI Machine Learning Repository

Features include:

Datetime – Timestamp of recording

Global_active_power, Global_reactive_power, Voltage, Global_intensity

Sub_metering_1, Sub_metering_2, Sub_metering_3

📝 Notebook Structure

Installation & Imports
Required libraries: pandas, numpy, matplotlib, seaborn, statsmodels, prophet, xgboost, scikit-learn

Data Loading & Preprocessing

Load the dataset

Handle missing values

Parse Datetime

Resample to hourly averages

Feature Engineering

Extract: hour, day, weekday/weekend, month

Modeling

ARIMA

Prophet

XGBoost Regressor

Evaluation

Metrics: Mean Absolute Error (MAE), Root Mean Squared Error (RMSE)

Visual comparison of actual vs predicted energy usage

Visualization

Time series plots

Forecast charts

🚀 Key Skills Gained

Time series forecasting

Feature engineering for temporal data

ARIMA, Prophet, and XGBoost modeling

Model comparison using MAE and RMSE

Temporal data visualization

📊 Results & Insights

Forecasts from ARIMA, Prophet, and XGBoost are visualized in the notebook.

XGBoost provides a strong predictive performance with numerical evaluation.

Clear daily and weekly energy consumption patterns were observed, supporting actionable insights for energy optimization.

📌 How to Run

Clone the repository:

git clone https://github.com/DuaIlyas24/energy-consumption-forecasting


Open the Jupyter Notebook: Task3_Energy_Forecasting.ipynb

Run all cells sequentially.

Visualizations and evaluation metrics will appear automatically in the notebook output.

🔗 GitHub Repository

https://github.com/DuaIlyas24/energy-consumption-forecasting
