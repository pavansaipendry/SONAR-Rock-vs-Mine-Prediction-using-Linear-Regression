# SONAR-Rock-vs-Mine-Prediction-using-Linear-Regression
## Project Overview

This project focuses on predicting whether a sonar signal indicates a rock or a mine using linear regression. By analyzing sonar data, the model aims to classify signals based on features extracted from frequency measurements. The project leverages machine learning techniques to provide insights into the performance of a linear regression model for classification tasks.


## Introduction

This notebook implements a machine learning pipeline that uses a linear regression algorithm to classify sonar signals. Sonar data is a collection of 60 frequency-based features, and each record is labeled as either a rock or mine signal. The primary objective is to build a predictive model that can differentiate between these two classes effectively.

## Dataset

The dataset used in this project is the **SONAR** dataset, containing 208 observations with 60 attributes, representing different frequency components of sonar signals. Each observation is labeled as either:

- **Rock (R)**
- **Mine (M)**

More details about the dataset can be found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+%28sonar,+mines+vs.+rocks%29).
- Link to Dataset: https://www.kaggle.com/code/manishkr1754/sonar-rock-vs-mine-prediction


## Approach

1. **Data Preprocessing**: We begin by cleaning and normalizing the dataset to prepare it for modeling.
2. **Modeling**: We employ the **Linear Regression** algorithm for classification. While linear regression is traditionally used for regression problems, we modify it to solve this binary classification problem by mapping output values to class labels.
3. **Evaluation**: The model is evaluated using accuracy metrics and confusion matrices to measure its performance.

## Results

The model's performance is evaluated on test data. Key metrics include:

- **Accuracy**: 0.7857142857142857
