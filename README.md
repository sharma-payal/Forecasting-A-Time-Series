# Forecasting-A-Time-Series
The project consists of three parts. Short Term Forecasting, Long Term forecasting and Regression. We will use a dataset that contains the historical stock prices for Apple Inc (AAPL) and Honeywell International Inc (HON) for a total time period of one year, consisting of 252 market days.
### Part 1: Short-term Forecasting
1. Use a simple line plot of both time series to detect seasonal, irregular, or trend behaviors if any. Write a summary of your
observations of both time series in your report.
2. Perform exponential smoothing to forecast both prices for period 253. Use successive values of 0.15, 0,35, 0.55, and 0.75 for the smoothing parameter α. Next, calculate the MAPE (Mean Absolute Percentage Error) of each forecast; and based on the MAPEs,
determine the value of α that has yielded the most accurate forecast for each stock. In your report, describe your results; and explain why in your opinion such values of α have yielded the most accurate
forecasts for the two stocks.
3. Use your exponential smoothing forecast of part second with α=0.55 and perform an adjusted exponential smoothing to forecast both prices for period 253. Use successive values of 0.15, 0.25, 0.45, and 0.85 for the trend parameters β for both stocks. Next, calculate the MAPEs (Mean Absolute Percentage Error) of your forecasts and determine the values of β that have provided the most accurate forecasts for both stocks. In your report, describe your results and explain why, in
your opinion, such values of β have yielded the most accurate forecasts.
### Part II: Long-term Forecasting
1. For each stock, use a 3-period weighted moving averages to forecast its value during periods 1 through 100. Use the weights 0.5 (for the most recent period), 0.3 (for the period before the most recent), and 0.2 (for two periods ago). Next, use the observed value for period 101 as the base of a linear trend, and use that linear trend to forecast the values of both stocks for periods 101 through 257. Write a summary of your results in your report. Describe how accurate this method of
forecasting has been by comparing the forecasted values for periods 253-257 with their actual “Close” values on those specific days (Hint:check the actual values on https://finance.yahoo.com).
2. Calculate the MAPEs (Mean Absolute Percentage Error) of your forecasts in question (i) above and compare them with the values
obtained for your forecasts in Part 1. For each stock, describe whichmethod has yielded a most accurate forecast.
### Part III: Regression
1. For each stock, use simple regression of stock values versus the time periods to predict its values for periods 1 through 257. In your report, describe how the accuracy of this prediction has been compared to the methods used in Parts 1 and 2 of this project.
2. Perform a residual analysis of your simple regression to verify whether regression is appropriate to use for each of the given data. In particular, determine:

● Whether the residuals are independent.

● Whether the residuals are homoscedastic.

● Whether the residuals are normally distributed by plotting a Normal probability plot of the residuals.

● Whether the residuals are normally distributed by performing a Chi-squared test for Normality of the residuals.

"After completing parts 1-3 and in your report, respond to the following question.
Note this question is subjective, and it does not necessarily have only one correct
answer at this stage of the course.
Question: Suppose that you have decided to form a portfolio (Pi) consisting ofΠ
the above two stock types (denote a share value of AAPL by and that of HON by𝑋
). You are however undecided as to what percentage of your investment should𝑌
be allocated to the AAPL shares and what percentage should be allocated to HON
shares. Let these percentages be denoted by P and Q respectively (Obviously, P +
Q=100%). In your opinion, what are good values to select for P and Q?"
