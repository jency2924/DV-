# Week 3 - Shopify Stock Data Understanding, Cleaning & Exploratory Analysis

## Project Overview

This project focuses on understanding, cleaning, and analyzing stock market data using Python. The analysis works with stock price attributes such as Open, High, Low, Close, and Volume.

The project calculates daily price changes, daily percentage returns, trading volume anomalies, and statistical measures of stock returns.

## Objectives

* Load and clean stock price attributes.
* Calculate daily price delta using Close and Open prices.
* Calculate daily percentage returns.
* Analyze trading volume and identify anomalous trading days.
* Calculate the mean, variance, and standard deviation of stock returns.

## Technologies Used

* Python
* Pandas
* Google Colab

## Dataset

The project uses an Excel stock dataset containing the following important attributes:

* Date
* Open
* High
* Low
* Close
* Volume

## Data Loading

The dataset is loaded from an Excel file using Pandas.

```python
df = pd.read_excel("/content/drive/MyDrive/AAPL.xlsx")
```

## Data Cleaning

The following cleaning steps were performed:

* Removed extra spaces from column names.
* Converted Open, High, Low, Close, and Volume columns into numeric data types.
* Invalid numeric values were converted to missing values.
* Rows containing missing values in the required price attributes were removed.

## Daily Price Delta

Daily price delta was calculated using the difference between the closing price and opening price.

```text
Price Delta = Close - Open
```

This shows the daily change between the opening and closing prices.

## Daily Percentage Return

Daily percentage return was calculated using the daily price delta and opening price.

```text
Daily Return = (Close - Open) / Open × 100
```

This helps measure the percentage change in the stock price during a trading day.

## Trading Volume Analysis

Trading volume was analyzed using a 5-day moving average.

A volume anomaly was identified when the trading volume was more than two standard deviations away from the average trading volume.

```text
Volume Anomaly = |Volume - Mean Volume| > 2 × Standard Deviation
```

The dates and trading volumes of anomalous trading days were displayed.

## Stock Return Statistics

The distribution of daily stock returns was summarized using:

### Mean

The mean represents the average daily return.

### Variance

Variance measures the spread of daily returns around the mean.

### Standard Deviation

Standard deviation measures the variability of daily returns.

The calculated values are displayed using Python.

## Output

The program displays:

* Mean Return
* Variance of Return
* Standard Deviation of Return
* Anomalous Trading Days
* Cleaned Dataset Preview

## Conclusion

This project demonstrates how Python and Pandas can be used to clean and analyze stock market data. Daily price changes and returns were calculated, trading volume anomalies were identified, and stock return statistics were summarized using mean, variance, and standard deviation.
