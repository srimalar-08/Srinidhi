# Telco Customer Churn Prediction - Data Cleaning and Exploratory Data Analysis

## Project Overview
This project performs data cleaning, preprocessing, exploratory data analysis (EDA), and visualization on the Telco Customer Churn dataset. The objective is to understand customer behavior and prepare the dataset for machine learning.

---

## Dataset
Dataset: WA_Fn-UseC_-Telco-Customer-Churn.csv

The dataset contains customer information such as:
- Gender
- Senior Citizen
- Tenure
- Internet Service
- Monthly Charges
- Total Charges
- Contract Type
- Churn Status

---

## Steps Performed

### Task 1: Data Loading
- Imported dataset into Google Colab.
- Verified dataset dimensions and column names.

### Task 2: Data Cleaning
- Checked missing values.
- Removed duplicate records.
- Converted appropriate data types.
- Fixed TotalCharges datatype.

### Task 3: Exploratory Data Analysis
Performed:
- Descriptive Statistics
- Skewness Analysis
- Outlier Detection using IQR
- Correlation Analysis
- Distribution Plots
- Count Plots
- Boxplots
- Histograms

---

## Findings

- No duplicate rows were found.
- Most columns had no missing values.
- SeniorCitizen showed the highest skewness.
- MonthlyCharges and Tenure contained no significant outliers.
- Data was successfully cleaned and prepared for machine learning.

---

## Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## How to Run

1. Download the dataset.
2. Open the notebook in Google Colab.
3. Upload the dataset.
4. Run all cells sequentially.

---

## Repository Contents

- Telco_Customer_Churn.ipynb
- WA_Fn-UseC_-Telco-Customer-Churn.csv
- README.md

---

## Author

Srinidhi B
