# Forecast-Exchange-Rates
### Time Series Forecast Exchange Rate on USD to INR 
1. Data provided is related to USD/INR Exchange rates. The objective is to understand the underlying
structure in the given dataset and come up with a suitable forecasting model which can effectively
forecast USD/INR exchange rate for the next 30 days.
2. This forecasting model will be used by exporting and importing companies to understand the
currency movements and accordingly set their revenue expectations.

Project – Python, Pandas, PyCaret, FB Prophet, XGBoost, LSTM, 
Built a time series forecasting model for USD/INR exchange rates to help import/export companies estimate currency trends.

Preprocessed 12,649 records, handled 5% missing data with forward fill, and applied log/differencing for stationarity.

Explored multiple models: ARIMA, FB Prophet, XGBoost, and PyCaret AutoML; selected LSTM as final model (RMSE: 0.0691).


