# NEO-MLFinal
This notebook aims to predict whether a near-earth object (NEO) is hazardous based on its characteristics. The data is from a dataset by NASA in which they have a column called 'is_hazardous'. This column is the target variable that will be predicted by the model using the data given.

We will build and evaluate two different machine learning models: Logistic Regression and Random Forest. The best-performing model will be chosen based on its accuracy and other performance metrics.

Model Performance Summary

Logistic Regression:

Accuracy: 0.87
ROC-AUC: 0.79

Strengths: Simplicity, interpretability
Weaknesses: May underperform on complex patterns in the data

Random Forest:

Accuracy: 0.96
ROC-AUC: 0.99

Strengths: Handles complex patterns well, robust to overfitting
Weaknesses: More computationally expensive, harder to interpret


Final Decision

Based on the results, Random Forest outperforms Logistic Regression in terms of both accuracy and ROC-AUC, making it the better model for predicting whether a near-earth object is hazardous. The confusion matrix shows that Random Forest also has better class prediction performance
