# 💳 Credit Card Fraud Detection

A comparison study of five machine learning models to detect fraudulent financial transactions in a highly imbalanced dataset.

---

## 🔍 Models Evaluated

- **Random Forest**
- **AdaBoost**
- **XGBoost**
- **Isolation Forest**
- **Local Outlier Factor (LOF)**

---

## 📂 Project Structure

1. **`01_data_exploration.ipynb`**  
   Begin here. You'll need to manually download the dataset files:

   - A `.csv` file containing the transaction data
   - A `.json` file containing the metadata

2. **`02_classifier_experiment.ipynb`**  
   This notebook runs the fraud detection experiments and compares model performance.

---

## ⚠️ About the Data

The dataset is **highly imbalanced**, with fraud cases being extremely rare compared to normal transactions.

Our objective is to **maximize the detection of fraudulent activities**.  
Hence, **recall (true positive rate)** is prioritized over **precision**, as **missing a fraud is more costly than a false alert**.

---

## 💡 Note on SMOTE

While **SMOTE** (Synthetic Minority Over-sampling Technique) can be used to rebalance the dataset, this experiment focuses on model performance without synthetic sampling. A future enhancement could explore its impact separately.

---
