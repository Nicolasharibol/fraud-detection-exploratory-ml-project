# Fraud Detection – Exploratory Machine Learning Project

## Project Overview
End-to-end machine learning project focused on detecting fraudulent credit card transactions in a highly imbalanced dataset.
The project emphasizes model evaluation, trade-off analysis, and justified model selection, rather than accuracy alone.

All work is documented in a single Jupyter Notebook, following a clean, reproducible workflow.

## Problem Statement
Fraud detection is an imbalanced binary classification problem where:

- Fraud cases are rare
- False Negatives are more costly than False Positives

Model evaluation is therefore centered on recall, confusion matrix analysis, and ROC-AUC.

## Models Trained
- Logistic Regression – interpretable baseline
- Random Forest Classifier – non-linear ensemble model
- CatBoost Classifier – gradient boosting with strong class separation
- LightGBM Classifier – efficient gradient boosting framework

All models were trained and evaluated using the same data split and metrics.

## Evaluation and Results 
Models were compared using:

- Precision, Recall, F1-score
- Confusion Matrix
- ROC-AUC score (numerical comparison)

➡️ Random Forest was selected as the final model, as it provided the best balance between False Negatives and False Positives, aligning with the business objective of minimizing missed fraud.

## Key Skills Demonstrated 
- Key Skills Demonstrated
- Imbalanced classification handling
- Model comparison and selection
- Business-driven evaluation metrics
- Ensemble learning (bagging & boosting)

## Future Improvements
- Hyperparameter tuning
- Cross-validation
- Cost-sensitive learning
- Advanced ensemble methods (e.g., gradient boosting)
- Feature engineering informed by domain knowledge
