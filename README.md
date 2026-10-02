# Task 1 - Data Cleaning and Preprocessing

## Project Overview

This project demonstrates data cleaning and preprocessing using the Mall Customer Segmentation dataset. The dataset contains customer information such as gender, age, annual income, and spending score.

## Dataset

The dataset contains 200 customer records and 5 columns:

- Customer ID
- Gender
- Age
- Annual Income
- Spending Score

## Data Cleaning Steps

The following data cleaning and validation steps were performed:

1. Loaded the raw CSV dataset using Pandas.
2. Inspected the dataset structure and dimensions.
3. Checked for missing values.
4. Checked for duplicate records.
5. Checked unique values in the Gender column.
6. Checked numerical ranges for Age, Annual Income, and Spending Score.
7. Standardized column names into lowercase, underscore-separated names.
8. Verified the data types of all columns.
9. Performed a final data-quality validation.
10. Saved the cleaned dataset as a separate CSV file.

## Data Quality Results

- Total records: 200
- Total columns: 5
- Missing values: 0
- Duplicate rows: 0
- Age range: 18–70
- Annual income range: 15–137 k$
- Spending score range: 1–99
- Gender values: Male, Female

## Column Names After Cleaning

| Original Column | Cleaned Column |
|---|---|
| CustomerID | customer_id |
| Gender | gender |
| Age | age |
| Annual Income (k$) | annual_income |
| Spending Score (1-100) | spending_score |

## Tools Used

- Python
- Pandas
- Jupyter Notebook
- Visual Studio Code

## Files

- `dataset/Mall_Customers.csv` - Original raw dataset
- `dataset/cleaned_mall_customers.csv` - Cleaned dataset
- `data_cleaning.ipynb` - Data cleaning and preprocessing code