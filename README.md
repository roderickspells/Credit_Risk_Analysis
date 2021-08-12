# Credit_Risk_Analysis

## Overview

For this project, I am utizlizing supervised machine learning with Python to preict and determine if credit was a high or a low risk. The goal was to predict high risk credit with a high accuracy and with a level of sensitivity and precision that would not allow for great creditors to be declined for bias. For my analysis, I utilized oversampling methods, undersampling methods and classifying methods to minimize biases. 

### Machine Learning Models Used

Naive Random Oversampling \
SMOTE Oversampling \
Cluster Centroid Undersampling \
SMOTEENN Sampling \
Balanced Random Forest Classifying \
Easy Ensemble Classifying


### Software

Jupyter Notebook \
Python Machine Learning

## Results

### Naive Random Oversampling

- Accuracy: 66.6%
- Precision High Risk: 1%
- Precision LowRisk: 100%
- Recall (Accuracy) High Risk: 70%
-Recall (Accuracy) Low Risk: 63%

![image](https://github.com/roderickspells/Credit_Risk_Analysis/blob/main/Challenge/images/naive_oversampling.png?raw=true)


### SMOTE Oversampling

- Accuracy: 66.2%
- Precision High Risk: 1%
- Precision LowRisk: 100%
- Recall (Accuracy) High Risk: 63%
-Recall (Accuracy) Low Risk:69%

![image](https://github.com/roderickspells/Credit_Risk_Analysis/blob/main/Challenge/images/SMOTE_oversampling.png?raw=true)


### Cluster Centroid Undersampling

- Accuracy: 54.4%
- Precision High Risk: 1%
- Precision LowRisk: 100%
- Recall (Accuracy) High Risk: 69%
-Recall (Accuracy) Low Risk: 40%

![image](https://github.com/roderickspells/Credit_Risk_Analysis/blob/main/Challenge/images/Cluster_Centroid_Undersampling.png?raw=true)


### SMOTEENN Sampling

- Accuracy: 64.5%
- Precision High Risk: 1%
- Precision LowRisk: 100% 
- Recall (Accuracy) High Risk: 72% 
-Recall (Accuracy) Low Risk: 57%

![image](https://github.com/roderickspells/Credit_Risk_Analysis/blob/main/Challenge/images/SMOTEENN_Sampling.png?raw=true)

### Balanced Random Forest Classifying

- Accuracy: 77.7%
- Precision High Risk: 3%
- Precision LowRisk: 100%
- Recall (Accuracy) High Risk: 68%
-Recall (Accuracy) Low Risk: 87%

![image](https://github.com/roderickspells/Credit_Risk_Analysis/blob/main/Challenge/images/Balanced_Random_Forest_Classifying.png?raw=true)


### Easy Ensemble AdaBoost Classifying

- Accuracy: 91.8%
- Precision High Risk: 9%
- Precision LowRisk: 100% 
- Recall (Accuracy) High Risk: 89%
-Recall (Accuracy) Low Risk: 94%

![image](https://github.com/roderickspells/Credit_Risk_Analysis/blob/main/Challenge/images/Easy_Ensemble_AdaBoost_Classifier.png?raw=true)



## Summary
Since we are looking for a model to predict credit worthiness, we want a model that will be more precise than sensitive as we do not want potential creditors to be denied when they are in fact a great customer to have. We are looking for a model that would be have the least amount of high risk loans approved (Recall High Risk), a low lever of low risk loans deemed high risk (Recall Low Risk), and an overall accuracy score.

Based on the classifcation reports from each model, the Easy Ensemble Classifying model would be the best overall predictor in assesing credit risk as it has a high accuracy rate (91.8%), high precision levels for identifying low risk credits (100%), low levels of low risk creditors being denied (9%) as well as (94%) recall rate for identifying low risk loans that were deemed high risk.


