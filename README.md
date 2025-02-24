# Workforce-Planning-Dashboard-with-Predictive-Analytics

## Project Overview
This project aims to analyze employee attrition in a company using machine learning. Attrition refers to employees leaving the company, and our goal is to identify patterns and factors influencing this behavior.

## Problem Statement
Employee attrition can be costly for businesses. Understanding why employees leave can help organizations improve retention strategies, leading to better workforce management and reduced costs.

## Solution
We used machine learning techniques to analyze various factors such as age, job role, salary, work-life balance, and more to predict employee attrition. The dataset contains information on 1,470 employees with 35 different attributes.

## Tools and Platforms Used
- **Python** for data analysis and machine learning
- **Pandas & NumPy** for data manipulation
- **Scikit-learn** for model building
- **Matplotlib & Seaborn** for data visualization
- **Jupyter Notebook** for implementation

## Obtained Output
After analyzing the dataset, we obtained the following results:

- **Dataset Summary:**
  - The dataset contains **1,470 employees** and **35 different attributes** (such as age, department, education, salary, work-life balance, etc.).
  - No missing values were found in the dataset.

- **Key Findings:**
  - The dataset includes both categorical (e.g., department, job role) and numerical (e.g., age, salary) variables.
  - Employee attrition is influenced by factors like **overtime, business travel, and job role**.
  - Work-life balance and salary hikes also impact attrition rates.

- **Model Performance:**
  - The trained model achieved an **accuracy of 82%** in predicting employee attrition.
  - **Precision and recall:**
    - Employees who stay: **88% precision, 92% recall**
    - Employees who leave: **29% precision, 20% recall**

  - This suggests that while the model performs well in identifying employees who stay, it struggles in predicting employees who will leave.


**This project serves as a foundation for HR teams to predict attrition and take preventive actions accordingly.**
