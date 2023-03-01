# Credit_Risk_Analysis

## Overview and Purpose

The purpose of this challenge is to use various machine learning models to predict credit risk. The following models were used:
- RandomOverSample (oversample the data)
- SMOTE (oversample the data)
- ClusterCentroids (undersample the data)
- SMOTEENN (combo of oversample and undersample data)
- BalancedRandomForestClassifier (reduced bias)
- EasyEnsembleClassifier (reduced bias)

## Results

### RandomOverSample
- Balance Accuracy Score: 64.1%
- High Risk: 
  - Precision: 0.01, Recall: 0.60, F1 Score: 0.02
- Low Risk: 
  - Precision: 1.00 , Recall: 0.68, F1 Score: 0.81

### SMOTE
- Balance Accuracy Score: 63.7%
- High Risk: 
  - Precision: 0.01, Recall: 0.60, F1 Score: 0.02
- Low Risk: 
  - Precision: 1.00 , Recall: 0.68, F1 Score: 0.81

### ClusterCentroids
- Balance Accuracy Score: 52.9%
- High Risk: 
  - Precision: 0.01, Recall: 0.61, F1 Score: 0.01
- Low Risk: 
  - Precision: 1.00, Recall: 0.45, F1 Score: 0.62

### SMOTEENN
- Balance Accuracy Score: 62.4%
- High Risk: 
  - Precision: 0.01, Recall: 0.70, F1 Score: 0.02
- Low Risk: 
  - Precision: 1.00, Recall: 0.55, F1 Score: 0.71

### BalancedRandomForestClassifier
- Balance Accuracy Score: 78.7%
- High Risk: 
  - Precision: 0.04, Recall: 0.67, F1 Score: 0.07
- Low Risk: 
  - Precision: 1.00, Recall: 0.91, F1 Score: 0.95

### EasyEnsembleClassifier
- Balance Accuracy Score: 92.5%
- High Risk: 
  - Precision: 0.07, Recall: 0.91, F1 Score: 0.14
- Low Risk: 
  - Precision: 1.00, Recall: 0.94, F1 Score: 0.97
  
  ## Summary
  The models used to perform a credit risk analysis resulted in low precision in determining when there is a high level for credit risk. The model that achieved the best balance accuract score would be the EasyEnsembleClassified. These models are should not be used to analyze the data that is presented as they show various levels of inaccuracies. 
