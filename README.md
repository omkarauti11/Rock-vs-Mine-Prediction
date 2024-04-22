# Rock vs Mine Prediction

This repository contains code for a machine learning model that predicts whether an object is a rock or a mine based on sonar data. The model uses Logistic Regression for classification.

## Contents

- [Description](#description)
- [Dependencies](#dependencies)
- [Data Collection and Processing](#data-collection-and-processing)
- [Training and Test Data](#training-and-test-data)
- [Model Training](#model-training)
- [Model Evaluation](#model-evaluation)
- [Making Predictions](#making-predictions)

## Description

This project utilizes machine learning techniques to classify objects as either rocks or mines based on sonar data. It includes data collection, preprocessing, model training, evaluation, and making predictions.

## Dependencies

The project requires the following dependencies:
- `numpy`
- `pandas`
- `scikit-learn`

These dependencies are used for data manipulation, model training, and evaluation.

## Data Collection and Processing

The sonar data is loaded into a pandas DataFrame and processed to prepare it for training.

## Training and Test Data

The dataset is split into training and test sets using a 90-10 split. Stratified sampling is used to maintain the class distribution in both sets.

## Model Training

A Logistic Regression model is trained using the training data.

## Model Evaluation

The accuracy of the model is evaluated using both the training and test data.

## Making Predictions

The trained model is used to make predictions on new data. An example input is provided, and the model predicts whether the object is a rock or a mine.

