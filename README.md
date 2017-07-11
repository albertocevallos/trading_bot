# trading_bot
Simple trading bot for Poloniex cryptocurrency exchange. Bot places order to buy BTC/USD when the moving average (MACD) is negative and 1st derivative equals zero (local min). Bot places order to sell BTC/USD when the moving average (MACD) is positive and equal to zero (local max).

The Moving Average Convergence Divergence (MACD) is a trend-following momentum indicator that shows the relationship between two moving averages of prices. The MACD is calculated by subtracting the 26-day exponential moving average (EMA) from the 12-day EMA.

Although MACD allows accuracy for buying and placing orders, divergence movements (2nd derivative inflection points) are difficult to predict over time. "Crossovers" (time from local min to local max) range from 30 min to 24 hours. We hope to plot an average sentiment line using another twitter sentiment analysis script to predict how long each crossover period will last.

We can add the RSI Indicator (Relative Strength Index) to improve the bots behaviour during bear and bull markets
