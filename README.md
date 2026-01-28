# 📊 Customer Churn Analysis & Machine Learning Prediction

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green.svg)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-ML-orange.svg)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen.svg)

---

## 📌 Project Overview
Customer churn prediction is a vital analytical task that helps businesses identify customers who are likely to discontinue a service. This project implements a complete end-to-end data science pipeline, starting from raw data exploration to machine learning model development, evaluation, and interpretation.

The project demonstrates best practices in data preprocessing, exploratory data analysis (EDA), feature engineering, and supervised machine learning, with a focus on producing reliable and interpretable results.

---

## 📁 Repository Structure

├── CustomerChurnFinal.csv<br>
├── ENDTERM.ipynb<br>
└── README.md



---

## 📊 Dataset Information

- **File Name:** `CustomerChurnFinal.csv`
- **Total Records:** 64,374
- **Total Features:** 12
- **Target Variable:** `Churn`

### 🔑 Feature Description
| Feature | Description |
|-------|-------------|
| CustomerID | Unique identifier |
| Age | Customer age |
| Gender | Customer gender |
| Tenure | Duration of association |
| Usage Frequency | Service usage rate |
| Support Calls | Number of support interactions |
| Payment Delay | Delay in payments |
| Subscription Type | Type of subscription |
| Contract Length | Contract duration |
| Total Spend | Total customer spending |
| Last Interaction | Days since last interaction |
| Churn | 1 = Churned, 0 = Retained |

---

## 🔍 Methodology & Step-by-Step Workflow

This project follows a systematic and industry-standard data science lifecycle, ensuring reproducibility, clarity, and reliable model performance.

---
### 1️⃣ Data Loading & Initial Exploration
The dataset is loaded and examined to understand its structure, size, and data types.  
Initial inspection helps identify missing values, inconsistencies, and potential data quality issues.

Key activities:
- Loading the dataset using Pandas
- Inspecting shape and column data types
- Identifying missing values and anomalies

---

### 2️⃣ Data Cleaning & Preprocessing
Data preprocessing ensures the dataset is clean and suitable for analysis and modeling.

Key activities:
- Handling missing values using appropriate imputation techniques
- Cleaning inconsistent or incorrect entries
- Preparing numerical and categorical features for analysis

---

### 3️⃣ Outlier Detection & Treatment
Outliers are analyzed to reduce noise and improve model performance while preserving meaningful business information.

Key activities:
- Detecting outliers using statistical and visual methods
- Applying transformations or limits where necessary

---

### 4️⃣ Exploratory Data Analysis (EDA)

#### 🔹 Univariate Analysis
Individual features are analyzed to understand their distributions and patterns.

Key activities:
- Distribution analysis of numerical features
- Frequency analysis of categorical variables
- Understanding class imbalance in churn

#### 🔹 Bivariate Analysis
Relationships between churn and other variables are examined to identify churn-driving factors.

Key activities:
- Analyzing churn vs tenure
- Evaluating the impact of support calls and usage frequency
- Assessing contract length and subscription type

---

### 5️⃣ Feature Engineering
Raw data is transformed into meaningful features suitable for machine learning models.

Key activities:
- Encoding categorical variables
- Selecting relevant features
- Improving feature interpretability

---

### 6️⃣ Train-Test Split
The dataset is divided into training and testing subsets to ensure unbiased model evaluation.

- Training set: 80%
- Testing set: 20%

---

### 7️⃣ Machine Learning Model Development
A supervised machine learning model is trained to predict customer churn based on historical data.

Key activities:
- Selecting an appropriate classification algorithm
- Training the model using processed features

---

### 8️⃣ Model Evaluation
The trained model is evaluated using standard classification metrics.

Evaluation metrics:
- Accuracy
- Precision
- Recall
- F1-Score

---

## 📈 Key Insights
- Customers with shorter tenure show a higher likelihood of churn
- High number of support calls strongly correlates with churn
- Contract length and usage behavior are significant predictors

---

## 🛠️ Tools & Technologies
- Python
- Jupyter Notebook
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn

---

## 🚀 How to Run the Project

### Install Dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
