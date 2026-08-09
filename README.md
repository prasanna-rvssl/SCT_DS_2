# Task 02 – Titanic Data Cleaning and Exploratory Data Analysis

## Overview

This project performs data cleaning and exploratory data analysis (EDA) on the Titanic dataset. The analysis focuses on identifying relationships, patterns, and trends among passenger characteristics and survival.

## Dataset

The project uses the Titanic `train.csv` dataset.

## Objectives

- Inspect and understand the dataset
- Identify and handle missing values
- Check for duplicate records
- Explore passenger survival patterns
- Analyze relationships between survival and passenger characteristics
- Use correlation analysis to identify relationships among numerical variables

## Data Cleaning

The following cleaning steps were performed:

- Missing `Age` values were replaced with the median age.
- Missing `Embarked` values were replaced with the most frequent value.
- The `Cabin` column was removed because it contained a large number of missing values.
- Duplicate records were checked.

After cleaning, there were no remaining missing values and no duplicate rows.

## Exploratory Data Analysis

The following analyses were performed:

- Survival distribution
- Survival by gender
- Survival by passenger class
- Age distribution
- Age distribution by survival
- Fare distribution by survival
- Correlation heatmap

## Key Findings

- The number of passengers who did not survive was higher than the number who survived.
- Female passengers had a considerably higher survival rate than male passengers.
- First-class passengers generally had better survival outcomes than second- and third-class passengers.
- Most passengers were young adults, with a large concentration between approximately 20 and 30 years of age.
- Age showed a weaker relationship with survival compared with gender and passenger class.
- Survivors generally paid higher fares than non-survivors.
- Passenger class had a moderate relationship with survival, while fare showed a mild positive relationship with survival.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project File

`Task_02_Titanic_EDA.ipynb`
