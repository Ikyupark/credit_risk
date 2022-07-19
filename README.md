# credit_risk
## Overview of the analysis: Explain the purpose of this analysis.
The purpose of this analysis was to investigate and evaluate multiple models for accuracy score.

## Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

### Random Oversampling
![image](https://user-images.githubusercontent.com/100812042/179656021-3b492c03-23df-4b58-bb79-0312e94728a9.png)

Balanced accuracy score: 64.1%
Precision: 1% for high risk 100% for low risk
Recall: 72% for high risk and 56% for low risk

### SMOTE oversampling
![image](https://user-images.githubusercontent.com/100812042/179656498-234d7b0d-e3ac-4c0a-8539-be65ec66a9d1.png)

Balanced accuracy score: 65.9%
Precision: 1% for high risk and 100% for low risk
Recall: 62% for high risk and 69% for low risk

### Undersampling
![image](https://user-images.githubusercontent.com/100812042/179656645-f2575512-2ff4-41f6-8cef-2971fdf9d462.png)

Balanced accuracy score: 66%
Precision: 1% for high risk 100% for low risk
Recall:62% for high risk and 69% for low risk

### Combination Under-Over-Sampling
![image](https://user-images.githubusercontent.com/100812042/179656753-2a7d4d76-e1da-4013-8789-cffc71a565ed.png)

Balanced accuracy score: 64%
Precision: 1% for high and 100% for low
Recall: 70% for high and 58% for low

### Balanced
![image](https://user-images.githubusercontent.com/100812042/179656913-2e403ab6-703e-4592-a3f2-3e5f210a1530.png)

Balanced accuracy score: 78.9%
Precision: 3% for high and 100% for low
Recall: 70% for high and 87% for low

### ADAboost Classifer 
![image](https://user-images.githubusercontent.com/100812042/179656979-ce5f42c9-bc67-4a15-99df-970fc4e4ebad.png)

Balanced accuracy score: 93.1%
Precision: 9% for high and 100% for low
Recall:92% for high and 94% for low 

## Summary

The results show that all models have higher than 90% in precision for low risk. The best machine learning model would be Easy Ensemble Adaboost Classifier since it gives the highest precision, recall and accuracy. 
