# StrokePrediction-ML
Machine Learning-based Stroke Prediction with Model Explainability
# Stroke Prediction Using Machine Learning

This project predicts the probability of a stroke based on various clinical and demographic features using multiple machine learning models.

---

## Dataset
- **Source**: [Kaggle – Stroke Prediction Dataset](https://www.kaggle.com/fedesoriano/stroke-prediction-dataset)
- Features: `age`, `hypertension`, `heart_disease`, `bmi`, `smoking_status`, etc.

## Preprocessing
- Missing value handling with `SimpleImputer`
- Outlier removal using IQR
- Label Encoding & One-Hot Encoding
- Feature scaling using `StandardScaler`

## Class Imbalance
- Handled using **SMOTE** (Synthetic Minority Over-sampling Technique)

## ML Models Compared
- Logistic Regression
- Decision Tree
- Random Forest
- SVM, KNN, Naive Bayes
- Gradient Boosting, AdaBoost
- XGBoost, LightGBM, CatBoost

## Evaluation Metrics
- Accuracy, Precision, Recall, F1-Score
- Confusion Matrix
- 5-Fold Cross-Validation

## Explainability
- **LIME**: Local Interpretable Model-agnostic Explanations
- **SHAP**: SHapley Additive exPlanations

## Best Model: LightGBM with ~96% accuracy

---

## Requirements
See `requirements.txt` or use:

```bash
pip install -r requirements.txt
