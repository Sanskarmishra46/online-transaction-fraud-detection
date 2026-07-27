# 🛡️ Online Transaction Fraud Detection

> A comprehensive Machine Learning and Deep Learning project for detecting fraudulent online transactions using Python, Scikit-learn, and TensorFlow.

---

## 📌 Project Overview

Online transaction fraud has become one of the most significant challenges in the digital payment ecosystem. Financial institutions process millions of transactions every day, making manual fraud detection impractical.

This project develops and evaluates multiple Machine Learning and Deep Learning models to classify fraudulent and legitimate transactions. The workflow includes data preprocessing, feature scaling, model development, performance evaluation, and comparative analysis to identify the most effective approach for fraud detection.

---
## 🎯 Project Objectives

This project aims to:

- Detect fraudulent online transactions using Machine Learning and Deep Learning techniques.
- Compare the performance of multiple classification algorithms.
- Evaluate models using Accuracy, Precision, Recall, F1-Score, Confusion Matrix, and ROC-AUC.
- Analyze model performance through visualizations and comparative metrics.
- Identify the most effective model for online transaction fraud detection.

---
## 📂 Repository Structure

```text
online-transaction-fraud-detection/
│
├── README.md
├── LICENSE
├── .gitignore
├── requirements.txt
├── notebooks/
│   └── Online_Transaction_Fraud_Detection.ipynb
├── dataset/
│   └── README.md
└── images/
```

---
## 🛠️ Technologies Used

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Data Processing | Pandas, NumPy |
| Machine Learning | Scikit-learn |
| Deep Learning | TensorFlow, Keras |
| Data Visualization | Matplotlib, Seaborn |
| Development Environment | Jupyter Notebook (Google Colab) |
| Version Control | Git, GitHub |

---
## 📊 Dataset

The project utilizes a balanced online transaction fraud detection dataset for binary classification. The dataset was preprocessed to remove missing values and standardize numerical features before model training.

### Target Variable

| Class | Description |
|-------|-------------|
| 0 | Legitimate Transaction |
| 1 | Fraudulent Transaction |

### Data Preprocessing

- Removed missing values
- Feature scaling using StandardScaler
- Data reshaped for CNN and LSTM models
- Train-test split performed before model training

> **Note:** The original dataset was obtained from Kaggle and further processed to create a balanced dataset for model comparison.

---
