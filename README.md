# Credit Risk Classification 
## Overview
This repository contains code for a credit risk classification model, which demonstrates strong performance in distinguishing between healthy loans (0) and high-risk loans (1). The goal of this project was to use a dataset of loan data to build a model that can identify whether a borrower can be trusted with a loan or not. 

## Model Evaluation
### Balanced Accuracy Score
The model's Balanced Accuracy Score is an impressive 0.992, signifying its ability to accurately classify both positive and negative classes while effectively handling imbalanced datasets.

### Confusion Matrix
![image](https://github.com/ashley-ley/credit-risk-classification/assets/132225987/30f44a7d-a732-4084-98bc-244f1ce01311)

+ True Positives (TP): 563
+ True Negatives (TN): 18,663
+ False Positives (FP): 102
+ False Negatives (FN): 56
  
The model correctly identified 18,663 healthy loans and 563 high-risk loans, with only 158 misclassifications, accounting for a mere 0.8% of all loans in the dataset. This performance highlights the model's excellence, particularly in identifying healthy loans.

## Classification Report
 ![image](https://github.com/ashley-ley/credit-risk-classification/assets/132225987/0e65796e-1429-4d05-836d-4c683a7884cf)

+ Precision: The precision of predicting a healthy loan was 1.00, while the precision of predicting a high-risk loan was 0.85, indicating that high-risk loans are correctly identified 85% of the time.
+ Recall (Sensitivity): The recall score for high-risk loans is 0.91, illustrating the model's ability to capture actual high-risk loans without missing many.
+ F-1 Score: The F-1 score of 0.88 demonstrates a well-balanced trade-off between precision and recall.
+ Support: The support column indicates the number of actual instances in each class, with 18,765 healthy loans and 619 high-risk loans.

## Conclusion
In summary, the logistic regression model showcased in this repository offers robust performance when distinguishing between healthy and high-risk loans. Its high precision and recall scores, along with a strong F-1 score, underscore a balanced approach to precision and recall, making it a valuable tool for credit risk classification. The logisitic regression model predicts a healthy, low-risk loan with 100% precision and a high-risk loan with 85% precision. 
