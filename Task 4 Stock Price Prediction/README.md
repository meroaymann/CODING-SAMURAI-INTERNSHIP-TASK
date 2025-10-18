For this advanced-level task, I worked on predicting future stock prices using time series forecasting techniques. I chose Microsoft (MSFT) stock data and applied the ARIMA (AutoRegressive Integrated Moving Average) model to forecast upcoming prices based on historical data.

Project Overview

The goal was to analyze the trend of stock prices over time and build a model that could predict future values accurately. Using the ARIMA model, I was able to capture the underlying pattern and forecast the next 30 business days.

What I Did

Collected MSFT daily closing prices (2015–2025) using the yfinance library.

Cleaned and prepared the dataset for modeling.

Checked for stationarity and applied first differencing (d=1) since the data was non-stationary.

Used a grid search to automatically find the best ARIMA order (4, 1, 5) based on AIC score.

Trained and tested the model, then visualized results with confidence intervals.

Generated a 30-day future price forecast.

Results

Best Model: ARIMA(4,1,5)

AIC: 12867.68

RMSE: 50.22

MAPE: 8.8%

The model performed well, showing accurate predictions and a reasonable confidence range.﻿


This project helped me understand how ARIMA models work for time series forecasting and how to evaluate prediction accuracy using RMSE and MAPE. The model achieved about 91% accuracy and successfully forecasted MSFT’s stock trend for the upcoming month.
