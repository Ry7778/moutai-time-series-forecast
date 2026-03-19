# Moutai Stock Forecast Report

## 1. Objective
This project aims to forecast Kweichow Moutai stock price using ARIMA.

## 2. Data
- Source: Historical stock data
- Variable: Closing price
- Time span: 2014–2024

## 3. Method
- ADF test → non-stationary
- First-order differencing → stationary
- ARIMA(2,1,2) selected via AIC

## 4. Results
- MAE: 352.57
- RMSE: 370.38
- MAPE: 20.26%
- R²: -9.65

## 5. Conclusion
ARIMA captures trend but fails to model volatility in stock prices.

## 6. Limitation
- Linear model limitation
- Poor performance on financial time series

## 7. Future Work
- Try LSTM / machine learning models