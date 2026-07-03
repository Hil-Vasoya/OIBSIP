# 🏡 House Price Prediction using Linear Regression

## 📌 Project Overview

This project is part of the **Oasis Infobyte Data Analytics Internship (OIBSIP)**.

The objective of this project is to build a **Linear Regression** model that predicts house prices based on various property features such as area, location, number of bedrooms, bathrooms, and house age. The project covers the complete machine learning workflow, from data exploration and preprocessing to model training, evaluation, and interpretation.

---

## 🎯 Objective

- Explore and understand the house price dataset.
- Identify the key factors influencing house prices.
- Clean and preprocess the dataset.
- Train a Linear Regression model.
- Evaluate model performance using regression metrics.
- Interpret feature importance through model coefficients.
- Compare predictions with actual house prices.

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Project Workflow

### ✅ Exploratory Data Analysis (EDA)

The dataset is analyzed to understand its structure and quality by performing:

- Dataset inspection
- Missing value analysis
- Data type verification
- Descriptive statistics
- Target variable (House Price) distribution
- Feature distribution analysis

---

### ✅ Feature Selection

Potential predictors of house price are identified based on domain knowledge and statistical analysis, including:

- Area
- Number of Bedrooms
- Number of Bathrooms
- Number of Floors
- Parking Availability
- House Age
- Location
- Furnishing Status
- Other relevant property features

A markdown discussion explains why these features are expected to influence house prices.

---

### ✅ Data Preprocessing

The preprocessing stage includes:

- Handling missing values
- One-Hot Encoding for categorical variables
- Data cleaning
- Preparing the dataset for model training

---

### ✅ Correlation Analysis

A correlation heatmap is created to identify the relationship between numerical variables and house prices, helping determine the most influential features.

---

### ✅ Model Training

The dataset is split into:

- **80% Training Data**
- **20% Testing Data**

A **Linear Regression** model is trained using Scikit-learn to predict house prices.

---

### ✅ Model Evaluation

The model is evaluated using the following performance metrics:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score (Coefficient of Determination)

These metrics measure prediction accuracy and overall model performance.

---

### ✅ Data Visualization

The notebook includes several visualizations, including:

- House Price Distribution
- Correlation Heatmap
- Actual vs Predicted House Prices Scatter Plot
- Residual Plot
- Feature Importance (Regression Coefficients)

---

### ✅ Coefficient Analysis

The regression coefficients are analyzed to determine:

- Features with the strongest positive influence on house prices.
- Features with the strongest negative influence on house prices.
- The relative importance of each predictor in the model.

---

### ✅ Model Comparison (Bonus)

For improved performance and reduced overfitting, the project optionally compares Linear Regression with:

- Ridge Regression
- Lasso Regression

The evaluation metrics of each model are compared to determine the best-performing approach.

---

## 📈 Key Features

- Data Exploration
- Data Cleaning
- Missing Value Handling
- One-Hot Encoding
- Feature Selection
- Correlation Analysis
- Linear Regression
- Model Evaluation
- Residual Analysis
- Feature Importance Interpretation
- Model Comparison

---

## 🔍 Key Insights

The analysis provides valuable insights into:

- The most significant factors affecting house prices.
- The strength of relationships between property features and selling price.
- The predictive capability of Linear Regression.
- Model strengths and limitations based on residual analysis.
- Opportunities for improving prediction accuracy using regularization techniques.

---

## 💡 Real-World Applications

House price prediction models can be applied in various domains, including:

- Real Estate Valuation
- Property Investment Analysis
- Mortgage and Loan Assessment
- Real Estate Recommendation Systems
- Housing Market Analysis
- Property Price Estimation Platforms

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Hil-Vasoya/OIBSIP.git
```

### 2. Navigate to the project folder

```bash
cd OIBSIP/DataAnalytics-L2-HousePricePrediction
```

### 3. Install required libraries

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open

```
HousePricePrediction.ipynb
```

---

## 📁 Dataset

The dataset contains residential property information, including features such as:

- Area
- Location
- Number of Bedrooms
- Number of Bathrooms
- Number of Floors
- Parking Availability
- Furnishing Status
- House Age
- Selling Price

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Exploratory Data Analysis (EDA)
- Data Cleaning and Preprocessing
- Feature Engineering
- One-Hot Encoding
- Correlation Analysis
- Linear Regression
- Model Evaluation
- Residual Analysis
- Feature Importance Interpretation
- Regression Model Comparison

---

## 📦 Libraries Used

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

---

## 👨‍💻 Author

**Hil Vasoya**

Computer Science Engineering Student

GitHub: https://github.com/Hil-Vasoya

---

## ⭐ Acknowledgement

This project was completed as part of the **Oasis Infobyte Data Analytics Internship (OIBSIP)**.
