**Quantitative Trading Strategies: Statistical Arbitrage & Momentum Models**

This project showcases two algorithmic trading strategies: Statistical Arbitrage and Momentum, developed in Python using publicly available financial data. It is designed to demonstrate practical skills in quantitative modeling, backtesting, and performance evaluation.

  
quant-strategies/  
├── data/               # Raw and processed data   
├── notebooks/          # EDA and strategy development notebooks  
├── strategies/         # Trading strategy logic  
├── backtests/          # Backtesting engine and results  
├── reports/            # Visuals, metrics, and performance summaries  
├── utils/              # Helper functions  
├── requirements.txt    # Python dependencies  
├── README.md      # Project overview  


📉 **Strategy Summaries**

**1. Statistical Arbitrage**

-**Type:** Mean-reversion / Pairs Trading

-**Signal:** Z-score of price spread between cointegrated assets

-**Execution:** Long/short the spread, revert to mean

-**Enhancements:** Dynamic hedge ratios, Kalman filter smoothing

**2. Momentum**

-**Type:** Trend-following (cross-sectional or time-series)

-**Signal:** Rolling returns, RSI, MACD

-**Execution:** Long top X% and short bottom X% ranked by momentum

-**ML Option:** Use a classifier to predict next-period returns or rank stocks

📊 **Performance Metrics**

Sharpe Ratio

Sortino Ratio

CAGR (Compounded Annual Growth Rate)

Max Drawdown

Hit Rate / Win-Loss Ratio

Turnover & Transaction Costs
