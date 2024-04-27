# Linear Regression

Linear regression is a statistical technique that seeks to establish a linear relationship between a dependent variable (Y) and one or multiple independent variables (X), by minimizing the sum of squared differences between actual Y values and the values predicted by a linear equation. It aims to estimate the coefficients (slope and intercept) of the linear equation, enabling prediction and interpretation of the dependent variable’s variations based on changes in the independent variables.

## 1. Data Preparation

- Split the dataset into 50% for training, 30% for validation, and 20% for testing.
- Normalize/Regularize data if necessary.
- Encode categorical variables using appropriate encoding method if necessary.

## 2. Linear Regression Model

Formulate a linear regression model between the observations x(i)j and target parameter y(i).
y(i) = θ0 + Xjθj∗x(i)j
Not used any specific library for doing it

## 3. Model Training

Use the mean squared error loss function to fit the following models.

### Model 1: Analytic Solution
- Report the R-squared and RMSE score for the test set after training the model.

### Model 2: Gradient Ascent
- Use an iterative solution via gradient ascent.
- Use 3 different learning rates: 0.01, 0.001, and 0.0001.
- Plot the Loss function for the training set and validation set at each iteration.
- Report the R-squared and RMSE score for the test set.

# Logistic Regression

Logistic regression is a statistical method used for binary classification. It models the probability of an event occurring by fitting a logistic curve to data, assigning values between 0 and 1. It’s a vital tool for predicting outcomes like yes/no or true/false in various fields.

## 1. Data Preparation

- Split the dataset into 50% for training, 30% for validation, and 20% for testing.
- Normalize/Regularize data if necessary.
- Encode categorical variables using appropriate encoding method if necessary.

## 2. Logistic Regression Classifier

Implement a standard Logistic Regression Classifier. Not used scikit-learn for this part.

## 3. Evaluation Metrics

Report the mean accuracy, precision, and recall for the class 1 (good) for the classifiers.
