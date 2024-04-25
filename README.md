# Wine Classification 

This project focuses on building a pipeline for wine classification using various machine learning algorithms. It involves data preprocessing, model selection, training, evaluation, and result visualization.

## Overview

The project performs the following steps:

1. **Importing Libraries and Loading Data**:
   - Imports necessary libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.
   - Loads the Wine dataset from the UCI Machine Learning Repository.

2. **Data Exploration and Visualization**:
   - Checks the first few rows, summary statistics, missing values, and class distribution of the dataset.
   - Visualizes significant correlations between features using heatmaps and bar charts.

3. **Data Preprocessing and Splitting**:
   - Assigns column names to the dataset.
   - Splits the dataset into features (X) and target variable (y).
   - Splits the data into training and testing sets.

4. **Model Selection and Training**:
   - Creates a pipeline with standard scaling and different classifiers (Logistic Regression, Random Forest, SVM).
   - Performs cross-validation to select the best model based on accuracy.

5. **Model Evaluation**:
   - Trains the best model on the training data.
   - Evaluates the model on the testing data using accuracy, classification report, and confusion matrix.
   - Generates detailed prediction reports and visualizes the confusion matrix for better interpretation.
