# Assignment 17 - Forecasting Exchange Rates using Time Series Analysis

## Overview

This assignment focuses on forecasting exchange rates using historical time series data. The dataset contains exchange rate values between USD and Australian Dollar over time. The purpose of this assignment is to study historical exchange rate patterns and predict future values using different forecasting methods.

Two forecasting models are used in this assignment:

- ARIMA
- Exponential Smoothing

Both models are compared using error metrics to determine which forecasting technique gives more accurate predictions.

---

## Objective

The main objective of this assignment is to understand how time series forecasting works and how historical exchange rate data can be used to predict future values. The assignment also helps compare different forecasting techniques and identify the model that performs best for exchange rate prediction.

---

## Dataset Description

The dataset contains:

- Date column
- Exchange rate values between USD and Australian Dollar

The Date column is converted into datetime format and used as the index for time series analysis.

---

## Steps Performed

1. Loaded the exchange rate dataset
2. Converted the Date column into datetime format
3. Explored the data using graphs
4. Handled missing values
5. Split the dataset into training and testing sets
6. Used ACF and PACF plots for ARIMA parameter selection
7. Built ARIMA forecasting model
8. Built Exponential Smoothing forecasting model
9. Performed forecasting using both models
10. Compared both models using MAE, RMSE, and MAPE
11. Analyzed the results and selected the better model

---

## Models Used

### ARIMA
ARIMA stands for AutoRegressive Integrated Moving Average. It uses past observations and past errors to forecast future values.

### Exponential Smoothing
Exponential Smoothing gives more importance to recent values and less importance to older values.

---

## Evaluation Metrics

The following evaluation metrics are used:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Percentage Error (MAPE)

Lower values indicate better forecasting performance.

---

## Key Findings

- Both ARIMA and Exponential Smoothing were able to forecast future exchange rate values.
- ARIMA is useful when the data contains strong time-based relationships.
- Exponential Smoothing is simpler and gives more importance to recent values.
- The model with lower MAE, RMSE, and MAPE is considered better.

---

## Files Included

- assignment17_exchange_rate_forecasting.ipynb
- exchange_rate.csv
- README.md

---

## Conclusion

In this assignment, we explored exchange rate data and built two forecasting models: ARIMA and Exponential Smoothing. Both models were evaluated using different error metrics. This assignment helped understand how time series forecasting works and how it can be useful in finance, currency prediction, and business decision-making.

---

## Author

Tausif Ali
