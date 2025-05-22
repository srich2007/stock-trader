# 📈 Moving Average Crossover Strategy Bot

This project is a simple yet fully functional backtesting engine for a **moving average crossover trading strategy** using Python and real historical stock price data from Yahoo Finance.

It simulates buying and selling a stock based on technical trend signals, and evaluates the strategy using key performance metrics.

---

## 🔍 What It Does

- Fetches daily stock price data via [`yfinance`](https://pypi.org/project/yfinance/)
- Calculates short- and long-term moving averages (e.g. 20 MA vs 50 MA)
- Generates trading signals based on crossover events:
  - **Buy** when short MA > long MA
  - **Sell** when short MA < long MA
- Simulates trading with:
  - Custom starting balance
  - Long/short positions
  - Strategy returns
  - Compounding
- Compares performance vs Buy & Hold benchmark

---

## 📊 Metrics Calculated

- ✅ Total Return
- ✅ Sharpe Ratio (risk-adjusted performance)
- ✅ Max Drawdown (worst drop from peak)
- ✅ Strategy Equity Curve
- ✅ Buy & Hold Comparison

---

## 📈 Visualization

Plots include:
- Close Price with Moving Averages
- Cumulative Return (Strategy vs Buy & Hold)

---

## ⚙️ How to Run

```bash
pip install yfinance matplotlib pandas numpy
