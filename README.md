# Quant-Task

Problem Statement

Predict the future volatility (variability in price movement) of a stock or index over a defined 
time window (e.g., next 5 days), using historical price data and engineered features. 

Approach

1]Data Source:yfinance
Ticker:BSE.NS
Date Range:2020-01-01 to 2025-07-06

2]Features (Technical Indicators)
Simple Moving Average (SMA 10)
Exponential Moving Average (EMA 10)
Relative Strength Index (RSI)
MACD (12 EMA – 26 EMA)
Bollinger Band Width

3]Target Variable
5-day Future Volatility

4]Exploratory Data Analysis
A correlation heatmap was plotted to analyze relationships between technical indicators and the target variable.
Some indicators like RSI and MACD showed strong relevance to volatility prediction.

Model
Algorithm Used: Random Forest Regressor  
Train-Test Split: 80-20 (without shuffling, to preserve time sequence)

Result

Predicted 5-day future volatility for BSE: 0.0270

Author
Soham Patil


