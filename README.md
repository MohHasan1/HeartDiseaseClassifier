# Predicting Heart Disease Using Machine Learning

This project explores the use of various Python-based machine learning and data science libraries to build a model capable of predicting whether a patient has heart disease based on their medical attributes.

## Problem Definition
Given clinical parameters about a patient, can we predict whether or not they have heart disease?

## Data
The dataset used is the Cleveland Heart Disease dataset from the UCI Machine Learning Repository. It contains 303 samples with 14 attributes, including age, sex, chest pain type, resting blood pressure, cholesterol levels, and more.

## Evaluation
The goal is to achieve 95% accuracy in predicting heart disease during the proof of concept.

## Features
- **age**: Age in years
- **sex**: 1 = male; 0 = female
- **cp**: Chest pain type (0: Typical angina, 1: Atypical angina, 2: Non-anginal pain, 3: Asymptomatic)
- **trestbps**: Resting blood pressure (in mm Hg)
- **chol**: Serum cholesterol in mg/dl
- **fbs**: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- **restecg**: Resting electrocardiographic results
- **thalach**: Maximum heart rate achieved
- **exang**: Exercise-induced angina (1 = yes; 0 = no)
- **oldpeak**: ST depression induced by exercise relative to rest
- **slope**: Slope of the peak exercise ST segment
- **ca**: Number of major vessels colored by fluoroscopy
- **thal**: Thalium stress result
- **target**: Presence of heart disease (1 = yes; 0 = no)

## Approach
1. **Exploratory Data Analysis (EDA)**: Analyze the dataset to understand the distribution of features and their relationships.
2. **Modeling**: Use machine learning models like Logistic Regression, K-Nearest Neighbors (KNN), and Random Forest to predict heart disease.
3. **Hyperparameter Tuning**: Optimize model performance using RandomizedSearchCV and GridSearchCV.
4. **Evaluation**: Assess model performance using accuracy, precision, recall, F1 score, and ROC-AUC.

## Results
- **Logistic Regression**: Achieved the highest accuracy of 85.25% on the test set.
- **Feature Importance**: The most significant features contributing to the model's predictions were `cp` (chest pain type), `thalach` (maximum heart rate), and `oldpeak` (ST depression).

## Conclusion
The Logistic Regression model performed the best, with a test accuracy of 85.25%. The model's performance can be further improved by exploring additional features or more advanced techniques.

## Google Colab
You can also run this notebook directly on Google Colab:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MohHasan1/HeartDiseaseClassifier/blob/main/HeartDiseaseClassifier.ipynb)
