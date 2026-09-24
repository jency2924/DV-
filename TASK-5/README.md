# Week 5 – Healthcare Data Understanding, Cleaning & Exploratory Analysis

## Project Overview

This project focuses on understanding, cleaning, and analyzing a healthcare dataset using Python and Pandas.

The analysis includes cleaning missing medical codes, standardizing date attributes, calculating hospital stay duration, categorizing admissions by urgency, analyzing billing amounts, and segmenting patient demographics by medical condition.

## Objectives

* Clean missing values in medical codes.
* Standardize date attributes.
* Calculate hospital stay duration in days.
* Categorize admissions into Emergency, Elective, and Urgent.
* Calculate summary statistics for patient billing amounts.
* Calculate summary statistics for hospital stays.
* Segment demographics based on medical condition.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

## Dataset

**Dataset:** Healthcare Dataset

The dataset contains healthcare-related information such as:

* Patient details
* Age
* Medical Condition
* Medical Code
* Date of Admission
* Discharge Date
* Admission Type
* Billing Amount

## Data Cleaning

The following cleaning steps were performed:

1. Loaded the healthcare dataset using Pandas.
2. Inspected the dataset using `head()` and `info()`.
3. Checked for missing values.
4. Removed extra spaces from column names.
5. Removed unnecessary spaces from text values.
6. Replaced missing Medical Code values with `Unknown`.

## Date Standardization

The following date columns were converted into proper datetime format:

* Date of Admission
* Discharge Date

The date format was standardized using Pandas `to_datetime()`.

## Hospital Stay Calculation

Hospital stay duration was calculated using the admission and discharge dates.

### Formula

`Hospital Stay Days = Discharge Date - Date of Admission`

This helps determine how many days each patient stayed in the hospital.

## Admission Urgency Classification

Admissions were categorized based on the Admission Type:

* Emergency
* Elective
* Urgent

This provides an overview of different types of hospital admissions.

## Billing Amount Analysis

Summary statistics were calculated for the Billing Amount column.

The analysis includes:

* Count
* Mean
* Standard Deviation
* Minimum
* Maximum
* 25th Percentile
* 50th Percentile
* 75th Percentile

## Hospital Stay Analysis

Summary statistics were calculated for Hospital Stay Days to understand the duration of patient hospital stays.

## Demographic Segmentation

Patient demographics were segmented based on Medical Condition.

The analysis includes:

* Average Age
* Minimum Age
* Maximum Age
* Average Billing Amount
* Average Hospital Stay

This helps compare patient characteristics across different medical conditions.

## Key Analysis

The project helps understand:

* Missing medical code values
* Patient admission patterns
* Hospital stay duration
* Patient billing amounts
* Age distribution by medical condition
* Average billing and hospital stay for different medical conditions

## Conclusion

The healthcare dataset was successfully cleaned and analyzed using Python. Missing medical codes were handled, date attributes were standardized, hospital stay duration was calculated, admissions were categorized by urgency, and summary statistics were generated for billing amounts and hospital stays. Patient demographics were also segmented according to medical conditions.

## Tools

**Python | Pandas | NumPy | Matplotlib | Seaborn | Google Colab**
