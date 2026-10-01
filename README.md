# Data Cleaning and Preprocessing - Titanic Dataset

## Project Overview

This project focuses on data cleaning and preprocessing of the Titanic dataset using Python and Pandas.

The main objective of this project is to identify and fix common data quality problems such as missing values, duplicate records, inconsistent text formats, and data type issues.

## Dataset

The dataset contains information about Titanic passengers, including:

- Passenger ID
- Survival status
- Passenger class
- Name
- Sex
- Age
- Siblings/Spouses
- Parents/Children
- Ticket
- Fare
- Cabin
- Embarked

## Tools Used

- Python
- Pandas
- NumPy
- Google Colab
- GitHub

## Data Cleaning Steps

### 1. Missing Values

Missing values were checked using:

`df.isnull().sum()`

The following actions were performed:

- Missing Age values were filled using the median.
- Missing Embarked values were filled using the mode.
- Missing Cabin values were replaced with "Unknown".

### 2. Duplicate Records

Duplicate rows were checked using:

`
