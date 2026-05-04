# 📊 Customer Churn Prediction using Machine Learning

## 🚀 Project Overview

Customer churn is a major challenge for telecom companies, as losing customers directly impacts revenue.
This project aims to predict whether a customer will churn using machine learning techniques and provide actionable insights to improve retention strategies.


## 📂 Dataset

* Telco Customer Churn Dataset (Extended Version)

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

Project Workflow-

### 1. Data Cleaning & Preprocessing

* Removed irrelevant columns (location, IDs, etc.)
* Handled missing values
* Standardized column names
* Converted categorical features into numerical format
* Feature scaling applied


### 2. Exploratory Data Analysis (EDA)

* Analyzed churn distribution
* Compared churn with tenure, monthly charges, and contract types
* Identified key behavioral patterns using visualizations

### 3. Model Building

* Implemented classification models:

  * Random Forest Classifier
  * Logistic Regression


### 4. Model Evaluation

* Accuracy: 79.46%
* Evaluated using:

  * Confusion Matrix
  * Precision, Recall, F1-score

## 📊 Key Insights

* Customers with **month-to-month contracts** show higher churn
* Customers with **higher monthly charges** are more likely to leave
* **New customers (low tenure)** have higher churn rates
* Lack of **Tech Support and Online Security** increases churn probability


## 🎯 Business Recommendations

* Encourage long-term contracts with discounts
* Improve customer support services
* Target high-risk customers with personalized offers
* Focus on retaining new customers early

## 🚀 Future Improvements

* Improve recall using class balancing techniques (SMOTE)
* Hyperparameter tuning for better performance
* Deploy model using Streamlit for real-time predictions

## 🙌 Conclusion

This project demonstrates how machine learning can be applied to solve real-world business problems by predicting customer churn and providing actionable insights.

