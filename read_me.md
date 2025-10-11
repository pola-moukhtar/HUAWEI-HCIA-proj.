# Churn Data Analysis and Prediction Models

This project analyzes a telecom churn dataset and builds multiple machine learning models to predict customer churn.

## Contents of the Notebook

### 1. Data Loading and Basic Information
Import libraries, read the `Churn.csv` dataset, and inspect data types and missing values.

### 2. Data Cleaning and Feature Selection
Convert `TotalCharges` to numeric, drop missing entries, and select key categorical and numerical features.

### 3. Exploratory Data Analysis (EDA)
Visualize important features and their relationship with customer churn.

### 4. Missing Value Check
Recheck dataset info and confirm data quality after cleaning.

### 5. Preprocessing Pipeline
Define a reusable function to drop unnecessary columns, handle missing values, and prepare data for modeling.

### 6. Train-Test Split
Split the data into training and testing sets for model evaluation.

### 7. Model Training & Evaluation
Train and evaluate several models:
- Logistic Regression
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Multi-layer Perceptron (MLP)
- Keras Sequential Neural Network

### 8. Model Accuracy Comparison
Compare accuracy scores to identify the best-performing churn prediction model.

## Requirements
- Python 3.x
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- tensorflow / keras

## Usage
1. Open `churn_data_with_headlines.ipynb` in Jupyter Notebook or Google Colab.
2. Run all cells sequentially to reproduce the analysis and model results.

