# credit-risk-classification
Challenge 20


# Credit Risk Analysis Report
The purpose of the analysis is to evaluate a model based on loan risk  by using a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.


The model adopted is Logistic Regression which is used when the dependent variable is binary or categorical.
The output is the probability of an event occurring, and it is transformed using the logistic function to be between 0 and 1 i.e. if the model predicts 0 it is a healthy loan and 1 if it is a high-risk loan.


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


Recommendation:
The model's accuracy is good at predicting if a loan will default because of the high accuracy and F-1 and recall scores are high on both the training and testing sets, which is promising. Although the results are promising, prior to adopting this model for loan risk to determine creditworthiness of borrowers, it is recommended, to enhance and confirm the model results, by further checking aspects such as imbalanced datasets, false positives and model robustness adopting and trialing other models such as using ensemble learning.


Resources:
- Data from Monash Data Bootcamo Course Aug 2023 cohort