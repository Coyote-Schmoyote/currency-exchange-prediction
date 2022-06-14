# Currency exchange prediction model
This notebook looks into Python-based machine learning and data science libraries in an attempt to analyze time series data and build a machine learning model that can predict the exchange rate of JPY to USD, and USD to EUR for a given day.

## 1. Problem Definition
* Problem 1
Fill in the missing NaN values with the data from the most recent previous day.

* Problem 2
With the above data, visualize each statistic and the time series.

* Problem 3
Display a histogram of the rate exchange, taking the difference between each day and the previous day (day - previous day).

* Problem 4
Build a linear regression model to predict future prices (e.g., next day), using November 2016 as training data. Use the price of the day as the target variable, and build a model that predicts the price of the day based on the prices from the previous days. Use December 2016 as test data.

## 2. Data
For this project, we are going to generate data using pandas module pandas_datareader.data to extract data from Federal Reserve Economic Data (FRED). We will take the exchange rate data for Japanese Yen to US Dollars, and US Dollars to Euro, starting January 2nd 2001, and ending December 30th 2016.
