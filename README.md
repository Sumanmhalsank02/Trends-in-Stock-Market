# Trends-in-Stock-Market
To get a basic idea about Trends in stock market, I would recommend the following link [Trends](https://www.investopedia.com/terms/t/trend.asp)

![GitHub top language](https://img.shields.io/github/languages/top/Sumanmhalsank02/Trends-in-Stock-Market?color=orange)
![GitHub repo size](https://img.shields.io/github/repo-size/Sumanmhalsank02/Trends-in-Stock-Market?style=plastic)
![GitHub](https://img.shields.io/github/license/Sumanmhalsank02/Trends-in-Stock-Market?style=plastic)


## Description
---

In this repository you will find a simple code that creates a column 'Trends' in the Stock Prices of the company TCS based on multiple conditions on the Daily Percentage Change. 

**Daily Percentage Change:** The percentage change between two consecutive day's Closing price.

Instead of using the Mathematical formula to compute the same I have used a function [pct_change()](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.pct_change.html) provided by Pandas for dataframes 
Pandas is used to process and analyse the data. To analyse the data, here, I found out the Trend of a stock price


## Extra functions in the code
---

1. The Maximum, Minimum and Mean price for the last 90 days (Price : Close Price)
2. Conversion of Dates to datetime64(ns)
3. Calculation of the monthwise VWAP (Volume Weighted Average Price) of the stock
4. Use of groupby() function
5. Calculation of Average and Profit/Loss over the last N days
6. Average and Median of the Total Traded Quantity
7. Plot of the Close Price
8. Stem Plot of the Daily_Percentage_Change and Number_of_Trades(Daily Volumes)
9. Histogram for the Daily_Percentage_Change distribution
10. Pie Chart for the Trends of the Stock price

PS: I have kept these Extras in the code for my personal reference


## How to use the Code
---

 1. Download the Zip File
 2. Copy the TCS.csv dataset to a preferred location
 3. Copy the path and paste it in the Trends python code
 4. Run the Trends python file 


## License
---

This repository is licensed under [MIT License](https://github.com/Sumanmhalsank02/Trends-in-Stock-Market/blob/main/LICENSE)





