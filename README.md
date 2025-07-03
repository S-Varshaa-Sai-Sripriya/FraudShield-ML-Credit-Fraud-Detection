# 🔒 FraudShield-ML: Credit Card Fraud Detection with Machine Learning

![Gemini_Generated_Image_u592vwu592vwu592](https://github.com/user-attachments/assets/62d48385-1272-427c-9009-3932f8eec19c)

A supervised machine learning project to detect fraudulent credit card transactions using anomaly-aware classification techniques. Built with Python, this model leverages real-world transaction data, performs thorough preprocessing, and applies robust classification algorithms to identify fraud with high precision.

> 🚨 Class imbalance addressed using undersampling techniques.  
> 📊 Evaluated with accuracy, precision, recall, and AUC-ROC metrics.

---

## 📊 Project Overview

This project uses a real-world credit card transaction dataset containing **highly imbalanced classes**, with only 0.17% fraudulent cases. The model classifies whether a transaction is fraudulent (`1`) or legitimate (`0`) based on anonymized features extracted via PCA.

---

## 🔍 Key Features

- ✅ **Real dataset** of ~284,000 transactions  
- ⚖️ **Class imbalance handled** using undersampling  
- 🧹 **Preprocessing**: feature scaling, class balancing  
- 🧪 **Model**: Logistic Regression  
- 📈 **Evaluation**: Confusion Matrix, AUC-ROC, Recall, Precision  

---

---

## 📈 Model Performance

| Metric      | Score     |
|-------------|-----------|
| Accuracy    | ~99.2%    |
| Recall      | 0.92+     |
| Precision   | 0.87+     |
| AUC-ROC     | 0.95+     |

> High recall is prioritized to minimize false negatives in fraud detection.

---

## 🧠 Techniques Used

- PCA-transformed anonymized features
- Train-test split with random state control
- Undersampling legitimate transactions
- Confusion matrix and ROC/AUC analysis
- Visualizations using Matplotlib/Seaborn
