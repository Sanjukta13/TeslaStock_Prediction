# TeslaStock_Prediction

#Stock Market Analysis and Forecasting (Tesla)

This project performs time series analysis and forecasting on Tesla (TSLA) stock data using Python. The analysis includes trend visualization, volatility analysis, moving averages, seasonal decomposition, and future price forecasting using Facebook Prophet.

The goal of this project is to understand stock market trends and predict future price movements using data science techniques.

#Technologies Used

Python

Pandas

NumPy

Matplotlib

Statsmodels

Prophet (Facebook Prophet)

Project Features

Data preprocessing and cleaning

Missing value analysis

Stock price trend visualization

Volume trend analysis

Moving average analysis (MA10 & MA50)

Volatility calculation

Seasonal decomposition of stock prices

Future stock price forecasting using Prophet

# Dataset

The dataset used in this project contains Tesla (TSLA) historical stock market data including:

Date

Open Price

High Price

Low Price

Close Price

#Data Analysis Performed
1️. Stock Price Trend

Visualization of Tesla closing price over time to observe long-term trends.

2️. Volume Analysis

Analysis of trading volume trends over time to understand market activity.

3️. Seasonal Decomposition

Using statsmodels to decompose the stock price into:

Trend

Seasonality

Residual components

4️. Moving Averages

Calculation of:

10-Day Moving Average (MA10)

50-Day Moving Average (MA50)
Used to identify trend direction and crossover signals.

5️. Volatility Analysis

Volatility calculated using rolling standard deviation of returns to understand market risk.

6️. Returns Analysis

Daily percentage returns calculated to measure stock performance fluctuations.

# Stock Price Forecasting

The project uses Facebook Prophet to forecast future stock prices.

Steps used:

Convert dataset into Prophet format (ds, y)

Train Prophet forecasting model

Generate future dates

Predict future stock prices
