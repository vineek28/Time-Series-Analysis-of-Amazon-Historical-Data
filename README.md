📈 AMZN Daily Return Forecasting:

Time Series Analysis & Model Evaluation
Project Overview

This project investigates the predictability of daily stock returns for Amazon (AMZN) using classical time-series modeling techniques.
The objective is to determine whether past returns contain meaningful linear predictive information for forecasting next-day returns.

The modeling pipeline follows a disciplined statistical workflow:
Data preprocessing, Stationarity testing, Autocorrelation analysis, Baseline modeling, AR(1) model comparison, Out-of-sample evaluation

📊 Dataset:

Source: Kaggle (Yahoo Finance via yfinance)
Asset: Amazon (AMZN)
Frequency: Daily
Features:Date, Open, High, Low, Close, Volume

So Far (02/15/2025):
Returns are stationary.
Returns exhibit no meaningful linear autocorrelation.
AR(1) does not outperform naive mean forecast.
Daily AMZN returns behave approximately as white noise in the mean.
This aligns with the Weak Form Efficient Market Hypothesis.
