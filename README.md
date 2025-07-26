# crypto-forecast-garch-cointegration
This project explores advanced time series techniques—namely ARIMA, GARCH, Granger Causality, and Vector Error Correction Models (VECM)—to forecast the volatility and market trends of two major cryptocurrencies: **Bitcoin** and **Ethereum**.
# Cryptocurrency Forecasting using GARCH and Cointegration
This project explores advanced time series techniques—namely ARIMA, GARCH, Granger Causality, and Vector Error Correction Models (VECM)—to forecast the volatility and market trends of two major cryptocurrencies: **Bitcoin** and **Ethereum**.

## Objective

To analyze and forecast the log returns of the market capitalizations of Bitcoin and Ethereum using statistical time series models. We aim to identify cointegration and volatility patterns for pair trading and risk estimation.

## Dataset

The data used in this project is obtained from:
- [Kaggle Cryptocurrency Price History](https://www.kaggle.com/datasets/sudalairajkumar/cryptocurrencypricehistory)

We used data for:
- `Bitcoin`: April 29, 2013 – July 6, 2021
- `Ethereum`: August 8, 2015 – June 6, 2021

## Methods Used

- Time Series Analysis:
  - ACF & PACF plots
  - ARIMA Modeling
  - Ljung-Box Test
  - Jarque-Bera Test
  - Augmented Dickey-Fuller Test
- Volatility Modeling:
  - ARCH-LM Test
  - GARCH(1,1) modeling
- Causality and Relationship Modeling:
  - Granger Causality
  - Vector Autoregression (VAR)
  - Johansen Cointegration Test
  - Vector Error Correction Model (VECM)

## Highlights

- Stationarity achieved via log return differencing
- ARIMA(1,1,1) selected based on AIC
- GARCH models revealed significant volatility clustering
- Cointegration tests suggest a long-run equilibrium relationship between BTC and ETH
- No short-run Granger causality, but long-run interdependence exists

## Forecast Results

The models predicted 10 future log returns for both BTC and ETH. These results can be extended for pricing or risk simulations.

## Tools & Technologies

- R (garchFit, tseries, urca, vars, tsDyn, forecast)
- Statistical modeling and hypothesis testing

## Project Structure
crypto-forecast-garch-cointegration/
│

├── data/ # Raw and processed CSVs

├── notebooks/ # R scripts or RMarkdowns for each modeling stage

├── results/ # Plots and tables

├── README.md # Project overview

└── final_report.pdf # Full project write-up (your uploaded PDF)
