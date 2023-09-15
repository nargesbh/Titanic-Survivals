# Titanic Survival Prediction

![titanic](titanic.gif)

This repository contains Python code for predicting the survival of passengers aboard the Titanic using logistic regression with L2 regularization. The dataset used for this prediction task includes passenger information such as age, gender, class, ticket fare, and more.

## Overview

In this project, I perform various steps of data preprocessing, exploratory data analysis, feature engineering, and model training to build a predictive model. Below is an overview of the main components of this repository:

### Data Preprocessing

- I start by importing necessary libraries and loading the Titanic dataset, which is divided into training and test sets.
- I perform data cleaning by omitting irrelevant features and handling missing values.
- Categorical data (e.g., gender, embarked port) is converted into numerical format.
- I standardize numerical features to ensure consistency in scale.

### Exploratory Data Analysis

- Visualizations are created to understand the distributions of key features like age and ticket fare.
- Bar plots show the relationships between passenger class (Pclass), gender (Sex), and survival.
- A correlation heatmap is used to explore the relationships between numerical features and survival.

### Model Training and Validation

- I implement logistic regression with L2 regularization (Ridge regression) to predict passenger survival.
- Cross-validation is performed to assess the model's performance and avoid overfitting.
- Hyperparameter tuning is carried out to find the best combination of learning rate and regularization strength.

### Model Deployment

- The trained model is used to make predictions on the test dataset.
- Predicted results are saved as a CSV file for submission.

## Usage

You can use this code to build your own Titanic survival prediction model by following the steps outlined in the Jupyter Notebook provided in this repository.

## Dependencies

- Python 3.x
- Libraries: pandas, matplotlib, numpy, seaborn, scikit-learn

