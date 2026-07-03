# Stock Analysis Dashboard

A Python-based analysis of RELIANCE.NS stock price data, covering returns, volatility, and moving averages, benchmarked against the Nifty 50 index.

## What this does
- Pulls historical OHLCV data using yfinance
- Calculates daily and cumulative returns
- Computes 20-day rolling volatility
- Plots 20-day and 50-day moving averages to identify crossover signals
- Benchmarks performance against the Nifty 50 index

## Key findings
-Most daily returns clustered tightly between -2% and +2%, 
with a few outlier days showing larger spikes (both gains and losses).

-SMA-20 crossed above SMA-50 (bullish signal) around [2023-07,2024-07,2025-07,2026-01], 
which lined up with a price increase.

-Volatility (20-day rolling) was highest around 2024-07, possibly due to earnings, market news, etc. 

-Comparing cumulative returns, RELIANCE.NS underperformed the Nifty 50 over this period."

"It's unclear whether the July 2024 volatility spike was stock-specific or market-wide —
would need to check Nifty 50's volatility over the same window to confirm."

## Tools used
Python, pandas, numpy, matplotlib, yfinance
