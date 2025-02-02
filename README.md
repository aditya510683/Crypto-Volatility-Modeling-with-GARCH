# Cryptocurrency Volatility Modelling 

![Volatility Plot Example](volatility_plot.png)

A Python-based project for modeling and analyzing cryptocurrency price volatility using GARCH-family models. This implementation automatically selects the best volatility model based on statistical criteria and provides visual insights into market dynamics.

## 📌 Project Description

This project models price volatility for Bitcoin (BTC) and Ethereum (ETH) using:
- **GARCH** (Generalized Autoregressive Conditional Heteroskedasticity)
- **EGARCH** (Exponential GARCH)
- **GJR-GARCH** (Glosten-Jagannathan-Runkle GARCH)

Key features:
- Automated data fetching from CoinGecko API
- Model comparison using AIC/BIC criteria
- Best model selection for volatility estimation
- Interactive volatility visualization
- Comprehensive output analysis

## 🚀 Features

- **Data Pipeline**
  - Daily price data fetching for cryptocurrencies
  - Log returns calculation
  - Missing data handling
  
- **Model Framework**
  - GARCH(1,1) implementation
  - EGARCH(1,1) with leverage effects
  - GJR-GARCH(1,1) with asymmetric volatility modeling
  
- **Analytics**
  - Automated model selection (AIC/BIC)
  - Conditional volatility visualization
  - Comparative analysis of BTC vs ETH volatility

## 📋 Requirements

- Python 3.8+
- Required packages:
  ```text
  pandas >= 1.4.3
  numpy >= 1.22.4
  requests >= 2.28.1
  matplotlib >= 3.5.3
  arch >= 5.3.1
