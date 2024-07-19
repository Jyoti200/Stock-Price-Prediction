# Stock Price Prediction using Time Series Forecasting
![image](https://github.com/user-attachments/assets/32021325-6424-4ca7-b491-15b3bc69ce40)


## Buisness Goal
The goal of this project is to predict future stock prices by analyzing historical data from Yahoo Finance. We will evaluate and compare the effectiveness of different forecasting methods to determine which one offers the most accurate predictions. The ultimate aim is to provide actionable insights that can help in making informed investment decisions.

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


