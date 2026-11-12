# python_example
# IBM HR Employee Attrition Prediction 📊

**Author:** Fenny Patel  
**Project:** Machine Learning Final Project  
**Date:** February 6, 2026

## 📌 Project Overview

Employee attrition is a major challenge for companies because losing employees increases hiring and training costs. This project uses the IBM HR Employee Dataset to analyze employee information and identify factors that may influence whether an employee leaves or stays with a company.

The main objective is to use machine learning techniques to predict employee attrition and discover patterns among different groups of employees.

## 🎯 Project Objectives

- Identify factors associated with employee attrition.
- Predict whether an employee will leave or stay with a company.
- Analyze employee characteristics such as age, monthly income, job satisfaction, and years at the company.
- Group employees based on similar characteristics.
- Explore how machine learning can help companies improve employee retention.

## 📂 Dataset

**Dataset:** IBM HR Employee Dataset

The dataset contains employee information used to analyze attrition.

Some of the features explored include:

- Age
- Monthly Income
- Years at Company
- Job Satisfaction
- Work-Life Balance
- Attrition (Yes/No)

**Target Variable:** Attrition

- Yes = Employee left the company.
- No = Employee stayed with the company.

## 🧹 Data Preprocessing and Exploration

The following preprocessing steps were performed:

- Checked for missing values.
- Checked and removed duplicate columns.
- Examined potential outliers.
- Created visualizations to explore the data.
- Generated histograms to examine age and attrition.
- Created a correlation heatmap to understand relationships between numerical variables.
- Normalized numerical data.
- Encoded categorical variables into numerical values for machine learning.

## 🤖 Machine Learning Models

Two machine learning approaches were explored.

### 1. Logistic Regression

Logistic Regression was used to predict whether an employee would leave or stay with the company.

The model analyzed employee characteristics such as age, monthly income, job satisfaction, and years at the company.

**Model parameter:** max_iter = 1000

### 2. Cluster Analysis

Cluster Analysis was used to group employees based on similar characteristics and identify patterns within the workforce.

Three clusters were explored:

- **Cluster 1:** Younger, lower-paid employees with lower job satisfaction.
- **Cluster 2:** Employees with higher satisfaction but less experience.
- **Cluster 3:** Older employees with higher job satisfaction and more experience.

The purpose was to identify employee groups that might have a higher risk of attrition.

## 📈 Model Evaluation

Different evaluation methods were used for the two approaches.

**Logistic Regression:**
- Confusion Matrix
- Accuracy
- Precision
- Recall
- F1-Score

**Cluster Analysis:**
- Silhouette Score

### Results

Logistic Regression was selected as the best model for this project because it was appropriate for predicting the binary attrition outcome (Yes or No).

Cluster Analysis produced a Silhouette Score of **0.228**, indicating that the employee groups were not clearly separated.

Therefore, Logistic Regression was more useful for the primary objective of predicting employee attrition.

## 💡 Conclusion

This project demonstrates how machine learning can help organizations better understand employee attrition.

By analyzing employee characteristics and predicting whether employees may leave, companies can identify potential retention challenges and make more informed decisions.

Logistic Regression was the most appropriate model for the project's prediction objective, while Cluster Analysis provided additional insights into employee group patterns.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Machine Learning
- Data Visualization

## 📚 Key Learning Outcomes

Through this project, I gained experience with:

- Data preprocessing and exploration.
- Handling numerical and categorical variables.
- Building a Logistic Regression classification model.
- Exploring unsupervised learning through clustering.
- Evaluating machine learning models.
- Interpreting results and identifying patterns in data.

--- 

**Thank you for visiting my project!** 😊

