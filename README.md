# 📊 Customer Churn Prediction Using Artificial Neural Networks (ANN)

## 📌 Project Overview

Customer churn is a major concern in the banking sector, as retaining existing customers is significantly cheaper than acquiring new ones. This project applies an **Artificial Neural Network (ANN)** to predict whether a bank customer is likely to leave or remain, based on demographic and financial features.

⚠️ **Note:** This project is intended for educational and portfolio purposes and does not represent a production-ready system.


## 🎯 Objectives

- Develop an ANN-based binary classification model
- Evaluate model performance using accuracy, confusion matrix, and ROC–AUC
- Predict churn probability for new customer profiles


## 📂 Dataset

- **Source:** `Churn_Modelling.csv`

- **Observations:** 10,000

- **Target Variable:** `Exited`
  - `1` → Customer churned
  - `0` → Customer retained

- **Features:**

  - Credit Score  
  - Geography  
  - Gender  
  - Age  
  - Tenure  
  - Balance  
  - Number of Products  
  - Credit Card Ownership  
  - Active Membership Status  
  - Estimated Salary  


## 🧠 Model

- Algorithm: Artificial Neural Network (MLPClassifier)
- Hidden Layers: 1 (100 neurons)
- Activation Function: ReLU
- Optimizer: Adam
- Feature Scaling: StandardScaler



## 📊 Evaluation Metrics

- Accuracy
- Confusion Matrix
- Precision, Recall, F1-score
- ROC Curve and AUC Score


## 🔍 Example Prediction

The trained model is used to predict churn probability for a new customer, demonstrating how probabilistic outputs can support business decisions using adjustable thresholds.


## 🛠️ Tools & Libraries

- Python
- NumPy
- Pandas
- Scikit-learn (MLPClassifier)
- Matplotlib

## 📝 Summary

This project demonstrates the application of an Artificial Neural Network (ANN) to predict customer churn in the banking sector using demographic and financial data. The model follows a complete machine learning workflow, including data preprocessing, feature encoding, scaling, model training, and performance evaluation.

The ANN achieved strong classification performance, with results evaluated using accuracy, confusion matrix, classification report, and ROC–AUC analysis. In addition to model evaluation, the project showcases a realistic business use case by predicting churn probability for a new customer and interpreting the result using a probability-based decision threshold.

Overall, this project highlights practical skills in:

- Supervised machine learning and neural networks

- Data preprocessing and feature engineering

- Model evaluation and performance interpretation

- Translating model outputs into business-relevant insights

## 🚀 How to Run

1. Clone the repository
2. Install required libraries

```bash
pip install -r requirements.txt

jupyter notebook ANN_Customer_Churn_Prediction.ipynb


