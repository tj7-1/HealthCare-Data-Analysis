**Diabetes Prediction Project**

**Project Overview**

This project focuses on predicting diabetes in patients using the Pima Indians Diabetes Dataset. The goal is to build and evaluate machine learning models that can accurately classify whether a patient is diabetic based on medical features.

**Dataset**

Source: Pima Indians Diabetes Dataset

Features:

Pregnancies

Glucose

BloodPressure

SkinThickness

Insulin

BMI

DiabetesPedigreeFunction

Age

Outcome (0 = Non-diabetic, 1 = Diabetic)

**Technologies Used**

Python 3

Pandas, NumPy (Data Manipulation)

Matplotlib, Seaborn (Data Visualization)

Scikit-learn (Model Building and Evaluation)

**Project Workflow**

Data Loading & Exploration:

Loaded data and explored its structure, missing values, and distributions.

Visualized feature correlations using a heatmap.

Data Preprocessing:

Handled missing values and scaled features using StandardScaler.

Split the data into training and testing sets with stratification.

Model Building:

Implemented Logistic Regression and Random Forest classifiers.

Performed Hyperparameter Tuning with GridSearchCV to optimize models.

Model Evaluation:

Evaluated models using accuracy, confusion matrix, classification report, and ROC AUC score.

Visualized ROC curves to compare model performance.

Feature Importance Analysis:

Analyzed feature importance from the Random Forest model to identify key predictors of diabetes.

**Results**

Random Forest outperformed Logistic Regression in prediction accuracy.

Key predictors identified: Glucose, BMI, and Age.

ROC Curve analysis showed Random Forest had a better area under the curve (AUC)
