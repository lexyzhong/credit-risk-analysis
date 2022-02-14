# Credit Risk Analysis
## Overview
In this project, we will employ different techniqiues to train and evaluate models with unbalanced classes. The data being analyzed is a credit card dataset from LendingClub. Techniques to be used:
- oversampling using RandomOverSampler and SMOTE algorithms
- undersampling using ClusterCentroids algorithm
- combinatory over- and undersampling using SMOTEENN algorithm
- predicting credit risk with machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier

## Results
### Naive Random Oversampling
- Accuracy: 60.7%
- Precision: 99%
- Recall: 61%
![https://github.com/lexyzhong/credit-risk-analysis/blob/main/Resources/Naive%20Random%20Oversampling.png](https://github.com/lexyzhong/credit-risk-analysis/blob/main/Resources/Naive%20Random%20Oversampling.png)

### SMOTE Oversampling
- Accuracy: 69.1%
- Precision: 99%
- Recall: 69%
![https://github.com/lexyzhong/credit-risk-analysis/blob/main/Resources/SMOTE%20Oversampling.png](https://github.com/lexyzhong/credit-risk-analysis/blob/main/Resources/SMOTE%20Oversampling.png)

### Undersampling
- Accuracy: 39.7%
- Precision: 99%
- Recall: 40%
![https://github.com/lexyzhong/credit-risk-analysis/blob/main/Resources/Undersampling.png](https://github.com/lexyzhong/credit-risk-analysis/blob/main/Resources/Undersampling.png)

### Combination (Over & Undersampling)
- Accuracy: 57.5%
- Precision: 99%
- Recall: 57%
![https://github.com/lexyzhong/credit-risk-analysis/blob/main/Resources/Combination%20(Over%20and%20Under)%20Sampling.png](https://github.com/lexyzhong/credit-risk-analysis/blob/main/Resources/Combination%20(Over%20and%20Under)%20Sampling.png)

### Balanced Random Forest Classifier
- Accuracy: 78.8%
- Precision: 99% 
- Recall: 91%
![https://github.com/lexyzhong/credit-risk-analysis/blob/main/Resources/Balanced%20Random%20Forest%20Classifier.png](https://github.com/lexyzhong/credit-risk-analysis/blob/main/Resources/Balanced%20Random%20Forest%20Classifier.png)

### Easy Ensemble AdaBoost Classifier
- Accuracy: 92.5% 
- Precision: 99%
- Recall: 94%
![https://github.com/lexyzhong/credit-risk-analysis/blob/main/Resources/Easy%20Ensemble%20AdaBoost%20Classifier.png](https://github.com/lexyzhong/credit-risk-analysis/blob/main/Resources/Easy%20Ensemble%20AdaBoost%20Classifier.png)

## Summary
Of the models tested, Easy Ensemble AdaBoost Classifier performed the best, offering the higest accuracy, precision, and recall percetnage.
