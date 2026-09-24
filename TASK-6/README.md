# Week 6 - Healthcare Data Analysis

## Project Overview

This project focuses on understanding and analyzing healthcare data using Python. The dataset contains patient information, medical conditions, admission details, billing amounts, insurance providers, medications, and test results.

The analysis helps identify patterns in patient demographics, medical conditions, hospital admissions, billing amounts, and healthcare-related attributes.

## Objectives

* Understand the structure of the healthcare dataset.
* Clean and prepare the data for analysis.
* Analyze patient demographics.
* Study different medical conditions.
* Analyze admission types.
* Examine billing amounts.
* Analyze insurance providers and medications.
* Study test results and healthcare patterns.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

## Dataset

The dataset contains **55,500 records and 15 attributes**.

### Main Attributes

* Name
* Age
* Gender
* Blood Type
* Medical Condition
* Date of Admission
* Doctor
* Hospital
* Insurance Provider
* Billing Amount
* Room Number
* Admission Type
* Discharge Date
* Medication
* Test Results

## Data Understanding

The dataset was loaded using Pandas and basic functions such as `head()`, `info()`, `describe()`, and `isnull().sum()` were used to understand the data structure, data types, statistical information, and missing values.

## Data Cleaning

The following preprocessing steps were performed:

* Checked for missing values.
* Checked the data types of columns.
* Standardized date attributes.
* Converted admission and discharge dates into datetime format.
* Cleaned categorical values where required.
* Checked numerical attributes such as Age and Billing Amount.

## Patient Demographic Analysis

Patient demographics were analyzed using attributes such as:

* Age
* Gender
* Blood Type
* Medical Condition

This helps understand the distribution of patients across different demographic groups.

## Medical Condition Analysis

The dataset contains different medical conditions. Patient records were grouped according to medical condition to identify the distribution of healthcare cases.

## Admission Analysis

Admission types were analyzed to understand how patients were admitted to hospitals.

The main admission categories include:

* Emergency
* Elective
* Urgent

## Billing Amount Analysis

The `Billing Amount` attribute was analyzed using statistical measures such as:

* Mean
* Minimum
* Maximum
* Standard deviation
* Quartiles

This provides an understanding of the variation in patient healthcare expenses.

## Insurance Provider Analysis

Insurance providers were analyzed to understand the number of patients associated with different insurance companies and their healthcare billing patterns.

## Medication Analysis

Medication records were analyzed to identify the distribution of commonly used medications among patients.

## Test Result Analysis

Test results were examined to understand the distribution of patient outcomes in the dataset.

## Key Analysis

The analysis provides insights into:

* Patient demographic distribution.
* Distribution of medical conditions.
* Different types of hospital admissions.
* Variation in healthcare billing amounts.
* Insurance provider distribution.
* Medication usage patterns.
* Test result distribution.

## Conclusion

This healthcare data analysis project demonstrates how Python can be used to clean, understand, and analyze a large healthcare dataset. The analysis provides useful insights into patient demographics, medical conditions, admissions, billing, insurance providers, medications, and test results.

## Tools

Python, Pandas, NumPy, Matplotlib, Seaborn, Google Colab
