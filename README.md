# Multi-Output Classification modelling

## Overview
This project aims to demonstrate multi-output classification modelling. Multi-output classification is a type of classification task where each sample can have multiple labels associated with it.

## File Structure
- `train.csv`: Training data.
- `trainLabels.csv`: Training labels.
- `test.csv`: Test data.
- `Karthik - AIQoD assignment.ipynb`: Python script for data preprocessing, model building, prediction, and submission.
- `Karthik_submissionfile.xlsx`: Submission file with predicted labels.

## Dependencies
- pandas
- scikit-learn
- scipy
- numpy

## Dataset
The dataset consists of three CSV files:
1. `train.csv`: Training data containing features.
2. `trainLabels.csv`: Training labels containing the target labels for the training data.
3. `test.csv`: Test data for which predictions need to be made.

## Approach
### Data Preprocessing:
- Handling missing values using SimpleImputer and KNNImputer.
- Encoding categorical variables using LabelEncoder.
- Standardizing numerical features using StandardScaler.
- Vectorizing text features using TfidfVectorizer.

### Model Building:
- Using a Random Forest Classifier as the base classifier.
- Utilizing MultiOutputClassifier to handle multi-output classification.

### Prediction and Submission:
- Predicting labels for the test dataset.
- Creating a submission file with predictions.


