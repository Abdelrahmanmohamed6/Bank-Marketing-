# Bank-Marketing-
Find the best strategies to improve for the next marketing campaign according to some features and obtain How can the financial institution have a greater effectiveness for future marketing campaigns.

Dataset Source: https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset

more information:
Find the best strategies to improve for the next marketing campaign. How can the financial institution have a greater effectiveness for future marketing campaigns? In order to answer this, we have to analyze the last marketing campaign the bank performed and identify the patterns that will help us find conclusions in order to develop future strategies.

# Bank Marketing Data Analysis and Modeling

This repository contains an analysis and modeling project based on the bank marketing dataset.

## Table of Contents

- [Introduction](#introduction)
- [Exploring the Data](#exploring-the-data)
- [Preprocessing Data](#preprocessing-data)
- [Resampling](#resampling)
- [Encoding and Standardization](#encoding-and-standardization)
- [Mutual Information](#mutual-information)
- [Grid Search](#grid-search)
- [Modeling](#modeling)

## Introduction

This project aims to analyze and model the bank marketing dataset to predict whether clients will subscribe to a term deposit. It includes data exploration, preprocessing, feature engineering, and building predictive models.

## Exploring the Data

The dataset contains various features related to bank clients, their interactions with the bank, and social-economic context attributes. Key steps in exploring the data include:

- Viewing the initial few rows of the dataset
- Checking data types, missing values, and duplicates
- Descriptive statistics of numerical features
- Checking for outliers and removing them
- Visualizing correlations and mutual information between features

## Preprocessing Data

Preprocessing steps include:

- Handling missing values and duplicates
- Splitting the dataset into training and testing sets
- Resampling to balance the dataset classes
- Encoding categorical variables and standardizing numerical features

## Resampling

Performed resampling to balance the dataset classes using the upsampling technique.

## Encoding and Standardization

Encoded categorical variables and standardized numerical features using appropriate preprocessing techniques.

## Mutual Information

Calculated mutual information between features and the target variable to assess feature importance.

## Grid Search

Utilized grid search to tune hyperparameters for a Logistic Regression model.

## Modeling

Built and evaluated several machine learning models including:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier
- Ensemble Model using Voting Classifier

Achieved promising results with the ensemble model, which combines predictions from multiple models.

For detailed information on data analysis, preprocessing steps, and model performance, refer to the Jupyter Notebook provided in this repository.
