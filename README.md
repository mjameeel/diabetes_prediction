# Diabetes Classification

![stop_diabetes](diabetes-1270350_1280.jpg)
Image by <a href="https://pixabay.com/users/nneem-1611501/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=1270350">nneem</a> from <a href="https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=1270350">Pixabay</a>

## Introduction

To determine patient's diabetes status, a model can be used to accurately predict whether a patient is diabetic or not based on features attributed to the diabetes. In this project, a machine learning model is built using Random Forest Classifier with hyper-parameters tuning to predict whether a patient is diabetic or not. The accuracy score of the model was 71%. With more training data, this performance can be enhanced.

## About the Datasets

The data used can be found [here]([https://www.kaggle.com/](https://www.kaggle.com/datasets/mrsimple07/diabetes-prediction))

## Dependences

The libraries used in this project are as follows:
* Pandas
* Numpy
* Matplotlib
* Sklearn
* Pickle

## Data Cleaning

The dataset has no missing values, except that there was an observation with age below 0. The data frame was cleaned by removing neagative ages.

## Exploratory Data Analysis

In exploration of the data, a histogram was ploted to see the distribution of features. All the features are normally distributed with no outliers. A class balance was also plotted to see the distribution of diabetic and non diabetic patients. 

## Model Building and Prediction

The data is split with diagnosis as the target vector and other features as the features matrix. A random forest classifier with hyper-parameters tuning was then built and fitted with the data.

## Model Evaluation

The accuracy score of the model was found to be 0.71. This shows that the model is fairly good in predicting the diagnosis of patients. But with more training data, this can be improved.

## Conclussion

Patients need to be classified to help early diagnosis of diabetes. A model like this can go a long way in stop the increasing number of patients who are at risk of being diagnosed diabetic.
