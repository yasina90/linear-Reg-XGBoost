# House Price Prediction with XGBoost 🏠

A simple yet effective implementation of **house price prediction** using the **XGBoost Regressor** algorithm. This project is built using Python and leverages libraries like Scikit-learn, XGBoost, and Matplotlib for modeling and visualization.

## 📌 Overview

This repository provides a complete workflow for predicting median home values using a set of socioeconomic and geographic features. The model is trained and evaluated using the classic **Boston Housing dataset**.

## 🔧 Features Used

| Feature | Description |
|--------|-------------|
| `per_capita_crime_rate` | Crime rate per capita |
| `avg_num_rooms_per_dwelling` | Average number of rooms per dwelling |
| `property_tax_rate` | Property tax rate |
| `pct_lower_status_population` | Percentage of lower-status population |
| `nox_concentration` | Nitrogen oxide concentration |
| ... | More features included — see full list in dataset |

## 📈 What's Included

- [x] Data loading and preprocessing
- [x] XGBoost model training
- [x] Cross-validation for robust performance estimation
- [x] Evaluation metrics: MAE, MSE, RMSE, R²
- [x] Visualization: Actual vs Predicted values with regression line
- [x] Feature importance plot

## 📦 Requirements

To run this project, ensure you have the following packages installed:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost