Stock Price Time Series Forecasting
This project demonstrates a comprehensive workflow for analyzing and forecasting daily stock market prices using Python. Focusing on Google (GOOGL) stock data, the notebook progresses from raw data extraction to predictive modeling using ARIMA techniques.

* Key Features
Data Extraction: Automated data fetching using the yfinance API.

Exploratory Data Analysis (EDA): Visualizing trends, histograms, and distributions of Open, Close, and Volume data.

Trend Analysis: Implementation of 7-day Moving Averages to smooth volatility.

Decomposition: Breaking down time series into Trend, Seasonality, and Residual components.

Statistical Testing: Stationarity checks using the Augmented Dickey-Fuller (ADF) test.

Forecasting: Building and evaluating an ARIMA(1, 0, 0) model to predict future closing prices.

* Technologies Used
Python (Pandas, NumPy)

Visualization: Matplotlib, Seaborn

Time Series: Statsmodels (ARIMA, seasonal_decompose)

Data Source: Yahoo Finance (yfinance)

* Project Results
The project evaluates the ARIMA(1, 0, 0) model using Mean Absolute Error (MAE) and analyzes the implications of model underfitting when dealing with non-stationary financial data
