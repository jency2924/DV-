# Week 1 – Superstore Sales Data Understanding, Cleaning & Exploratory Analysis

##  Project Overview

This project focuses on understanding, cleaning, and performing basic exploratory data analysis on the **Superstore Sales Dataset** using Python and Pandas.

The dataset contains information about orders, customers, categories, sales, and shipping details.

##  Objectives

* Load the Superstore dataset using Pandas.
* Inspect the dataset using `.head()`, `.info()`, and `.describe()`.
* Convert Order Date and Ship Date into proper datetime format.
* Clean categorical text attributes such as Category, Sub-Category, and Segment.
* Calculate initial summary statistics for numerical attributes.
* Perform basic exploratory analysis using charts.

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

##  Dataset

**Dataset:** Superstore Sales Dataset

The dataset contains fields such as:

* Order Date
* Ship Date
* Category
* Sub-Category
* Segment
* Sales
* Quantity
* Profit
* Customer details

##  Data Preprocessing

The following preprocessing steps were performed:

1. Loaded the dataset using Pandas.
2. Inspected the dataset using `head()`, `info()`, and `describe()`.
3. Converted `Order Date` and `Ship Date` into datetime format.
4. Checked for missing values.
5. Cleaned categorical text formatting.
6. Calculated basic numerical statistics.

##  Exploratory Analysis

Basic exploratory analysis was performed to understand the dataset.

### Sales by Category

A bar chart was created to compare total sales across different product categories.

### Sales Distribution

A histogram was created to understand the distribution of sales values.

### Delivery Days

Delivery days were calculated using:

`Ship Date - Order Date`

##  Key Analysis

The analysis helps understand:

* Dataset structure
* Data types
* Numerical statistics
* Sales distribution
* Category-wise sales
* Order delivery duration

##  Conclusion

The Superstore dataset was successfully loaded, inspected, cleaned, and analyzed using Python. Date attributes were converted into the correct format, categorical attributes were cleaned, and basic exploratory analysis was performed to understand sales patterns and dataset characteristics.

## 👩‍💻 Tools

**Python | Pandas | NumPy | Matplotlib | Seaborn | Google Colab**
