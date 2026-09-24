# Week 7 - Student Performance Data Understanding, Cleaning & Feature Engineering

## Project Overview

This project focuses on understanding, cleaning, and performing feature engineering on student performance data. The analysis includes categorical data cleaning, statistical analysis of subject scores, creation of total marks and percentage features, and detection of extreme performance outliers.

## Objectives

* Clean categorical features such as Gender, Race/Ethnicity, Parental Level of Education, Lunch, and Test Preparation Course.
* Calculate mean, median, standard deviation, and quartiles for subject scores.
* Create Total Marks and Percentage features.
* Detect extreme performance outliers across subject areas.

## Technologies Used

* Python
* Pandas
* NumPy
* Google Colab

## Dataset

The dataset contains student performance information with categorical features and scores for:

* Math Score
* Reading Score
* Writing Score
* Gender
* Race/Ethnicity
* Parental Level of Education
* Lunch
* Test Preparation Course

## Data Cleaning

The categorical features are cleaned by removing unwanted spaces using the `strip()` function.

The cleaned categorical features are:

* Gender
* Race/Ethnicity
* Parental Level of Education
* Lunch
* Test Preparation Course

## Statistical Analysis

Statistical measures are calculated for:

* Math Score
* Reading Score
* Writing Score

The following measures are calculated:

* Mean
* Median
* Standard Deviation
* Q1 (25th Percentile)
* Q2 (50th Percentile)
* Q3 (75th Percentile)

## Feature Engineering

### Total Marks

A new feature named `Total Marks` is created by adding the Math, Reading, and Writing scores.

### Percentage

A new feature named `Percentage` is calculated from the total marks out of 300.

## Outlier Detection

Extreme performance outliers are detected separately for:

* Math Score
* Reading Score
* Writing Score

The Interquartile Range (IQR) method is used.

The lower and upper limits are calculated using Q1, Q3, and IQR. Values outside these limits are identified as outliers.

## Output

The project produces:

* Cleaned categorical features
* Statistical measures for subject scores
* Total Marks
* Percentage Performance
* Number and sample records of extreme outliers for each subject

## Conclusion

This project cleans the categorical features, summarizes student subject performance using standard statistical measures, creates useful calculated features such as Total Marks and Percentage, and identifies extreme performance values using the IQR method.
