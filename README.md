# Using stock prices of Asia's major indexes to develop a trading strategy for the S&P500 
## Due to the timezone difference, Asian Markets open and close before the US markets are open. What we are trying to do is to discover the relationship between the different indexes using machine learning so as to develop a profitable trading strategy thatis implemented on VOO
#### Data from Asia's major stock indexes:
- Singapore(Strait Times Index)
- Hong Kong(Hang Seng Index
- ShangHai (SSE Composite Index)
- Japan (Nikkei 225) 
- USA's stock market (S&P 500)

#### Interpreting the data
- Open
- Adjusted close
- High
- Low
- Adjusted close day difference
#### Creating a model
- X Input data: STI, Hang Seng Index, SSE Composite Index, Nikkei
- Y data: S&P 500 (opening price 1day time frame) (open and close)
- Using Machine Learning techniques (LSTM, ARIMA/VAR, regression) 

#### Trading strategy (1 day time frame)
- For example our model predicts 3% increase
- 3% we close 
- 2% stop loss (research)
-  Close position at the end of the day

#### We may need to research more and incorporate technical indicators
- Simple moving averages (50day SMA, 30days SMA)
- MACD for momentum
- Exponential Moving Average
