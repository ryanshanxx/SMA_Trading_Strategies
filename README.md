# SMA_Trading_Strategies

1. Process the historical price history in attached ‘adj_close_hist.csv’ and fill missing values with     its previous closing price.

2. Implement the following technical trading strategies and initiate a stock position from long side.
  a. Short term:
      i. Buy when stock closes above its 5-day SMA (simple moving average)
      ii. Sell when stock closes below its 5-day SMA
  b. Medium term:
      i. Buy when 15-day SMA moves above 50-day SMA
      ii. Sell when 15-day SMA moves below 50-day SMA
  c. Long term trend following:
      i. Buy when 50-day SMA moves above its 200-day SMA
      ii. Sell when 50-day SMA moves below its 200-day SMA
      
3. Compare the following performance statistics for the above trading strategies:
  a. Average position turn-over per annum
  b. Average position holding period
  c. Average annualized return
  d. Average annualized return volatility
