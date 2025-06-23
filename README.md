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
'requirements.txt'

## Cite:
N. N. Reddy, S. Maddula, P. Deepika, R. Sanjana, N. Lingadally, and S. Thoutireddy, "Enhancing thyroid cancer diagnosis with ensemble machine learning techniques," in Recent Trends in VLSI and Semiconductor Packaging, 1st ed., CRC Press, 2025, pp. 421–430. doi: 10.1201/9781003616399-54.
