# QRSC-Strategy
Quadratic Relative Strength &amp; Convexity (QRSC) Strategy is a cross-sectional momentum strategy that fits a quadratic curve to each asset’s log price relative to a benchmark (SPY or BTC-USD) over a rolling lookback window. It scores assets by slope + λ·convexity, converts scores to softmax portfolio weights, rebalances daily, and supports flexible universes (sectors, ETFs, stocks, crypto, or all) with an optional “underperformers only vs benchmark” filter.

In simple terms: it looks at how strongly each asset has been trending versus SPY/BTC, picks today’s strongest trends across your chosen universe, and continuously reallocates into those leaders.

<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/75f2699a-a370-42ba-9db1-6b9e3e9c088c" />
