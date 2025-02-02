# Crypto-Volatility-Modelling-with-GARCH

This project analyzes the volatility of **Bitcoin (BTC)** and **Ethereum (ETH)** using the GARCH(1,1) model. It provides insights into the comparative volatility patterns of these two major cryptocurrencies over the past year.

## Key Features
- Implements the **GARCH(1,1)** model for volatility estimation.
- Visualizes volatility trends for BTC and ETH over a 365-day period.
- Compares the volatility patterns to identify which asset is more volatile.
  
## Data Source
The historical price data for Bitcoin and Ethereum is retrieved from **CoinGecko** using their free API. 

### API Endpoint:
`https://api.coingecko.com/api/v3/coins/{crypto}/market_chart?vs_currency=usd&days=365&interval=daily`

## Results
From the analysis:
- **Ethereum (ETH)** exhibits higher volatility compared to **Bitcoin (BTC)**.
- ETH has larger spikes and a broader volatility range, making it more sensitive to market events.

## Graph
The generated plot highlights the volatility trends for BTC and ETH:
- **Blue Line**: BTC GARCH(1,1) Volatility
- **Orange Line**: ETH GARCH(1,1) Volatility

![Volatility Graph](path/to/your/image.png)

## Requirements
- Python 3.8+
- Libraries:
  - `pandas` for data manipulation
  - `numpy` for numerical calculations
  - `matplotlib` for plotting
  - `arch` for implementing GARCH models
  - `requests` for fetching data from the CoinGecko API


Feel free to contribute to improve the project!
