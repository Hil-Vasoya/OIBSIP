# 😊 Sentiment Analysis using Machine Learning

## 📌 Project Overview

This project is part of the **Oasis Infobyte Data Analytics Internship (OIBSIP)**.

The objective of this project is to build a **Sentiment Analysis** model capable of classifying text into **Positive**, **Negative**, or **Neutral** sentiments. The project demonstrates a complete Natural Language Processing (NLP) workflow, including text preprocessing, feature extraction, machine learning model training, evaluation, and result interpretation.

---

## 🎯 Objective

- Analyze text data to determine sentiment.
- Perform text preprocessing for machine learning.
- Convert text into numerical features using TF-IDF.
- Train and compare multiple classification algorithms.
- Evaluate model performance using standard classification metrics.
- Visualize sentiment distribution and frequently occurring words.
- Identify common prediction errors and suggest improvements.

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn
- WordCloud
- Jupyter Notebook

---

## 📊 Project Workflow

### ✅ Dataset Inspection

The dataset is explored by:

- Checking dataset dimensions
- Viewing sample records
- Inspecting missing values
- Examining sentiment class distribution
- Understanding data balance

---

### ✅ Text Preprocessing

The preprocessing pipeline includes:

- Converting text to lowercase
- Removing punctuation
- Removing special characters
- Removing stopwords
- Tokenization
- Optional stemming or lemmatization

This step prepares raw text for feature extraction and improves model performance.

---

### ✅ Feature Extraction

Text data is transformed into numerical representations using **TF-IDF (Term Frequency–Inverse Document Frequency)**.

TF-IDF highlights important words while reducing the influence of commonly occurring words, making it an effective representation for text classification.

---

### ✅ Model Training

The dataset is divided into:

- 80% Training Data
- 20% Testing Data

Two machine learning models are trained and compared:

- Multinomial Naive Bayes
- Logistic Regression *(or Support Vector Machine, depending on implementation)*

---

### ✅ Model Evaluation

Each model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

The results are compared to determine the best-performing classifier.

---

### ✅ Data Visualization

The notebook includes visualizations such as:

- Sentiment Distribution Bar Chart
- WordCloud for Positive Reviews
- WordCloud for Negative Reviews
- WordCloud for Neutral Reviews
- Confusion Matrix Heatmap

---

### ✅ Error Analysis

The project examines incorrectly classified samples by:

- Displaying five misclassified examples
- Comparing predicted and actual labels
- Discussing possible reasons for incorrect predictions
- Identifying opportunities for future model improvements

---

## 📈 Key Features

- Data Inspection
- Text Cleaning
- Tokenization
- Stopword Removal
- TF-IDF Feature Extraction
- Machine Learning Classification
- Model Comparison
- Performance Evaluation
- WordCloud Generation
- Error Analysis

---

## 🔍 Key Insights

The analysis provides valuable insights into:

- Overall sentiment distribution within the dataset.
- Frequently used words associated with each sentiment.
- Comparative performance of different machine learning algorithms.
- Common sources of prediction errors.
- Effectiveness of TF-IDF in text classification tasks.

---

## 💡 Real-World Applications

Sentiment Analysis has applications across various industries, including:

- Customer Feedback Analysis
- Product Review Classification
- Social Media Monitoring
- Brand Reputation Management
- Market Research
- Customer Support Automation
- Opinion Mining
- Business Intelligence

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Hil-Vasoya/OIBSIP.git
```

### 2. Navigate to the project folder

```bash
cd OIBSIP/DataAnalytics-L1-SentimentAnalysis
```

### 3. Install required libraries

```bash
pip install pandas numpy scikit-learn nltk matplotlib seaborn wordcloud jupyter
```

### 4. Download NLTK resources

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
```

### 5. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 6. Open

```
SentimentAnalysis.ipynb
```

---

## 📁 Dataset

The dataset contains text samples labeled with one of the following sentiment categories:

- Positive
- Negative
- Neutral

Examples include customer reviews, product feedback, tweets, or other textual opinions suitable for sentiment classification.

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Natural Language Processing (NLP)
- Text Preprocessing
- Tokenization
- Stopword Removal
- Stemming and Lemmatization
- TF-IDF Vectorization
- Machine Learning Classification
- Model Evaluation
- Confusion Matrix Interpretation
- WordCloud Visualization
- Error Analysis

---

## 📦 Libraries Used

- pandas
- numpy
- scikit-learn
- nltk
- matplotlib
- seaborn
- wordcloud

---

## 👨‍💻 Author

**Hil Vasoya**

Computer Science Engineering Student

GitHub: https://github.com/Hil-Vasoya

---

## ⭐ Acknowledgement

This project was completed as part of the **Oasis Infobyte Data Analytics Internship (OIBSIP)**.
