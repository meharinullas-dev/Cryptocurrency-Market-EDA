# Cryptocurrency Market Analysis Using Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project explores historical cryptocurrency market data using Python and Exploratory Data Analysis (EDA). It examines price movements, trading volume, daily returns, volatility, and correlations between Bitcoin and selected alternative cryptocurrencies.

The goal is to identify patterns in cryptocurrency performance and understand how market risk and relationships change during different volatility conditions.

## 🎯 Objectives

- Analyze historical prices and trading volumes of selected cryptocurrencies.
- Explore daily percentage returns and price distributions.
- Compare cryptocurrency performance using indexed prices.
- Measure rolling volatility and maximum drawdown.
- Investigate correlations between Bitcoin and altcoins during different Bitcoin volatility regimes.
- Examine average daily returns by day of the week.
- Export cleaned data and analytical summary tables.

## 🛠️ Technologies Used

- **Python**
- **Pandas** — data manipulation and analysis
- **NumPy** — numerical calculations
- **Matplotlib** — data visualization
- **Seaborn** — statistical visualizations
- **yfinance** — cryptocurrency market data collection
- **Jupyter Notebook** — analysis environment

## 📊 Dataset

Historical daily cryptocurrency data is collected from Yahoo Finance using the `yfinance` Python library.

The analysis covers these seven cryptocurrencies:

- Bitcoin (BTC)
- Ethereum (ETH)
- Solana (SOL)
- XRP
- Dogecoin (DOGE)
- BNB
- Cardano (ADA)

The observation period depends on data availability when the notebook is executed.

## 🔍 Analysis Performed

1. Data collection and inspection
2. Data cleaning and quality checks
3. Approximate USD-to-INR price conversion
4. Feature engineering, including daily returns and moving averages
5. Closing-price and daily-return distributions
6. Cryptocurrency price and indexed-performance comparisons
7. Return correlation analysis
8. Rolling volatility and maximum drawdown analysis
9. Bitcoin volatility regime and altcoin correlation comparison
10. Day-of-week return analysis
11. Statistical summary and performance comparison

## 📈 Key Research Question

Do alternative cryptocurrencies become more closely correlated with Bitcoin during periods of high Bitcoin volatility?

The notebook compares Bitcoin–altcoin daily return correlations during high- and lower-volatility periods. The findings should be interpreted using the calculated results and the number of observations in each regime.

## 🚀 How to Run the Project

1. Download or clone this repository.
2. Install Python and Jupyter Notebook.
3. Install the required libraries:

   ```bash
   pip install pandas numpy yfinance requests matplotlib seaborn jupyter
   ```

4. Open the notebook in Jupyter Notebook or JupyterLab.
5. Run the cells from top to bottom.

An internet connection is required to retrieve current market data and the exchange rate.

## ⚠️ Limitations

- Results depend on the selected cryptocurrencies and observation period.
- External data sources and libraries may change.
- Correlation does not imply causation.
- INR-converted historical prices are approximate when a single reference exchange rate is applied to all dates.
- Cryptocurrency markets are volatile, and historical performance does not guarantee future results.

## 👩‍💻 Author

**Meharin Ullas**

BCA Graduate | Aspiring Data Analyst

GitHub: [meharinullas-dev](https://github.com/meharinullas-dev)
