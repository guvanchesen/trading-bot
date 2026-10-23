# Automated Trading Bot with Backtesting

Course project for **IT Project: Advanced Concepts of Algorithmics and Software Development** (VIZJA University, Warsaw).
Topic 2 – Automated Trading Bot. Individual project by Guvanch.

> ⚠️ For educational purposes only. This project uses simulated trading and is not financial advice. No real money is used.

## About the project

This bot tests trading strategies on historical market data (backtesting) and runs them in simulated trading (paper trading).
It calculates technical indicators, generates buy and sell signals, applies risk rules, and measures the results with clear metrics.

## Planned features

- Download historical price data (yfinance) and store it in a database
- Technical indicators: SMA, EMA, RSI, Bollinger Bands
- Strategies: moving-average crossover, RSI mean-reversion, Bollinger breakout
- Backtesting engine without look-ahead bias
- Risk management: stop-loss, take-profit, position sizing
- Metrics: total return, maximum drawdown, Sharpe ratio, win rate
- Web dashboard with price charts and buy/sell markers

## Technologies

Python, pandas, NumPy, yfinance, FastAPI, React, Chart.js, MongoDB, pytest, Docker, GitHub Actions

## Project structure (planned)

```
trading-bot/
├── data/          # data download and storage
├── indicators/    # SMA, EMA, RSI, Bollinger Bands
├── strategies/    # buy/sell rules
├── backtest/      # backtesting engine
├── risk/          # stop-loss, position sizing
├── api/           # FastAPI backend
├── frontend/      # React dashboard
└── tests/         # pytest tests
```

## Status

| Milestone | Description | Status |
|---|---|---|
| M1 | Project proposal and repository setup | In progress |
| M2 | Data loader and indicators | Planned |
| M3 | Strategies and backtesting engine | Planned |
| M4 | Risk management and metrics | Planned |
| M5 | API and dashboard | Planned |
| M6 | Testing, Docker, CI/CD, final report | Planned |

## How to run

Setup instructions will be added in Milestone 2.
