# Thyroid Disease Detection using Ensemble Machine Learning

This project detects thyroid disease using an ensemble of machine learning models (Random Forest, XGBoost, SVM, Logistic Regression). It handles class imbalance with SMOTE and reduces dimensionality using PCA.

## 🔍 Key Features
- Dataset preprocessing and cleaning
- Feature engineering and correlation analysis
- SMOTE for class imbalance
- PCA for dimensionality reduction
- GridSearchCV for hyperparameter tuning
- Ensemble model with VotingClassifier
- Evaluation metrics (Accuracy, F1, ROC, etc.)

## 📊 Performance
- Accuracy: 80.89% (VotingClassifier)
- Ensemble improved performance over individual models

## 🖼️ Visualizations
- Heatmaps
- Feature Importances
- ROC Curves
- Confusion Matrix

## 📁 Dataset
`thyroid_clean.csv` (anonymized and pre-cleaned)

## 📦 Requirements
Install all dependencies using:
