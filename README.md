# STAT 495 : 

Exploring ARCH /GARCH methods and their application in modelling the changing variance of time in predicting stock prices

## Abstract

This project is a basic exploration of methods modelling the changing variance in time series models. More specifically, it is an introduction to Autoregressive Conditional Heteroskedasticity and Generalized Autoregressive Conditional Heteroskedasticity models `ARCH` and `GARCH`. It is an extension of the exploration and application of the Auto Regressive Integrated Moving Average methods `ARIMA` used to model future air quality measures conducted as part of the major's STAT 495 final project. In this study, we will see the application of these novel methods in modelling the changing variance of time in time series. The data used in this study are obtained from the S&P 500 index, which is a measure that estimates the performance of 500 companies listed in the United States Stock exchange market.

## Summary

The tasks for this project are defined as follows:

1. GARCH exposition to explain the usefulness of and background behind generalized autoregressive conditional heteroscedasticity models.
2. Use of the TSA (Time Series Analysis) and the rugarch packages to simulate and fit GARCH models to Stock Market data.
3. Use of the tseries package to fit ARIMA models for the same stock market data.
4. Comparison of the models above and interpretation of the findings yielded from fitting them to obtain stock price estimates. The response variables of interest are open, high, low or volume quantities provided from the S&P stock data.
