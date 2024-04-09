# Diabetes Prediction Model using Support Vector Machine (SVM)

This project aims to predict whether a person has diabetes or not based on certain medical predictor variables using the Support Vector Machine (SVM) algorithm. The dataset used for this task is the PIMA Diabetes Dataset.

## Dataset Overview

The PIMA Diabetes Dataset contains several medical predictor variables and one target variable, Outcome (0 for non-diabetic, 1 for diabetic).

## Workflow

### Data Collection and Analysis

- Loaded the dataset into a Pandas DataFrame.
- Explored the dataset by printing the first 5 rows, checking the shape, and getting statistical measures.
- Checked the distribution of diabetic and non-diabetic persons in the dataset.
- Calculated the mean values of various features grouped by the outcome.

### Data Preprocessing

- Separated the data into features (X) and labels (Y).
- Standardized the features using StandardScaler.
- Split the dataset into training and testing sets (80% training, 20% testing) using stratified sampling.

### Model Training

- Utilized the SVM algorithm with a linear kernel to train the model.
- Evaluated the model's performance on the training and testing datasets using accuracy score.

### Predictive System

- Created a simple system to predict diabetes for a given input using the trained model.
