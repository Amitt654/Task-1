# Task-1
 Data Cleaning &amp; Preprocessing

# Titanic Dataset Preprocessing

## Overview

This project performs data preprocessing on the **Titanic-Dataset 4.csv** dataset to prepare it for machine learning. The preprocessing includes cleaning missing values, encoding categorical features, scaling numerical data, and removing outliers.

## Dataset

* **Dataset Name:** Titanic-Dataset 4.csv
* **Rows:** 891
* **Columns:** 12

## Preprocessing Steps

1. Imported the dataset using Pandas.
2. Explored the dataset by checking data types and missing values.
3. Filled missing values:

   * `Age` → Median
   * `Embarked` → Mode
   * Dropped `Cabin` due to excessive missing values.
4. Converted categorical columns (`Sex` and `Embarked`) into numerical values using Label Encoding.
5. Standardized numerical features using `StandardScaler`.
6. Visualized outliers with boxplots.
7. Removed outliers using the Interquartile Range (IQR) method.
8. Saved the cleaned dataset for machine learning.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

## Files

* `Titanic-Dataset 4.csv` – Original dataset
* `Titanic_preprocessing.py` – Data preprocessing code
* `README.md` – Project documentation

## Result

The Titanic dataset was successfully cleaned, transformed, standardized, and prepared for machine learning model development.
