# WEEK 11 – AUTOMOBILE DATASET ANALYSIS USING PYTHON
## Data Cleaning and Preprocessing

### 1. Introduction
This project focuses on cleaning and preprocessing an automobile dataset using Python. The main objective is to prepare the raw dataset for further analysis by handling missing values, converting data types, creating new features, and performing data validation.

### 2. Objectives
- Load and understand the automobile dataset.
- Identify and handle missing values.
- Perform category-wise median imputation.
- Convert columns into appropriate data types.
- Create new analytical features.
- Perform group-wise analysis.
- Export the cleaned dataset.

### 3. Tools and Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

### 4. Dataset Overview
The automobile dataset contains 205 records and 26 original columns. It includes manufacturer details, fuel type, body style, engine specifications, vehicle dimensions, mileage, horsepower, and price.

### 5. Task-wise Implementation

#### Task 1: Import Libraries and Load Dataset
Imported Pandas, NumPy, Matplotlib, and Seaborn. Loaded the automobile CSV dataset and displayed the first five records, last five records, dataset dimensions, and column names.

#### Task 2: Understand Dataset Structure
Used `df.info()` and `df.describe()` to understand the dataset structure and statistical information. Identified categorical and numerical columns.

#### Task 3: Handle Missing Values
Replaced question mark (`?`) symbols with `NaN` values. Calculated the number and percentage of missing values in each column.

#### Task 4: Category-wise Median Imputation
Handled missing values in horsepower, peak-rpm, bore, stroke, and price columns using manufacturer-wise median values. Used the overall median as a fallback for remaining missing values.

#### Task 5: Convert Data Types
Converted horsepower into integer format and peak-rpm, price, bore, and stroke into floating-point format.

#### Task 6: Create Power-to-Weight Ratio
Created a new feature called `power_to_weight_ratio` using horsepower and curb-weight.

Formula:

Power-to-Weight Ratio = (Horsepower / Curb Weight) × 1000

#### Task 7: Create Combined MPG
Created a new feature called `combined_mpg` by calculating the average of city mileage and highway mileage.

Formula:

Combined MPG = (City MPG + Highway MPG) / 2

#### Task 8: Group by Body Style
Grouped the dataset based on body-style and calculated average horsepower, engine-size, curb-weight, price, and combined_mpg.

#### Task 9: Group by Engine Location
Grouped the dataset based on engine-location and calculated average horsepower, engine-size, curb-weight, price, and combined_mpg.

#### Task 10: Final Validation and Export
Checked missing values, data types, duplicate records, and newly created features. Exported the processed dataset as `automobile_cleaned.csv`.

### 6. Results
- Loaded and explored the automobile dataset.
- Replaced missing-value symbols and performed median imputation.
- Converted selected columns into appropriate data types.
- Created two new analytical features.
- Performed body-style and engine-location analysis.
- Exported the cleaned dataset for further analysis.

### 7. Output File
`automobile_cleaned.csv`

### 8. Conclusion
Week 11 successfully covered the data cleaning and preprocessing stages of automobile dataset analysis. Missing values were handled, data types were converted, and new features were created. The cleaned dataset was exported and prepared for visualization and further analysis in Week 12.
