# Time Series Analysis of SPY, QQQ and VIX

## Project Overview

This project analyzes historical market data using three widely followed financial instruments:

- SPY (S&P 500 ETF)
- QQQ (Nasdaq-100 ETF)
- VIX (Volatility Index)

The goal is to explore market behavior through returns, volatility, moving averages, and correlations between equity markets and market volatility.

---

## Data Source

Data is retrieved directly from Yahoo Finance using the `yfinance` Python package.

Period analyzed:

- Start date: 2020-01-01
- Assets: SPY, QQQ, VIX

---

## Analysis Performed

### Return Analysis

- Daily percentage returns
- Log returns
- Cumulative returns

### Volatility Analysis

- 30-day rolling volatility

### Trend Analysis

- 50-day moving average
- 200-day moving average

### Cross-Asset Analysis

- Correlation matrix
- 30-day rolling correlations
- Comparison of SPY, QQQ, and VIX behavior

---

## Key Findings

- SPY and QQQ exhibit strong positive correlation due to their exposure to the broader equity market.
- VIX generally shows a negative relationship with equity returns, acting as a market fear indicator.
- Correlations are not constant and change over time.
- Market volatility increases significantly during periods of market stress.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- yfinance
- JupyterLab

---

## How to Run

Install dependencies:

```bash
pip install pandas numpy matplotlib yfinance
```

Launch jupyterlab:

```bash
jupyter lab
```

Open the notebook:

```text
analysis.ipynb
```