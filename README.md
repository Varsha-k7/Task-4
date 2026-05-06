# Task-4
Classification Model Comparison
Logistic Regression vs Decision Tree


Overview:
This Task demonstrates a complete machine learning classification pipeline.
The goal is to compare two widely used models:

Logistic Regression
Decision Tree Classifier

The models are evaluated using multiple performance metrics to determine the most reliable and generalizable model.

Objectives:
Perform binary classification on a real-world dataset
Evaluate model performance using confusion matrix and metrics
Compare Logistic Regression and Decision Tree
Analyze overfitting and model stability
Select the best model based on performance

Dataset:
Dataset Used: Breast Cancer Dataset (from sklearn)
Type: Binary Classification
Target Classes:
0 → Malignant (Cancer)
1 → Benign (No Cancer)

Workflow:
Data Loading & Preprocessing
Train-Test Split (80-20)
Feature Scaling (for Logistic Regression)
Model Training:
Logistic Regression
Decision Tree
Model Evaluation:
Confusion Matrix
Accuracy, Precision, Recall, F1 Score
ROC Curve & AUC
Model Comparison

Evaluation Metrics
Accuracy → Overall correctness
Precision → Correct positive predictions
Recall → Ability to detect actual positives
F1 Score → Balance between precision & recall
ROC-AUC → Overall classification performance

Confusion Matrix:
The confusion matrix is used to evaluate classification results:

[[TN  FP]
 [FN  TP]]
TP → Correct positive predictions
TN → Correct negative predictions
FP → Incorrect positive predictions
FN → Missed positive cases

Model Comparison:
Metric	Logistic Regression	Decision Tree
Accuracy	High	Moderate–High
Precision	High	Moderate
Recall	High	Moderate
F1 Score	High	Moderate
ROC-AUC	High	Moderate
Overfitting	Low	High

Key Insights:
Logistic Regression provides better generalization
Decision Tree is more interpretable but prone to overfitting
F1-score is preferred over accuracy for balanced evaluation
ROC-AUC confirms overall model effectiveness

Final Conclusion:

Logistic Regression was selected as the final model because:

It has balanced performance across all metrics
It shows lower overfitting
It provides more stable predictions

Technologies Used:
Vscode
Python
NumPy
Pandas
Matplotlib
Scikit-learn

Author
VARSHA KUMARI

