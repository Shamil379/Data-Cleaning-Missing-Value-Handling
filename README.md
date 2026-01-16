# Data Cleaning & Missing Value Handling

## Overview
This project focuses on cleaning and preprocessing two datasets:
- **Housing Dataset**
- **Medical Appointment Dataset**

The goal was to identify, visualize, and handle missing values to improve data quality before further analysis or machine learning.

---

## Steps Performed

1. **Dataset Loading**
   - Loaded both datasets using Pandas in a Jupyter Notebook.

2. **Missing Value Identification**
   - Used `.isnull().sum()` to detect missing values in each column.

3. **Missing Data Visualization**
   - Visualized missing value patterns using simple bar charts.

4. **Numerical Data Imputation**
   - Applied **median imputation** to numerical columns to handle outliers effectively.

5. **Categorical Data Imputation**
   - Applied **mode imputation** to categorical columns.

6. **High Missing Value Removal**
   - Removed columns with more than **40% missing values** to avoid poor data quality.

7. **Validation**
   - Verified that no missing values remained after cleaning.
   - Compared dataset shape and quality before and after cleaning.

---

## Deliverables

- `Housing_Cleaned.csv` – Cleaned Housing dataset  
- `Medical_Appointment_Cleaned.csv` – Cleaned Medical Appointment dataset  
- `Data_Cleaning_Notebook.ipynb` – Jupyter Notebook with all cleaning steps

---

## Outcome
After cleaning, both datasets are complete, consistent, and ready for exploratory data analysis or machine learning tasks.
