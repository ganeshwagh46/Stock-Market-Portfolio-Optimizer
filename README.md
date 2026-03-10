# Stock Market Portfolio Optimizer 📈
A Python-based tool for sectoral stock analysis, Monte Carlo simulation, and Risk-Adjusted Portfolio Optimization.

A quantitative finance project that identifies top-performing stocks across Indian sectors (Banking, IT, Auto, etc.) and optimizes asset allocation using Monte Carlo simulations.

## Key Features
- **Sectoral Quant Analysis:** Filters 30+ stocks based on Sharpe Ratio, ROE, and P/E.
- **Monte Carlo Simulation:** Analyzes 5,000 random portfolios to find the **Maximum Sharpe Ratio** weights.
- **Risk Metrics:** Calculates **Value at Risk (VaR)** and **Market Beta** vs. Nifty 50.
- **Diversification:** Features a Correlation Heatmap to verify sector-wise hedging.

## Performance Results
- **Portfolio Return:** 27.38% (Annualized)
- **Portfolio Beta:** 0.73 (Defensive/Stable)
- **Alpha Generated:** +25.59% vs. Nifty 50 Benchmark

## Tech Stack
- Python (Pandas, Numpy, Matplotlib, Seaborn)
- Yahoo Finance API (yfinance)
