# Week 2 – AAPL Stock Data Understanding, Cleaning & Exploratory Analysis

##  Project Overview

This project focuses on understanding, cleaning, and performing exploratory analysis on **Apple (AAPL) stock data** using Python and Pandas.

The dataset contains stock price information such as Open, High, Low, Close, Adjusted Close, and Trading Volume.

##  Objectives

* Load and inspect the AAPL stock dataset.
* Check data types and dataset structure.
* Display the first and last five records.
* Check and clean missing values and duplicate records.
* Standardize the Date column.
* Calculate average opening and closing prices.
* Identify the highest High and lowest Low prices.
* Calculate daily price change.
* Calculate daily percentage returns.
* Identify days with the highest and lowest returns.

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Google Colab

##  Dataset

**Dataset:** AAPL Stock Data

The dataset contains the following attributes:

* Date
* Open
* High
* Low
* Close
* Adj Close
* Volume

##  Data Cleaning

The following data cleaning steps were performed:

1. Loaded the dataset using Pandas.
2. Checked the dataset structure and data types.
3. Displayed the first and last five records.
4. Checked for missing values.
5. Checked for duplicate records.
6. Converted the Date column into proper datetime format.

##  Stock Price Analysis

### Average Opening Price

The average opening price of the stock was calculated using the Open column.

### Average Closing Price

The average closing price was calculated using the Close column.

### Highest High Price

The record with the highest stock price in the High column was identified.

### Lowest Low Price

The record with the lowest stock price in the Low column was identified.

##  Daily Price Delta

Daily price change was calculated using:

`Daily Price Delta = Close - Open`

The top 10 days with the highest price change were identified.

##  Daily Percentage Return

Daily percentage return was calculated using:

`Daily Return = ((Close - Open) / Open) × 100`

The days with the highest and lowest percentage returns were identified.

##  Key Analysis

The analysis helps understand:

* Stock opening and closing price behavior
* Highest and lowest price levels
* Daily price changes
* Positive and negative daily returns
* High-return and low-return trading periods
* Trading volume patterns

##  Conclusion

The AAPL stock dataset was successfully loaded, cleaned, and analyzed using Python. Missing values and duplicate records were checked, the Date column was standardized, and important stock price metrics such as daily price delta and percentage returns were calculated.

## Tools

**Python | Pandas | NumPy | Matplotlib | Google Colab**
