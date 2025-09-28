# heart-disease-uci-end-to-end-ml-pipeline
End-to-end machine learning pipeline on the UCI Heart Disease dataset: data preprocessing, feature engineering, PCA, feature selection, supervised &amp; unsupervised learning, hyperparameter tuning, and deployment with Streamlit &amp; Ngrok.

## Overview
This project aims to build a machine learning model to predict the risk of heart disease based on patient clinical data. It covers data preprocessing, feature selection, dimensionality reduction, model training, and evaluation.

## Dataset
- *Dataset used:* Cleveland Heart Disease Dataset (processed.cleveland.data)
- *Number of features:* 13 clinical features plus target variable
- *Source:* [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/45/heart+disease)

## Features Used
- Age
- Sex
- Chest pain type (cp)
- Resting blood pressure (trestbps)
- Serum cholesterol (chol)
- Fasting blood sugar (fbs)
- Resting ECG results (restecg)
- Maximum heart rate achieved (thalach)
- Exercise induced angina (exang)
- ST depression induced by exercise (oldpeak)
- Slope of the peak exercise ST segment (slope)
- Number of major vessels colored by fluoroscopy (ca)
- Thalassemia (thal)
- Diagnosis of heart disease (target) (num)

## Project Steps
1. Data Preprocessing
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling
2. Dimensionality Reduction (PCA)
3. Feature Selection
4. Model Training
   - Tested multiple models including Logistic Regression, Decision Tree, Random Forest, and SVM
5. Hyperparameter Tuning
   - Performed using GridSearchCV / RandomizedSearchCV
6. Model Evaluation
   - Metrics such as Accuracy, Precision, Recall, and F1 Score
   - Detailed results are saved in results/evaluation_metrics.txt

## Results
- *Best Model:* Random Forest (example, adjust based on final results)
- *Achieved Accuracy:* ~90.16%
- Precision, Recall, and F1 Score are included in evaluation metrics
- This project represents a first end-to-end machine learning experience.
