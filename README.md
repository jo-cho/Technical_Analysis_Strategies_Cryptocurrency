# Technical_Ananylsis_Cryptocurrnecy

Different trading strategies using technical analysis.
(기술적 분석을 이용한 다양한 트레이딩 전략)

- Strategies
  1. SMA (Simple Moving Average) Crossover strategy
  2. Envelope SMA strategy
  3. MACD (Moving average convergence divergence) strategy
  4. BB (Bollinger Bands) strategy
  5. RSI (Relative Strength Index) signal strategy
  6. Stochastic slow %K strategy
  7. Stochastic slow %K %D strategy
  8. Regime Double strategy*


- Data: Ethereum/USD 5 minutes bars, '2020-4-1' to '2021-4-10'

- Trading
  - Only long  position
  - Enter the long position when the long signal comes, exit the position when the short signal comes.
  - Ignore when long or short signal comes in a row.

- Backtest
  - Cumulative Returns plot
  - Ann Sharpe Ratio
  - Benchmark (daily trading returns)

- *Regime Double
  - Two regime: Trend-following, Mean-reverting
  - Decide the regime by rolling hurst exponents (weekly window)
  - Do SMA crossover & BB strategy on each regime.
