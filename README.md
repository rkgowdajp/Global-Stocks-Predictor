# Global-Stocks-Predictor
Predict buy, hold, sell for S&amp;P 500, Nikkei 225, FTSE 100, Nifty 50, BSE Index stocks
This is a test version, don't use it for your actual trading!!

Usage:
Source: yahoo finance tickers
Nikkei Index: Ticker 7203.T for Toyota
S&P 500 Index: Ticker AAPL for Apple
FTSE 100 Index: Ticker HSBA.L for HSBC bank
BSE Index: Ticker INFY.BO for Infosys
Nifty Index: INFY.NS for Infosys

Result:
If the stock goes up more than 2% in next 7 days, Its a BUY ( BUY->1)
If the stock goes down more than 2% in next 7 days, Its a SELL ( SELL->-1)
It's a HOLD if it does not move 2% in next 7 days ( HOLD->0)
accuracy is % of chance,  0.5 is 50%, Better the accuracy, better the outcome
