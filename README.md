# Fraud Detection Project

## Overview
This project aims to develop a fraud detection system using machine learning techniques. The system will analyze various data points and identify potential fraudulent activities.

This challenge is from `https://zindi.africa/competitions/xente-fraud-detection-challenge/data`

## Features
- Data preprocessing: Clean and transform raw data into a suitable format for analysis.
- Feature engineering: Extract relevant features from the data to improve model performance.
- Model training: Build and train machine learning models to detect fraudulent activities.
- Model evaluation: Assess the performance of the trained models using appropriate metrics.

# Results

I have 0.68 % of private score on Zindi with this algorithm.

I had 0.71 % in a previous submission but in this one, I did'nt use OneHotEncoder on my 5 categorical values but I used OrdinalEncoder which is not coherent with what I explained previously about why I used OneHotEncoder.

I prefered to be more logical on the machine learning approach

It could be possible to upgrade the model : 
- Using more feature engineering by modeling some cluster with for exmeple BatchId.
- Looking for other types of algorithms like MLP which are very powerfull with these kind of big dataset
- Using PCA for reduction of dimensionality
- More fine-tuning with RandomizedSearchCV to tune the hyperparameter