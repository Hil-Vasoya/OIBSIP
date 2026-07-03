# 🛍️ Customer Segmentation Analysis using K-Means Clustering

## 📌 Project Overview

This project is part of the **Oasis Infobyte Data Analytics Internship (OIBSIP)**.

The objective is to perform **Customer Segmentation Analysis** using the **K-Means Clustering** algorithm. By analyzing customer purchasing behavior, the project groups customers into distinct segments to help businesses develop targeted marketing strategies and improve customer engagement.

---

## 🎯 Objective

- Analyze customer purchasing behavior.
- Perform customer segmentation using K-Means clustering.
- Identify meaningful customer groups based on behavioral features.
- Generate actionable marketing recommendations for each customer segment.

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

### ✅ Data Loading & Inspection

- Load customer dataset
- Check dataset shape
- Inspect data types
- Handle missing values
- Remove duplicate records
- Identify inconsistent data

---

### ✅ Exploratory Data Analysis

- Summary statistics
- Customer purchase distribution
- Purchase frequency analysis
- Customer Lifetime Value (CLV)
- Average purchase value

---

### ✅ Feature Engineering

Selected key behavioral features for clustering:

- **Recency (R)** – Days since last purchase
- **Frequency (F)** – Number of purchases
- **Monetary (M)** – Total amount spent

(RFM Analysis)

---

### ✅ Data Preprocessing

- Feature Selection
- Data Standardization using **StandardScaler**
- Prepare dataset for clustering

---

### ✅ K-Means Clustering

- Apply K-Means Algorithm
- Determine optimal number of clusters using the **Elbow Method**
- Train clustering model
- Assign customers to clusters

---

### ✅ Data Visualization

The project includes:

- Elbow Method Plot
- Cluster Scatter Plot (Recency vs Frequency)
- Cluster Scatter Plot (Frequency vs Monetary)
- Customer Distribution by Cluster (Bar Chart)

---

### ✅ Cluster Profiling

For each cluster:

- Average Recency
- Average Frequency
- Average Monetary Value
- Customer characteristics

Example customer groups:

- High-Value Loyal Customers
- Regular Customers
- New Customers
- At-Risk Customers
- Low-Value Customers

---

## 📈 Visualizations Used

- Scatter Plots
- Bar Charts
- Histograms
- Pair Plot (Optional)
- Elbow Curve
- Cluster Distribution Chart

---

## 🔍 Key Insights

The analysis helps identify:

- High-value customers who generate the most revenue.
- Customers who purchase frequently.
- Customers who are at risk of churn.
- Low-engagement customers.
- Potential customers for upselling and cross-selling campaigns.

---

## 💡 Marketing Recommendations

### 🟢 High-Value Customers

- Offer exclusive rewards and loyalty programs.
- Provide early access to new products.
- Personalized recommendations.

---

### 🔵 Regular Customers

- Encourage repeat purchases with discounts.
- Recommend complementary products.
- Introduce membership benefits.

---

### 🟡 New Customers

- Welcome offers.
- Personalized onboarding emails.
- Product recommendations.

---

### 🟠 At-Risk Customers

- Re-engagement campaigns.
- Limited-time discounts.
- Reminder emails.

---

### 🔴 Low-Value Customers

- Budget-friendly promotions.
- Bundle offers.
- Seasonal campaigns.

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Hil-Vasoya/OIBSIP.git
```

### 2. Navigate to the project folder

```bash
cd OIBSIP/DataAnalytics-L1-CustomerSegmentation
```

### 3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open

```
CustomerSegmentation.ipynb
```

---

## 📁 Dataset

The dataset contains customer purchase information such as:

- Customer ID
- Purchase History
- Purchase Frequency
- Transaction Amount
- Recency
- Customer Lifetime Value
- Additional customer behavioral attributes

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Customer Segmentation
- RFM Analysis
- Feature Engineering
- Data Standardization
- K-Means Clustering
- Elbow Method
- Cluster Profiling
- Data Visualization
- Business Insight Generation

---

## 📦 Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## 👨‍💻 Author

**Hil Vasoya**

Computer Science Engineering Student

GitHub: https://github.com/Hil-Vasoya

---

## ⭐ Acknowledgement

This project was completed as part of the **Oasis Infobyte Data Analytics Internship (OIBSIP)**.
