# Week 4 – Shopify Stock Visualization, Time-Series Analysis & Financial Insights

##  Project Overview

This project focuses on visualizing and analyzing **Shopify stock data** using Python. The analysis includes OHLC price trends, trading volume, moving averages, daily returns, and rolling volatility.

The main goal is to understand stock price movements, return patterns, and periods of higher volatility.

##  Objectives

* Visualize Open, High, Low, and Close (OHLC) prices over time.
* Analyze trading volume trends.
* Calculate and visualize 20-day and 50-day moving averages.
* Compare moving averages with daily closing prices.
* Generate histogram and KDE plots for daily returns.
* Analyze rolling volatility to identify high-volatility periods.
* Provide financial insights based on the analysis.

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

##  Dataset

**Dataset:** Shopify Stock Data

The dataset contains stock market attributes such as:

* Date
* Open
* High
* Low
* Close
* Volume

##  OHLC Price Analysis

Line plots were created for:

* Opening Price
* Highest Price
* Lowest Price
* Closing Price

These plots help visualize Shopify's stock price movement over time.

##  Trading Volume Analysis

A line plot was created to analyze trading volume over time.

Trading volume represents the number of shares traded during a particular period.

##  Moving Average Analysis

Two moving averages were calculated:

* **20-Day Moving Average (MA20)** – used to observe short-term price trends.
* **50-Day Moving Average (MA50)** – used to observe longer-term price trends.

The moving averages were plotted together with the daily closing price to compare short-term and long-term trends.

### Formula

`MA20 = 20-day rolling mean of Closing Price`

`MA50 = 50-day rolling mean of Closing Price`

##  Daily Return Analysis

Daily returns were calculated using:

`Daily Return = Percentage Change in Closing Price`

A histogram with KDE was generated to visualize the distribution of daily returns.

This helps examine whether the returns are approximately normally distributed or show characteristics such as heavier tails.

##  Rolling Volatility Analysis

A **20-day rolling standard deviation** of daily returns was calculated to measure changes in volatility over time.

Higher rolling volatility indicates periods with larger fluctuations in daily returns.

##  Financial Insights

The analysis provides insights into:

* Overall stock price movement
* Trading volume trends
* Short-term and long-term moving averages
* Daily return distribution
* Periods of relatively high and low volatility
* Stock stability over different time periods

##  Key Visualizations

The project includes:

1. Shopify OHLC Price Line Plot
2. Shopify Trading Volume Line Plot
3. Daily Closing Price Plot
4. 20-Day Moving Average Plot
5. 50-Day Moving Average Plot
6. Closing Price with 20-Day and 50-Day Moving Averages
7. Daily Return Histogram with KDE
8. 20-Day Rolling Volatility Plot

##  Conclusion

The Shopify stock dataset was visualized and analyzed using Python. OHLC prices, trading volume, moving averages, daily returns, and rolling volatility were examined to understand stock price behavior and identify periods of increased price variation.

##  Tools

**Python | Pandas | NumPy | Matplotlib | Seaborn | Google Colab**
