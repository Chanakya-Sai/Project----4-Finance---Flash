Task Documentation: EUR/INR Technical Analysis

Objective

The objective of this task is to analyse the trend of EUR/INR for the upcoming day and week using technical indicators. The analysis includes the calculation of Moving Averages, Bollinger Bands, and the Commodity Channel Index (CCI). Trading decisions are made based on the signals generated by these indicators.
Step 1: Data Retrieval
1.1. Data Source: Currency data for EUR/INR was retrieved from Yahoo Finance.
1.2. Period Covered: The data spans from January 1, 2023, to December 7, 2023.

Step 2: Technical Analysis

Calculating Moving Averages

2.1.1. 1-day Moving Average (1_day_MA): Calculated as the rolling mean of the closing prices with a window size of 1 day.
2.1.2. 1-week Moving Average (1_week_MA): Calculated as the rolling mean of the closing prices with a window size of 5 days.

Bollinger Bands

2.2.1. Standard Deviation (std): Calculated as the rolling standard deviation of the closing prices with a window size of 20 days.
2.2.2. Upper Bollinger Band (upper_band): Calculated as the sum of 2 times the standard deviation and the 1-week Moving Average.
2.2.3. Lower Bollinger Band (lower_band): Calculated as the difference between the 1-week Moving Average and 2 times the standard deviation.

Commodity Channel Index (CCI)

2.3.1. Typical Price: Calculated as the average of the high, low, and closing prices.
2.3.2. Mean Deviation: Calculated as the absolute difference between the Typical Price and its 14-day simple moving average.
2.3.3. CCI: Computed using the formula involving the Typical Price, its 14-day simple moving average, and the Mean Deviation.



Step 3: Trading Decisions

Moving Averages

3.1. 1-day Moving Average Signal (1_day_MA_Signal):
•	'BUY' when both the closing price and the 1-day Moving Average are above the 1-week Moving Average.
•	'SELL' when both are below the 1-week Moving Average.
•	'NEUTRAL' otherwise.

Bollinger Bands

3.2. Bollinger Bands Signal (BB_Signal):
•	'SELL' when the closing price is above the Upper Bollinger Band.
•	'BUY' when it's below the Lower Bollinger Band.
•	'NEUTRAL' otherwise.

Conclusion

Based on the analysis and trading signals generated by the Moving Averages and Bollinger Bands, trading decisions can be made for the specified time frames. It is recommended to review the visualizations and signals regularly for dynamic market conditions.
