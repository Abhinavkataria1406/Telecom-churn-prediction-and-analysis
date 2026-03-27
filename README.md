## 📊 Telecom Customer Churn Analysis
## 🚀 Overview

This project analyzes telecom customer data to understand churn behavior and builds machine learning models to predict which customers are likely to leave.

 ## 🎯 Objectives
- Identify key factors influencing customer churn
- Perform exploratory data analysis (EDA)
- Build predictive models to classify churn
- Compare multiple models for performance

## 🛠️ Tech Stack
- Python (Pandas, NumPy, Scikit-learn)
- Visualization: Matplotlib, Seaborn
- Machine Learning: Logistic Regression, Random Forest, SVM
- Deep Learning: TensorFlow/Keras

## 📂 Dataset
- Telecom customer dataset (~7,000 records, 20+ features)
- Includes customer demographics, services, billing, and churn status

## 🔍 Key Steps
- Data Cleaning
- Handled missing values (e.g., TotalCharges)
- Converted categorical variables to numeric
- Exploratory Data Analysis
- Churn distribution analysis
- Contract type vs churn
- Tenure impact on churn
- Feature Engineering
- Encoding categorical variables
- Feature scaling (StandardScaler)
- Model Building
- Logistic Regression ,
Random Forest (with GridSearchCV tuning) ,
Support Vector Machine (SVM) ,
Neural Network (Keras) ,
- Model Evaluation
Accuracy, Precision, Recall, F1-score, ROC-AUC ,
Confusion Matrix comparison

## 📊 Results
- Logistic Regression: ~80% accuracy
- Random Forest: ~77% accuracy (better recall for churn)
- SVM: ~79% accuracy
- Neural Network: ~80% accuracy

## 📈 Key Insights
- Customers with month-to-month contracts have highest churn
- Low tenure customers are more likely to churn
- Lack of additional services (security, support) increases churn
