# Data Cleaning – Employee Attrition Dataset

## Project Overview

This project focuses on importing and cleaning the Employee Attrition dataset using Python and Jupyter Notebook. The dataset was cleaned and prepared for further analysis.

## Dataset Information

* Total Records: 1470
* Total Columns: 35
* Missing Values After Cleaning: 0
* Duplicate Records After Cleaning: 0

## Data Cleaning Steps

### 1. Data Importing

The Employee Attrition dataset was imported into Jupyter Notebook using Pandas.

### 2. Missing Value Handling

Missing values were identified using Pandas. Missing numerical values were handled using the median value of the respective columns.

### 3. Duplicate Records

Duplicate records were checked and removed where necessary. The final dataset contains 0 duplicate records.

### 4. Inconsistent Entries

Categorical columns such as Attrition, BusinessTravel, Department, EducationField, Gender, JobRole, MaritalStatus and OverTime were checked for inconsistent entries.

### 5. Data Types

The data types of all columns were checked and corrected where required. Numerical columns were stored as integer values and categorical columns as string values.

### 6. Column Names

Column names were checked for proper naming and readability. No unnecessary column renaming was required.

### 7. Formatting

The dataset was checked for formatting issues and properly organized for further analysis.

### 8. Final Verification

The final cleaned dataset was verified.

* Final Shape: 1470 rows × 35 columns
* Missing Values: 0
* Duplicate Records: 0

## Output

The cleaned dataset is saved as:

`cleaned_employee_attrition.csv`

The cleaned dataset is ready for further data analysis and visualization.
