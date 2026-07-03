# 🧹 Data Cleaning and Preprocessing

## 📌 Project Overview

This project is part of the **Oasis Infobyte Data Analytics Internship (OIBSIP)**.

The objective of this project is to demonstrate professional-level **data cleaning and preprocessing** skills by transforming a raw, messy dataset into a clean, consistent, and analysis-ready dataset. Every cleaning decision is documented to ensure transparency and reproducibility.

---

## 🎯 Objective

- Assess the overall quality of a raw dataset.
- Identify and handle missing values.
- Detect and remove duplicate records.
- Standardize inconsistent data formats.
- Identify and handle outliers.
- Correct data types.
- Generate a clean dataset suitable for further analysis or machine learning.

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Jupyter Notebook

---

## 📊 Data Cleaning Workflow

### ✅ Data Quality Assessment

The initial inspection includes:

- Dataset shape
- Column information
- Missing value count
- Duplicate row detection
- Data type inspection
- Value range anomaly detection

---

### ✅ Missing Value Handling

Different imputation techniques are applied based on the nature of each column, including:

- Mean Imputation
- Median Imputation
- Mode Imputation
- Forward Fill
- Row Deletion (where appropriate)

Each decision is documented with justification in the notebook.

---

### ✅ Duplicate Removal

- Detect duplicate records
- Remove duplicate rows
- Record the total number of duplicates removed

---

### ✅ Data Standardization

The dataset is standardized by:

- Normalizing text values (e.g., "Male", "male", "M" → "Male")
- Converting date columns to a consistent datetime format
- Removing unnecessary spaces
- Standardizing categorical values

---

### ✅ Outlier Detection

Outliers are identified using statistical methods such as:

- Interquartile Range (IQR)
- Z-Score

Each detected outlier is evaluated and either:

- Retained
- Capped
- Removed

with documented reasoning.

---

### ✅ Data Type Correction

Column data types are corrected where necessary, including:

- Dates → Datetime
- IDs → String
- Numeric values → Integer or Float
- Categories → Appropriate categorical format

---

### ✅ Before vs After Comparison

A summary comparison is generated to highlight the improvements made during the cleaning process, including:

- Number of rows
- Missing values
- Duplicate records
- Data type accuracy

---

### ✅ Export Clean Dataset

The cleaned dataset is saved as a new CSV file for future analysis and machine learning tasks.

---

## 📈 Key Operations Performed

- Missing Value Analysis
- Duplicate Detection
- Data Standardization
- Data Type Conversion
- Outlier Detection
- Data Quality Reporting
- Dataset Export

---

## 🔍 Key Insights

The cleaning process improves the overall quality of the dataset by:

- Eliminating incomplete or inconsistent records.
- Standardizing formats for reliable analysis.
- Correcting invalid data types.
- Reducing noise caused by duplicate entries and outliers.
- Producing a structured dataset ready for visualization, statistical analysis, or predictive modeling.

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Hil-Vasoya/OIBSIP.git
```

### 2. Navigate to the project folder

```bash
cd OIBSIP/DataAnalytics-L1-DataCleaning
```

### 3. Install required libraries

```bash
pip install pandas numpy jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open

```
DataCleaning.ipynb
```

---

## 📁 Dataset

The dataset contains intentionally inconsistent and incomplete records to demonstrate real-world data cleaning techniques. It includes missing values, duplicate entries, inconsistent formatting, incorrect data types, and potential outliers.

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Data Quality Assessment
- Missing Value Treatment
- Duplicate Removal
- Data Standardization
- Outlier Detection
- Data Type Conversion
- Data Preprocessing
- Dataset Validation
- Preparing Data for Analysis and Machine Learning

---

## 📦 Libraries Used

- pandas
- numpy

---

## 👨‍💻 Author

**Hil Vasoya**

Computer Science Engineering Student

GitHub: https://github.com/Hil-Vasoya

---

## ⭐ Acknowledgement

This project was completed as part of the **Oasis Infobyte Data Analytics Internship (OIBSIP)**.
