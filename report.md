# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis was to train and evaluate a machine learning model capable of predicting the credit risk associated with loans. Using a dataset of historical lending activity from a peer-to-peer lending services company, the goal was to build a model that can accurately identify the creditworthiness of borrowers and classify loans as either low-risk (healthy) or high-risk.

## Results

ogistic Regression Model on Imbalanced Data (Model 1)

Accuracy: 99.18%
Balanced Accuracy: 95.20%
Precision:
Healthy loans: 100%
High-risk loans: 85%
Recall:
Healthy loans: 99%
High-risk loans: 91%
This model exhibited high accuracy but was affected by the imbalance, leading to lower precision and recall for high-risk loans.


## Summary

Based on the evaluation of the logistic regression model trained on the imbalanced data, the following key points are noted:

Accuracy: The model achieved a high accuracy score of 99.18%.
Balanced Accuracy: The balanced accuracy score of 95.20% indicates that the model performs reasonably well across both classes.
Precision and Recall: The model has high precision and recall for healthy loans, but the precision and recall for high-risk loans are lower due to the class imbalance.
The logistic regression model trained on the imbalanced data shows strong overall performance but reveals limitations in correctly classifying high-risk loans. Given the importance of accurately identifying high-risk loans to mitigate potential defaults, the performance of this model could be improved by addressing the class imbalance in the dataset.

To enhance the model's ability to predict high-risk loans, further steps such as oversampling the minority class or applying other balancing techniques are recommended. This would help create a more balanced dataset, allowing the model to better learn the characteristics of high-risk loans and ultimately improving precision and recall for this critical class.

In conclusion, while the logistic regression model on imbalanced data performs well, implementing strategies to address class imbalance would likely result in more accurate and reliable predictions, particularly for high-risk loans.