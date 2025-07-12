# Data-Science-Forecasting-Challenge
Weekly Sales Forecasting Challenge
📋 Project Overview
This project implements a comprehensive time series forecasting solution for predicting weekly sales quantities across multiple product categories, channels, and brands. The solution includes thorough exploratory data analysis, feature engineering, model training, validation, and forecasting for a 3-month horizon.
🎯 Objectives

Explore and understand weekly sales data patterns
Build a robust forecasting model using machine learning
Validate model performance on the last 3 months (Jun-Jul-Aug 2024)
Generate accurate forecasts for the next 3 months (Sep-Oct-Nov 2024)
Provide monthly accuracy metrics and comprehensive analysis

Step 1: Exploratory Data Analysis
What this notebook does:

✅ Data quality assessment and cleaning
✅ Missing value and outlier detection
✅ Temporal pattern analysis
✅ Seasonal decomposition
✅ Category-wise sales breakdown
✅ Individual time series analysis

Step 2: Forecasting and Modeling

What this notebook does:

✅ Feature engineering (time-based, lag, rolling statistics)
✅ Model training with Random Forest
✅ Validation on last 3 months (Jun-Jul-Aug 2024)
✅ Monthly accuracy calculation
✅ Forecast generation for next 3 months (Sep-Oct-Nov 2024)
✅ Model persistence and reproducibility

📈 Model Performance
Validation Metrics
The model is validated on the last 3 months of available data:

Validation Period: June - August 2024
Accuracy Formula: 1 - Σ|ŷ - y|/Σy
Monthly Accuracy Breakdown: Provided for each validation month
Additional Metrics: MAE, RMSE, R² score

Key Features Used

Time-based Features: Year, month, quarter, cyclical encodings
Lag Features: 1, 2, 3, 4, 8, 12 weeks historical values
Rolling Statistics: Moving averages and standard deviations
Categorical Features: Encoded channel, brand, category information

🔮 Forecast Output
Generated Forecasts

Period: September - November 2024
Granularity: Weekly forecasts for each SerialNum
Format: CSV files with detailed predictions
Aggregations: Monthly totals and category breakdowns

