# Heart-Disease-Prediction-Using-Machine-Learning
## Overview
This project is designed to predict the likelihood of heart disease in individuals by leveraging a logistic regression model. Predicting heart disease early on can be crucial for timely intervention and preventive measures. The project utilizes a dataset containing various health-related features to train and evaluate the predictive model.

## Table of Contents
### Introduction
### Dependencies
### Data Collection
### Data Processing
### Model Training
### Model Evaluation
### Building a Predictive System
### Usage

## Introduction
Heart disease is a leading cause of mortality globally, and early detection is essential for effective treatment. This project focuses on creating a predictive model using logistic regression to assess the likelihood of an individual having heart disease based on their health metrics.

## Dependencies
To run this project, you need to have the following Python libraries installed:

NumPy
Pandas
scikit-learn
You can install these dependencies using the following command:

bash
pip install numpy pandas scikit-learn
## Data Collection
The dataset used for this project is stored in a CSV file named data.csv. This dataset includes information such as age, sex, blood pressure, cholesterol levels, and other health-related parameters.

## Data Processing
Data processing involves several steps:

Loading the dataset into a Pandas DataFrame.
Exploring the first and last five rows of the dataset to understand its structure.
Checking for missing values to ensure data completeness.
Exploring statistical measures to understand the distribution of features.
Splitting the data into features (X) and the target variable (Y).
Further dividing the dataset into training and test sets for model evaluation.
## Model Training
The logistic regression model is selected due to its effectiveness in binary classification problems. The model is trained on the training dataset to learn the patterns and relationships within the data.

## Model Evaluation
The accuracy of the logistic regression model is assessed using both the training and test datasets. The accuracy score is calculated to quantify the model's performance in predicting heart disease.

## Building a Predictive System
A predictive system is implemented to take input data and predict whether an individual is likely to have heart disease based on the trained logistic regression model. This system can be used for real-time predictions.

## Usage
To use this project, follow these steps:

Install the required dependencies using the provided command.
Ensure that the dataset (data.csv) is available.
Run the provided Python script to execute the entire pipeline from data processing to model evaluation.
