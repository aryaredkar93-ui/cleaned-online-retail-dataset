# 🧼 Online Retail Dataset – Cleaned Version

This repository contains the cleaned version of the Online Retail dataset. The original data was preprocessed using Microsoft Excel to improve consistency, accuracy, and readiness for further analysis or visualization.

 Dataset Overview

Filename: Online_Retail_Cleaned.xlsx
Original Source: [UCI Machine Learning Repository – Online Retail](https://archive.ics.uci.edu/ml/datasets/online+retail)

The dataset contains transactional records for an online retail store, including invoices, product details, customer countries, and purchase dates.

 Data Cleaning Steps Performed :

The following preprocessing was done using Excel

Missing Values Handled :
Filtered and replaced or removed missing entries using Excel filters.
  
Duplicate Rows Removed:  
Exact duplicate entries were identified and deleted to ensure data integrity.

Date Formats Standardized:  
All date columns were converted to a consistent date format (DD-MM-YYYY) for uniformity.

Column Headers Cleaned:  
Column names were renamed to be:
- Lowercase or PascalCase where needed
- Free of special characters or extra spaces


You can load the cleaned Excel file using:

python
import pandas as pd

df = pd.read_excel("Online_Retail_Cleaned.xlsx")
print(df.head())
