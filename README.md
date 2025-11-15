# QRSC-Strategy
Quadratic Relative Strength &amp; Convexity (QRSC) Strategy is a cross-sectional momentum strategy that fits a quadratic curve to each asset’s log price relative to a benchmark (SPY or BTC-USD) over a rolling lookback window. It scores assets by slope + λ·convexity, converts scores to softmax portfolio weights, rebalances daily, and supports flexible universes (sectors, ETFs, stocks, crypto, or all) with an optional “underperformers only vs benchmark” filter.

In simple terms: it looks at how strongly each asset has been trending versus SPY/BTC, picks today’s strongest trends across your chosen universe, and continuously reallocates into those leaders.

**Backtest (2018-09-18 to 2025-11-14, ETFS mode vs SPY)**

QRSC: CAGR 18.9%, vol 20.6%, Sharpe 0.91, max DD −20.6%, total return +244%

SPY : CAGR 14.3%, vol 20.0%, Sharpe 0.72, max DD −33.7%, total return +160%

<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/75f2699a-a370-42ba-9db1-6b9e3e9c088c" />
