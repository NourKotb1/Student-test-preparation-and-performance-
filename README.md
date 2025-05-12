# 🎓 Student Performance Prediction using Machine Learning

## 📌 Project Overview

This project demonstrates an end-to-end machine learning pipeline to predict whether a student has completed a test preparation course. As a data scientist at an educational institution, the aim is to leverage predictive analytics to understand student behavior and performance patterns.

## 🎯 Objective

To predict a binary target (completion of a test preparation course) based on features like gender, race/ethnicity, parental education level, lunch type, and exam scores.

## 📂 Dataset Description

The dataset consists of student-level data with the following columns:

- `gender`: Gender of the student
- `race/ethnicity`: Group classification
- `parental level of education`: Education level of the student’s parents
- `lunch`: Type of lunch the student receives
- `test preparation course`: Target variable – whether the course was completed
- `math score`: Exam score in mathematics
- `reading score`: Exam score in reading
- `writing score`: Exam score in writing

## 🛠️ Tools & Technologies

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## ✨ Features

- Data cleaning and preprocessing
- Feature engineering (Label Encoding)
- Exploratory Data Analysis (EDA)
- Binary classification using multiple ML models
- Evaluation using accuracy, F1-score, precision, and recall
- Handling class imbalance using SMOTE

## 📈 Results & Insights

- Built and compared multiple classification models
- Applied oversampling to improve predictions on imbalanced data
- Achieved insights into which factors correlate most with test preparation completion

## 📊 Future Improvements

- Try advanced models like XGBoost or LightGBM
- Hyperparameter tuning using GridSearchCV
- Deploy the model as an API
