# Credit Risk Analysis

## Project Overview
The goal of this project was to compare/contrast the performance of various data modeling techniques to evaluate credit card risk. Credit risk is an inherently unbalanced classification issue; good loans significantly outnumber risky loans.
For this project I used the credit card credit dataset from LendingClub, a peer-to-peer lending services company. I oversampled the data using the random oversampling and SMOTE algorithms. And I undersampled the data using the ClusterCentroids algorithm. Then, I used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Then, I compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. The two libraries used in this project were imbalanced-learn and scikit-learn.

#### Oversampling Methods
- Random Oversampling
- SMOTE

#### Undersampling Methods
- Cluster Centroids

#### Combination Over/Undersampling Methods
- SMOTEENN

#### Machine Learning Models
- Balanced Random Forest Classifier
- Easy Ensemble Classifier

## Results

### Random Oversampling
The first algorithm tested was random oversamping. 
- Accuracy score: 65% 
- Precision: 1%
- Sensitivity(Recall): 62%
- F1 score: 2%
- The low F1 score indicates a significant imbalance between precision and sensitivity.

<img width="666" alt="ROS 1" src="https://user-images.githubusercontent.com/88804543/145696692-2cc31b5d-230e-4993-9936-e6a7f9ec8347.png">














## Summary
