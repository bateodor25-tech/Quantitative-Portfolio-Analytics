📄 Executive Summary
In an era where financial markets move in microseconds, relying on static spreadsheets is a competitive disadvantage. This project transitions from passive monitoring to active, data-driven portfolio management.

Built with Python, this automated pipeline tracks current performance, calculates risk metrics (VaR, Drawdowns), and simulates thousands of future market scenarios using Monte Carlo methods to identify algorithmic trading opportunities.

🛠️ Tech Stack
Python Libraries: Pandas, NumPy, yFinance, Matplotlib, Seaborn

Data Source: Live Google Sheets API & Yahoo Finance

Concepts: Modern Portfolio Theory (MPT), Geometric Brownian Motion (GBM), Technical Analysis (RSI, Bollinger Bands).

📊 Key Features
1. Automated Data Pipeline
Dynamic ingestion of portfolio holdings from Google Sheets.

Real-time price extraction and normalization for comparative analysis.

2. Advanced Risk Analysis
Underwater Plot: Visualizing maximum drawdowns and recovery periods.

Distribution Analysis: Identifying "Fat Tails" in daily returns (non-normal distribution risks).

Efficiency Scorecard: Calculation of Beta, Alpha, Sharpe Ratio, and Sortino Ratio against the S&P 500 benchmark.

3. Stochastic Forecasting (Monte Carlo)
Simulation of 1,000 future market scenarios over a 252-day horizon.

Estimation of 95% Confidence Intervals (Optimistic vs. Pessimistic outcomes).

4. Technical Analysis Dashboard
An algorithmic signal generator that scans holdings for:

RSI Divergences: Identifying Oversold (<30) or Overbought (>70) conditions.

Bollinger Band Breakouts: Detecting volatility squeezes and price anomalies.

Trend Confirmation: SMA 50 crossovers.
