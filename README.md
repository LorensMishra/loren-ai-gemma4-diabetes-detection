# **LOREN_AI  Early Diabetes Risk Analysis System**

![alt text](thumbnail.jpg)

## Overview

Gemma(LOREN_AI)Health AI is a healthcare-focused data analytics and machine learning project designed to identify diabetes risk patterns using patient medical and lifestyle information.

Diabetes is one of the most common chronic diseases worldwide, yet many people remain unaware of their risk until serious complications appear. Factors such as obesity, abnormal blood sugar levels, hypertension, smoking habits, and cardiovascular conditions can significantly increase diabetes risk.

This project explores these health indicators through data analysis and predictive modeling to better understand diabetes patterns and support preventive healthcare.

The system combines healthcare analytics, machine learning, and explainable AI concepts to analyze patient information and predict diabetes risk more effectively.

---

## Problem Statement

Diabetes has become a growing public health concern. Many individuals fail to recognize early warning signs due to limited awareness of medical indicators such as blood glucose level, HbA1c level, body mass index (BMI), and hypertension.

Late diagnosis can lead to severe complications including:

* Heart disease
* Kidney damage
* Vision problems
* Poor metabolic health

This project aims to analyze healthcare data and identify meaningful patterns associated with diabetes risk using data-driven methods.

---

## Project Objective

### Primary Objective

To analyze healthcare data and identify important indicators contributing to diabetes risk using data analytics and machine learning techniques.

### Secondary Objectives

* Understand healthcare patterns related to diabetes
* Analyze the impact of BMI, blood glucose, and HbA1c level
* Identify high-risk patient characteristics
* Compare machine learning models for prediction
* Support preventive healthcare awareness

---

## Dataset Information

The dataset used in this project was collected from Kaggle and contains healthcare and lifestyle-related patient information.

### Dataset Source

[Kaggle](https://www.kaggle.com?utm_source=chatgpt.com)

### Dataset Features

| Feature             | Description                                           |
| ------------------- | ----------------------------------------------------- |
| gender              | Gender of patient                                     |
| age                 | Age of patient                                        |
| hypertension        | Indicates presence of hypertension (0 = No, 1 = Yes)  |
| heart_disease       | Indicates presence of heart disease (0 = No, 1 = Yes) |
| smoking_history     | Smoking behavior of patient                           |
| bmi                 | Body Mass Index                                       |
| HbA1c_level         | Average blood sugar level over time                   |
| blood_glucose_level | Blood glucose measurement                             |
| diabetes            | Diabetes status (Target Variable)                     |

### Target Variable

**Diabetes**

* **0 → Non-Diabetic**
* **1 → Diabetic**

---

## Project Workflow

The project follows a structured healthcare analytics workflow:

### 1. Data Collection

The diabetes healthcare dataset was collected from Kaggle.

### 2. Data Understanding

The dataset structure, feature types, and medical indicators were analyzed.

### 3. Data Cleaning

Data preprocessing was performed to:

* Check missing values
* Remove duplicate records
* Verify data types
* Detect data inconsistencies

### 4. Exploratory Data Analysis (EDA)

EDA was performed to understand healthcare patterns and diabetes-related behavior.

Analysis included:

* Diabetes distribution analysis
* Gender analysis
* Age analysis
* Hypertension analysis
* Heart disease analysis
* Smoking history analysis
* BMI analysis
* HbA1c level analysis
* Blood glucose level analysis
* Correlation analysis
* Outlier detection

### 5. Statistical Insights

Statistical methods were used to identify major diabetes risk factors.

### 6. Machine Learning

Machine learning models were trained for diabetes prediction.

Models used:

* Logistic Regression
* Random Forest Classifier

### 7. Model Evaluation

Models were evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report

### 8. Healthcare Recommendation Layer

The project provides healthcare-focused recommendations based on diabetes risk indicators.

---

## Key Findings

Several important healthcare insights were identified during analysis:

### Blood Glucose Level

Blood glucose level showed one of the strongest relationships with diabetes risk.

Patients with higher glucose values were more likely to have diabetes.

### HbA1c Level

HbA1c emerged as one of the strongest medical indicators of diabetes.

Elevated HbA1c levels were commonly observed among diabetic patients.

### BMI (Body Mass Index)

Higher BMI values were strongly associated with increased diabetes prevalence.

This highlights obesity as an important lifestyle-related risk factor.

### Age

Older age groups showed greater diabetes occurrence compared to younger individuals.

### Hypertension and Heart Disease

Patients with hypertension and heart disease demonstrated higher diabetes prevalence.

---

## Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

### Development Environment

* Jupyter Notebook / Kaggle Notebook

### AI Concept

* Gemma 4 Inspired Explainable Healthcare Insights

---

## Machine Learning Models

### Logistic Regression

Used as a baseline classification model for diabetes prediction.

### Random Forest Classifier

Used to improve prediction accuracy and identify important healthcare indicators.

---

## Real-World Impact

This project has practical healthcare applications.

It can help:

* Improve early diabetes awareness
* Support preventive healthcare strategies
* Help individuals understand health risks
* Encourage healthy lifestyle changes
* Improve healthcare accessibility through explainable AI

By identifying diabetes risk earlier, healthcare interventions can be implemented before severe complications develop.

---

## Future Improvements

Several improvements can enhance this project further:

* Real-time diabetes prediction system
* Healthcare web application
* Medical report upload feature
* Personalized AI health explanations
* Multilingual healthcare support
* Larger healthcare datasets for better prediction

---

## Conclusion

Gemma Health AI demonstrates how healthcare analytics and machine learning can be used to better understand diabetes risk.

By analyzing important medical indicators such as BMI, blood glucose level, HbA1c level, hypertension, and lifestyle habits, the project provides meaningful healthcare insights and supports preventive care.

This project highlights the importance of combining healthcare data analysis with explainable AI to make medical insights more understandable and accessible.

---

## Author

Developed as part of a healthcare-focused AI and data analytics project for learning, research, and hackathon innovation.
