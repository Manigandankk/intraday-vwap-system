# intraday-vwap-system
The project is designed for Intraday VWAP Mean Reversion Strategy with Walk-Forward Optimization and Live Signal Engine

Can intraday VWAP mean reversion generate alpha in BTCUSDT 5m data?

**Methodology**
   
Session VWAP
ZScore deviation
Trend filter
Volatility filter
Time filter
Walk-forward optimization

**Technologies**
Python
VectorBT
Pandas
NumPy
CCXT
Binance API

**Results**

Include metrics:

Sharpe
Drawdown
Return
Profit factor

real-time signal engine running on completed 5m candles, prints when the signal is generated. No real execution
