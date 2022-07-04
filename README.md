# Credit_Risk_Analysis

## Overview of the analysis:

The purpose of this analysis is to understand how to use Machine Learning statistical algorithms to make predictions based on historical data. We split the data into training and testing datasets and monitor their Accuracy, Precision and Sensitivity results. In this particular case we will be using the data provided to us to Train a ML Model to be able to detect High and Low risk profiles in order to predict credit risk.

## Results:

Naive OverSampling resulted with a 0.6259 Accuracy, 0.01 Precision for High Risk and a 1.00 Precision for Low risk cases. The sensitivity is 0.6 for High risk and 0.65 for Low risk cases.

![](https://github.com/kbehyar/Credit_Risk_Analysis/blob/main/Images/Naive%20OverSampling.PNG)

SMOTE resulted with a 0.6512 Accuracy, 0.01 Precision for High Risk and a 1.00 Precision for Low risk cases. The sensitivity is 0.64 for High risk and 0.62 for Low risk cases.

![](https://github.com/kbehyar/Credit_Risk_Analysis/blob/main/Images/SMOTE%20OverSampling.PNG)

Cluster Centroids resulted with a 0.5293 Accuracy, 0.01 Precision for High Risk and a 1.00 Precision for Low risk cases. The sensitivity is 0.61 for High risk and 0.45 for Low risk cases.

### Cluster Centroids
![](https://github.com/kbehyar/Credit_Risk_Analysis/blob/main/Images/Cluster%20Centroids.PNG)

SMOTEENN resulted with a 0.6501 Accuracy, 0.04 Precision for High Risk and a 1.00 Precision for Low risk cases. The sensitivity is 0.67 for High risk and 0.90 for Low risk cases.

### SMOTEENN
![](https://github.com/kbehyar/Credit_Risk_Analysis/blob/main/Images/SMOTEENN.PNG)

Balanced Random Forest Classifier resulted with a 0.7855 Accuracy, 0.04 Precision for High Risk and a 1.00 Precision for Low risk cases. The sensitivity is 0.67 for High risk and 0.90 for Low risk cases.

![](https://github.com/kbehyar/Credit_Risk_Analysis/blob/main/Images/Balanced%20Random%20Forest%20Classifier.PNG)

Ensemble Classifier resulted with a 0.9316 Accuracy, 0.09 Precision for High Risk and a 1.00 Precision for Low risk cases. The sensitivity is 0.92 for High risk and 0.94 for Low risk cases.

![](https://github.com/kbehyar/Credit_Risk_Analysis/blob/main/Images/Easy%20Ensemble%20AdaBoost%20Classifier.PNG)


## Summary:

According to our test results, the technique of ensemble learning gives better results than under or oversampling. Ensemble learning (including Random Forest) works with many decision trees and collects all the from many "Weak Leaners" as a result our prediction, accuracy or reliability becomes better.
