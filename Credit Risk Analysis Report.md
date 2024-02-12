# Module 20 Credit Risk Analysis Report

## Overview of the Analysis

The objective of the analysis is to determine if the selected model should be adopted to determine determine creditworthiness of borrowers

The dataset of historical lending activity from a peer-to-peer lending services company was split into a training and a testing model, omce the model is run the score od the training and testing models are comapred to determine if the model selected is appropriate for the intended application.

The model adopted is `LogisticRegression` which is used when the dependent variable is binary or categorical.
The output is the probability of an event occurring, and it is transformed using the logistic function to be between 0 and 1 i.e. if the model predicts 0 it is a healthy loan and 1 if it is a high-risk loan.

## Results

Summary of the TRAINING results (0) of the machine learning model.
- Accuracy: 0.993912505158894, which is high and suggests the single measurements or predictions are close to the true value
- Precision: 1.00, which is high and refers to consistency and repeatability of the set of measurements
- Recall scores: 1.00, look at the sensitivity between true positives and false negatives, this suggests that the model is effective in capturing a significant proportion of positive instances.
- F-1 score: 1.00, F1-score equals 1, it means that the model has achieved perfect precision and recall simultaneously.

Summary of the TEST results (1) of the machine learning model.
- Accuracy: 0.993912505158894, which is high and suggests the single measurements or predictions are close to the true value
- Precision: 0.87, which is high and refers to consistency and repeatability of the set of measurements
- Recall scores: 0.95, look at the sensitivity between true positives and false negatives, this suggests that the model is effective in capturing a significant proportion of positive instances.
- F-1 score: 0.91, F1-score equals 1, it means that the model has achieved high precision and recall simultaneously.

## Summary

The model's accuracy is good at predicting if a loan will default because of the high accuracy and F-1 and recall scores are high on both the training and testing sets, which is promising. Although the results are promising, prior to adopting this model for loan risk to determine creditworthiness of borrowers, it is recommended, to enhance and confirm the model results, by further checking aspects such as imbalanced datasets, false positives and model robustness adopting and trialing other models such as using ensemble learning.
