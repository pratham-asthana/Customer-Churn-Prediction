# Customer Churn Prediction

Welcome to the Customer Churn Prediction repository! This project aims to predict customer churn using machine learning techniques. Customer churn refers to the phenomenon where customers stop doing business with a company. Accurately predicting churn can help businesses take proactive measures to retain customers and enhance their services.

## Project Overview

The main goal of this project is to build a predictive model that identifies customers who are likely to churn based on their historical data. The repository contains data preprocessing scripts, exploratory data analysis (EDA), feature engineering, model training, evaluation, and deployment.

## Features

- **Data Preprocessing:** Handling missing values, encoding categorical variables, feature scaling, and data splitting.
- **Exploratory Data Analysis (EDA):** Visualizations and statistical analysis to understand the data and identify patterns.
- **Feature Engineering:** Creating new features to improve model performance.
- **Model Building:** Implementing various machine learning algorithms such as Logistic Regression, Decision Trees, Random Forest, Gradient Boosting, and Neural Networks.
- **Model Evaluation:** Assessing the performance of models using metrics like accuracy, precision, recall, F1-score, and AUC-ROC.
- **Deployment:** Exporting the trained model and creating an API for real-time predictions.

## Repository Structure

customer-churn-prediction/
│
├── data/
│ ├── raw/ # Raw data files
│ ├── processed/ # Processed data files
│
├── notebooks/
│ ├── 01_data_preprocessing.ipynb
│ ├── 02_eda.ipynb
│ ├── 03_feature_engineering.ipynb
│ ├── 04_model_building.ipynb
│ ├── 05_model_evaluation.ipynb
│
├── src/
│ ├── data_preprocessing.py
│ ├── feature_engineering.py
│ ├── model_building.py
│ ├── model_evaluation.py
│ ├── app.py # Flask API for model deployment
│
├── requirements.txt # Required Python packages
├── README.md # Project documentation
└── LICENSE # Project license
