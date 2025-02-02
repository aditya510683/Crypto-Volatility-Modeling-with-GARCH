# Crypto-Volatility-Modeling-with-GARCH

This project analyzes the volatility of **Bitcoin (BTC)** and **Ethereum (ETH)** using the GARCH(1,1) model. It provides insights into the comparative volatility patterns of these two major cryptocurrencies over the past year.

## Key Features
- Implements the **GARCH(1,1)** model for volatility estimation.
- Visualizes volatility trends for BTC and ETH over a 365-day period.
- Compares the volatility patterns to identify which asset is more volatile.

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
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `arch`

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/garch-volatility-analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the script:
   ```bash
   python garch_analysis.py
   ```
2. View the output graph to analyze BTC and ETH volatility.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
Feel free to contribute to improve the project!
