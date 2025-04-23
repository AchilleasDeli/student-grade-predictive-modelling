# student-grade-predictive-modelling
linear and polynomial regression for predictive modelling for student grades
 Student Performance Prediction Using Regression
This project uses linear and polynomial regression to predict student Performance Index based on various academic and lifestyle factors. It involves data preprocessing, feature engineering, model training, evaluation, and interpretation of results.

 Project Overview
The goal is to develop a regression model that accurately predicts a student's performance based on:

Hours studied

Previous academic scores

Sleep habits

Practice exam attempts

Extracurricular activity involvement

 Dataset Features

Feature	Type	Description
Hours Studied	Numeric	Hours spent studying daily
Previous Scores	Numeric	Past exam performance
Sleep Hours	Numeric	Daily average sleep duration
Sample Question Papers Practiced	Numeric	Number of mock/practice exams
Extracurricular Activities	Categorical	Yes/No participation
Performance Index	Target	Final performance score
 Models Implemented
Linear Regression (Baseline)

Polynomial Regression (degree 1–9)

Feature scaling via StandardScaler

One-hot encoding for categorical variables

Evaluation metrics:

R² Score

MAE, MSE, RMSE

 Key Findings
Previous Scores is the most impactful feature.

Hours Studied and Practice Papers also contribute significantly.

Adding higher-degree polynomial features led to overfitting.

The linear model with scaled inputs and feature selection performs best (R² ≈ 0.988).

 Visualizations
Correlation heatmap

Actual vs. Predicted Performance Index

Polynomial degree vs. R² plot

Feature importance chart

