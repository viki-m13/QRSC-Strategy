# QRSC-Strategy
Quadratic Relative Strength &amp; Convexity (QRSC) Strategy is a cross-sectional momentum strategy that fits a quadratic curve to each asset’s log price relative to a benchmark (SPY or BTC-USD) over a rolling lookback window. It scores assets by slope + λ·convexity, converts scores to softmax portfolio weights, rebalances daily, and supports flexible universes (sectors, ETFs, stocks, crypto, or all) with an optional “underperformers only vs benchmark” filter.

In simple terms: it looks at how strongly each asset has been trending versus SPY/BTC, picks today’s strongest trends across your chosen universe, and continuously reallocates into those leaders.

QRSC stats: {'start': '2018-09-18', 'end': '2025-11-14', 'CAGR': np.float64(0.1888477833881117), 'ann_vol': 0.20649106188797023, 'Sharpe': np.float64(0.9145566963599097), 'max_dd': -0.20580844397666953, 'total_ret': np.float64(2.442819137888288), 'n_days': 1801}
SPY stats: {'start': '2018-09-18', 'end': '2025-11-14', 'CAGR': np.float64(0.1431315730986047), 'ann_vol': 0.20006941752672375, 'Sharpe': np.float64(0.7154095556832731), 'max_dd': -0.3371725510474566, 'total_ret': np.float64(1.601378466517433), 'n_days': 1801}

<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/75f2699a-a370-42ba-9db1-6b9e3e9c088c" />
