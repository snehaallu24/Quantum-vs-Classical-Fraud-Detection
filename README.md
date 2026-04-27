# 🚀 Quantum vs Classical Machine Learning for Credit Card Fraud Detection

## 📌 Overview

This project presents a **comparative study of Classical and Quantum Machine Learning (QML) models** for detecting fraudulent credit card transactions.

The primary objective is to evaluate whether **quantum models can compete with or outperform classical approaches** under identical conditions.

---

## 🎯 Key Highlights

* 🔹 Fair comparison using **same dataset and same conditions**
* 🔹 Implementation of **9 models (4 Classical + 5 Quantum)**
* 🔹 Introduction of **Quantum Kernel Alignment (QKA)**
* 🔹 **QABD Analysis** to identify quantum advantage regions
* 🔹 **Noise robustness testing** for NISQ-era systems
* 🔹 Evaluation using **F1-score, ROC-AUC, PR-AUC, Cross-validation**

---

## 🧠 Models Implemented

### 🔹 Classical Machine Learning Models

* Support Vector Machine (SVM - RBF Kernel)
* XGBoost Classifier
* Random Forest
* Logistic Regression

### 🔹 Quantum Machine Learning Models

* Quantum Support Vector Machine (QSVM - ZZ Feature Map)
* Quantum Support Vector Machine (QSVM - Pauli Feature Map)
* Variational Quantum Classifier (VQC)
* Quantum Neural Network (QNN)
* Quantum Kernel Alignment (QKA)

---

## ⚙️ Tech Stack

* **Programming Language:** Python
* **Libraries:**

  * Scikit-learn
  * XGBoost
  * Qiskit (Quantum Computing)
  * Pandas, NumPy
  * Matplotlib, Seaborn
  * SHAP

---

## 📊 Dataset

The dataset used is the **Credit Card Fraud Detection Dataset** from Kaggle:

👉 https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

* Total Transactions: **284,807**
* Fraud Cases: **492 (0.17%)**
* Highly imbalanced dataset

⚠️ Note:
Due to file size limitations, the dataset is **not included in this repository**.

---

## 🧪 Methodology

### 🔹 Data Preprocessing

* Feature Scaling (StandardScaler)
* Class Balancing using **SMOTE**
* Dimensionality Reduction using **PCA (30 → 4 features)**
* Final Dataset: **200 balanced samples**

### 🔹 Training Strategy

* Same dataset used for all models
* **5-Fold Stratified Cross-Validation**
* Fair evaluation pipeline

---

## 📈 Evaluation Metrics

* Precision
* Recall
* F1 Score
* ROC-AUC
* PR-AUC

---

## 📊 Results Summary

* ✅ **SVM (Classical)** achieved the highest overall F1-score
* ✅ **QKA (Quantum)** achieved **perfect precision (1.0)**
* ✅ **QSVM** showed strong cross-validation stability
* ⚠️ Quantum models are competitive but still limited by current hardware constraints

---

## 🔬 Key Contributions

* ✔️ Fair same-data comparison framework
* ✔️ Introduction of **Quantum Advantage Boundary Detection (QABD)**
* ✔️ Noise robustness analysis (~5% threshold identified)
* ✔️ First application of **QKA for fraud detection**

---
