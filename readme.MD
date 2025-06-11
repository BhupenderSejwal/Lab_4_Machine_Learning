# Week 5 Lab: Data Tidying, Cleaning, and Outlier Detection

##  Overview
This lab focuses on fundamental data preprocessing techniques using Python. You'll learn how to **tidy**, **clean**, and **detect/remove outliers** in datasets using `pandas`, `NumPy`, and `scikit-learn`.

---

##  Sections Covered:

### 1. Data Tidying
- Convert messy data to tidy format using `melt()` and `pivot_table()`
- Practice on PEW Research and Billboard datasets
- Extract week numbers, convert columns, and format time-based data

### 2. Data Cleaning
- Handle missing values in the `cars.csv` dataset
- Use `.isnull().sum()` and percentages to identify nulls
- Clean with:
  - `.dropna()`
  - Mean/Median imputation
  - `SimpleImputer` from `sklearn`

### 3. Outlier Detection
Outliers are detected using:
- **Z-Score**: Remove rows with Z-scores > 2
- **IQR (Interquartile Range)**:
  - Calculate Q1, Q3, and IQR
  - Define bounds
  - Remove rows outside `[Q1 - 1.5 * IQR, Q3 + 1.5 * IQR]`

---

##  Libraries Used
- `pandas`
- `numpy`
- `scipy`
- `sklearn`

---

##  Learning Outcomes
- Tidy unstructured data into a usable format
- Handle missing values intelligently
- Detect and remove outliers using statistical methods
- Prepare cleaner, more accurate data for analysis or modeling

---

##  Notes
- Always visualize data before and after cleaning
- Choose imputation or removal based on dataset size and importance
- Keep a copy of raw data before modification

---

##  Run Environment
- Python 3.8+
- Jupyter Notebook
- Libraries: install via `pip install pandas numpy scipy scikit-learn`

---
