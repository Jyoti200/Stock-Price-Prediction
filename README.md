# Stock Price Prediction using Time Series Forecasting

## Overview
This project aims to forecast stock prices using various time series forecasting algorithms, specifically ARIMA, SARIMA, and SARIMAX models. The data used is historical stock price data obtained from Yahoo Finance stock data. The main goal is to compare the performance of these models in predicting future stock prices based on past data.

## Dependencies
Ensure you have the following Python libraries installed:
- pandas
- NumPy
- matplotlib
- stats models

You can install them using pip:
```bash
pip install pandas numpy matplotlib statsmodels
```

## Dataset
The dataset used in this project contains historical stock price data. It includes the following columns:
- Date: The date of the trading day
- Open: The opening price of the stock
- High: The highest price reached during the day
- Low: The lowest price reached during the day
- Close: The closing price of the stock
- Volume: The trading volume of the day

## Files
- **data.csv**: CSV file containing the raw historical stock price data.

## Models
### ARIMA (AutoRegressive Integrated Moving Average)
ARIMA is a classical approach to time series forecasting that assumes the time series is stationary.

### SARIMA (Seasonal ARIMA)
SARIMA extends ARIMA by accounting for seasonality in the data.

### SARIMAX (Seasonal ARIMA with Exogenous Variables)
SARIMAX incorporates exogenous variables (such as external predictors) into the SARIMA model.

## Usage
1. **Data Preparation**: Ensure `data.csv` is in the project directory.
2. **Model Selection**: Choose the appropriate model (ARIMA, SARIMA, or SARIMAX) based on the characteristics of your data (e.g., presence of seasonality).
3. **Model Training**: Use historical data to train the selected model.
4. **Model Evaluation**: Evaluate the model using appropriate metrics (e.g., Mean Squared Error, Mean Absolute Error).
5. **Forecasting**: Generate forecasts using the trained model.
6. **Visualization**: Visualize the observed vs. predicted values to assess the model's performance.

