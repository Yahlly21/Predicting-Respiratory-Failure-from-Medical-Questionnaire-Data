# Project Description: Predicting Respiratory Failure from Medical Questionnaire Data
## Yahlly Schein & Dor Bar 


## Project Overview
This project focuses on predicting respiratory failure in patients using a dataset provided by a pulmonary clinic. The dataset includes questionnaire data from patients, some of whom have experienced respiratory failure, while others have not.  
The goal of the project is to implement a binary classification model to predict whether a patient is likely to suffer from respiratory failure based on the provided features.  
This project was graded in a format similar to a Kaggle competition, and our work achieved the 2nd best performance among all students in the course this year.

### Project Stages and methodology:

**Data Exploration and Preprocessing:**

Data Understanding: Analyzed the dataset to understand the distribution, types of features (numerical, categorical, binary), and the presence of missing values.  
Data Cleaning: Handled missing values, removed outliers, and converted categorical features to numerical representations.  
Feature Engineering: Added and transformed features, including normalizing numerical data and reducing dimensionality using techniques like PCA.

**Model Selection and Training:**
Trained multiple models including Logistic Regression, Decision Trees, CatBoost, and a Multi-Layer Perceptron (ANN).
Performed hyperparameter tuning using techniques like Cross Validation and GridSearchCV to optimize model performance.
Selected the best model based on AUC scores from validation tests.

**Model Evaluation:**

Evaluated models using the AUC metric and analyzed the results through confusion matrices and ROC curves.  
Chose the ANN model as the final model based on its superior performance on the validation set.


**Prediction and Final Output:**
Applied the selected model to a test dataset to make predictions. Exported the predicted probabilities to a CSV file for final submission.
