# Internship Task 1 – Data Cleaning & Wrangling

## 📌 Overview
This project demonstrates how raw datasets can be transformed into clean, structured, and analysis‑ready formats using Python and Pandas. The dataset `sales_data.csv` was cleaned step by step to remove duplicates, fix datatypes, standardize values, and add derived insights.

## 🗂 Files in this Repo
- `task1_cleaning.py` → Python script with the full cleaning workflow
- `raw_sales_data.xlsx` → Raw dataset before cleaning
- `cleaned_sales_data.xlsx` → Final cleaned dataset
- `raw_data_dictionary.xlsx` → Data dictionary for raw dataset
- `cleaned_data_dictionary.xlsx` → Data dictionary for cleaned dataset

## 🧾 Task Description
Task 1 focuses on loading a raw dataset, identifying issues such as duplicates, missing values, inconsistent formats, and invalid records. Using Pandas, the dataset was cleaned, standardized, and enriched with an `Age` column. Outputs include raw vs cleaned datasets and their dictionaries exported to Excel.

## 🛠 Steps Performed
1. **Raw Data Familiarization**
   - Loaded dataset
   - Printed raw dataset
   - Generated raw data dictionary

2. **Data Cleaning**
   - Removed duplicates
   - Standardized Gender values
   - Converted Quantity & Price to numeric
   - Converted DOB & PurchaseDate to datetime
   - Removed negative prices
   - Added Age column

3. **Cleaned Data Dictionary**
   - Printed cleaned dataset
   - Generated cleaned data dictionary

4. **Export & Download**
   - Exported raw and cleaned datasets to Excel
   - Exported raw and cleaned data dictionaries to Excel

## 📊 Results
- Raw dataset: **21 rows**
- Cleaned dataset: **19 rows**
- Added `Age` column for analysis

## ✅ Conclusion
Task 1 successfully demonstrated how raw data can be transformed into a clean, structured, and reliable format using Python and Pandas. By removing duplicates, correcting datatypes, standardizing values, and adding derived insights such as the `Age` column, the dataset is now analysis‑ready. The exported raw vs cleaned datasets and their dictionaries clearly highlight the improvements, making the data suitable for academic, internship, and project use.
