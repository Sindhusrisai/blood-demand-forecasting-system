Blood Demand Forecasting System
Overview

A data-driven system for forecasting blood demand in blood banks. The framework combines time-series decomposition and machine learning to capture trends, seasonal patterns, and short-term fluctuations for accurate daily demand prediction.

Problem

Blood demand is variable due to emergencies, seasonal effects, and operational constraints. Traditional methods fail to adapt to these non-stationary patterns, causing shortages or wastage.

Solution

STL decomposition for trend and seasonal patterns

Gradient Boosting / ensemble models for residual learning

Integration of temporal and contextual features (weekday, holiday, lag features)

Dataset

Synthetic blood demand time-series with features like historical usage, hospital admissions, donor availability, and calendar attributes.

Models

Baseline model

Random Forest

Gradient Boosting

Extra Trees

Hybrid STL + ML models

Performance evaluated using MAE and RMSE.

Output

Generates daily blood demand forecasts to support proactive inventory planning.

Example:

Date	Predicted Demand
2025-02-10	260 units
2025-02-11	254 units
2025-02-12	259 units
Tools

Python, Pandas, NumPy, Scikit-learn, XGBoost, Statsmodels (STL), Matplotlib, Google Colab
