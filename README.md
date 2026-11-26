#  Heart Disease Data Cleaning & EDA

A comprehensive data preprocessing and exploratory data analysis (EDA) project using Python and Pandas. This repository focuses on transforming raw, messy clinical data into a clean, analysis-ready format.

## Key Project Steps
1. **Data Inspection:** Evaluated dataframe structures, data types, and checked for explicit missing values and duplicate rows.
2. **Handling Hidden Missing Values:** 
   - Detected and removed anomalous zero-values in blood pressure (`RestingBP`).
   - Addressed hidden missing values (zeros) in clinical measurements like `Cholesterol` using median imputation.
3. **Distribution & Skewness Analysis:** 
   - Analyzed feature skewness (e.g., right-skewed cholesterol distribution) to justify statistical choices.
4. **Data Preprocessing & Preparation:** Cleaned and prepped numerical and categorical features for downstream analysis.

##  Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy
