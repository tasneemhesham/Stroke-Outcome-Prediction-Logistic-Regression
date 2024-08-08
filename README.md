# Stroke Outcome Prediction Using Logistic Regression

## Overview
This project implements a logistic regression model to predict the likelihood of a stroke based on various health features. The goal is to develop a model that can assess the risk of stroke using attributes such as age, gender, hypertension, heart disease, average glucose level, BMI, and smoking status.

## Dataset
The dataset used for this project is `stroke.csv`, which contains the following features:

- **gender**: Gender of the individual (e.g., Male, Female).
- **age**: Age of the individual.
- **hypertension**: Indicates if the individual has hypertension (0 = No, 1 = Yes).
- **heart_disease**: Indicates if the individual has heart disease (0 = No, 1 = Yes).
- **avg_glucose_level**: Average glucose level of the individual.
- **bmi**: Body Mass Index of the individual.
- **smoking_status**: Smoking status of the individual (e.g., Never smoked, Formerly smoked, Smokes).
- **stroke**: Target variable indicating if the individual had a stroke (0 = No, 1 = Yes).

## Features
- **Logistic Regression Model**: A logistic regression model to predict stroke outcomes.
- **Data Preprocessing**: Includes handling categorical variables, missing values, and feature scaling.
- **Model Evaluation**: Evaluates the model using a confusion matrix.

