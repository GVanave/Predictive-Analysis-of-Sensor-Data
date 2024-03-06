# Binary Classification APS - Air Pressure System Analysis and Prediction

## Overview
This repository presents a machine learning and deep learning-based approach for predicting failures in the Air Pressure System (APS) of Scania Trucks. By accurately identifying whether a failure is attributed to the APS, this solution aims to optimize vehicle maintenance procedures, minimizing downtime and associated costs.

## Problem Statement
The task involves binary classification, distinguishing between negative cases (failures unrelated to APS, labeled as 0) and positive cases (failures due to APS, labeled as 1). The dataset comprises a comprehensive set of features collected from the APS.

## Features
In addition to the fundamental dataset attributes, various statistical features have been engineered for model training. These include mean, standard deviation, sum, minimum values of sensor readings, as well as statistical measures such as skewness and kurtosis.

## Implemented Models
The solution leverages a range of machine learning algorithms and deep learning architectures, including:
- Logistic Regression
- Support Vector Machine
- Random Forest Classifier
- Adaptive Boosting
- Deep Learning Neural Network

## Performance Evaluation
Model performance is evaluated using standard metrics such as validation loss, classification reports, confusion matrices, precision-recall curves, and ROC curves. This ensures robust evaluation and comparison across models.

## Files
This repository contains the following notebooks:
- `Approach_First.ipynb`: Model training and evaluation without PCA.
- `Approach_Second.ipynb`: Model training and evaluation with PCA applied.
- `Approach_Third.ipynb`: Model training and evaluation after data preprocessing.

## Dataset
The training dataset comprises 60,000 samples with 171 features, while the test dataset includes 16,000 samples. Notably, the dataset exhibits class imbalance, with approximately 88% negative cases and 12% positive cases.

Feel free to explore the notebooks for detailed implementation and analysis.



