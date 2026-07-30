# Cafe Sales Data Cleaning & Preprocessing

## Project Overview

This project was completed as part of the Oasis Infobyte Data Analytics Internship (Level 1 – Task 3). The objective was to clean and preprocess a raw cafe sales dataset so that it could be used for further analysis.

## Objectives

- Handle missing values
- Remove duplicate records
- Correct incorrect data types
- Standardize categorical values
- Detect and handle outliers
- Generate a before vs. after cleaning summary
- Export the cleaned dataset

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

- **Input:** `dirty_cafe_sales.csv`
- **Output:** `cleaned_cafe_sales.csv`

## Data Cleaning Process

The following preprocessing steps were performed:

- Checked for missing values and handled them appropriately.
- Removed duplicate records.
- Corrected column data types.
- Standardized inconsistent text values.
- Identified potential outliers using the IQR method.
- Compared dataset statistics before and after cleaning.
- Exported the cleaned dataset to a new CSV file.

## Repository Contents

```
DataAnalytics-L1-Task3-CafeSalesPreprocessing/
│
├── cafe_sales.ipynb
├── dirty_cafe_sales.csv
├── cleaned_cafe_sales.csv
└── README.md
```

## Result

The dataset was successfully cleaned and transformed into an analysis-ready format. The notebook documents each preprocessing step and saves the final cleaned dataset for future analysis.
