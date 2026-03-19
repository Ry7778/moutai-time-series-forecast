# Moutai Stock Price Forecast (ARIMA)

## Project Overview
This project applies time series analysis to forecast the stock price of Kweichow Moutai using ARIMA modeling.

## Methodology
- Data preprocessing and time indexing
- Stationarity testing (ADF test)
- First-order differencing
- ARIMA model selection using AIC
- Forecasting future prices
- Model evaluation (MAE, RMSE, MAPE, R²)

## Results
- MAE: 352.57
- RMSE: 370.38
- MAPE: 20.26%
- R²: -9.65

## Tools
Python, Pandas, NumPy, Statsmodels, Matplotlib, Scikit-learn

## Notes
The ARIMA model captures general trends but performs poorly on volatile stock movements, indicating limitations of linear time series models in financial prediction.
