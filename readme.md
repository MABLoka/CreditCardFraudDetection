# Credit Card Fraud Detection

This project implements a machine learning pipeline to detect fraudulent credit card transactions using the [Kaggle Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). It demonstrates data preprocessing, model training, and evaluation in the context of an imbalanced classification problem.

---

## Dataset Summary

- **Total Transactions**: 284,807
- **Fraudulent Transactions**: 492 (0.172%)
- **Features**: 30 (anonymized PCA components + `Amount`, `Time`)
- **Target**: `Class` (0 = normal, 1 = fraud)

---

## Key Steps

1. **Data Acquisition**
   - Dataset downloaded using the Kaggle API
   - CSV file loaded with `pandas`

2. **Exploratory Data Analysis**
   - Data inspection and basic statistics
   - Class imbalance check

3. **Model Training**
   - Includes standard SVMM
   - Evaluation using metrics suited for imbalanced data (Precision, Recall, F1 Score)

4. **Imbalanced Handling**
   - Resampling techniques (e.g., SMOTE or undersampling)
   - ROC-AUC curve visualization

---

## Notes

  Be cautious of class imbalance — metrics like accuracy are misleading

  Try different models and oversampling methods for better performance

---

## Tech Stack

  -Python

  -Pandas, Scikit-learn

  -Jupyter Notebook
