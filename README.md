# 📊 Customer Churn Data Analysis

This project analyzes customer churn data to identify patterns and build predictive models that can help businesses reduce churn and improve customer retention.

## 🚀 Overview

- 📌 **Goal:** Understand the factors driving customer churn and predict which customers are at risk.
- 📊 **Approach:** Perform Exploratory Data Analysis (EDA), feature engineering, and apply machine learning models.
- 🛠 **Tools:** Python, Pandas, Scikit-learn, Matplotlib, Seaborn, XGBoost


## 🧠 Key Insights

- Customers with monthly contracts are more likely to churn than those on yearly plans.
- High monthly charges and no tech support increase the probability of churn.
- Senior citizens and customers using electronic check as payment method churn more often.

## 🤖 ML Models Used

| Model              | Accuracy | Precision | Recall | F1 Score |
|-------------------|----------|-----------|--------|----------|
| Logistic Regression | 85%     | 83%       | 80%    | 81.5%    |
| Random Forest       | 88%     | 86%       | 84%    | 85%      |
| XGBoost             | 89%     | 87%       | 85%    | 86%      |

## 🗂 Dataset

- **Source:** [Kaggle - Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn)
- **Features:** Demographics, service usage, billing info
- **Target:** `Churn` (Yes/No)

## ⚙️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/churn-data-analysis.git
2. cd churn-data-analysis
3.  pip install -r requirements.txt
4.  jupyter notebook

👤 Author: Harsh Pardhi
📬 Contact: harshpardhi477@gmail.com


