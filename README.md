# Heart Disease Classification

Hands-On Machine Learning (Géron, 2nd ed.) – **Chapter 3: Classification**, applied to the UCI Heart Disease dataset (`heart.csv`, 1025 rows).

## Contents
- EDA, class balance, and detection of 723 duplicate rows (data leakage)
- Baseline (DummyClassifier), Logistic Regression, KNN, LDA, QDA, SVM, Decision Tree, Random Forest
- Model comparison with 5-fold cross-validation on de-duplicated data
- Confusion matrix, precision, recall, F1 via `cross_val_predict`
- Precision/recall trade-off and threshold tuning for ≥90% recall
- ROC curves and AUC
- Multiclass (chest-pain type, OvO vs OvR) and multilabel classification

## Run
Put `heart.csv` next to the notebook and run all cells (scikit-learn, pandas, matplotlib).
