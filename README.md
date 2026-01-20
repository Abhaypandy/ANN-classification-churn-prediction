# ANN-classification-churn-prediction

# 🧠 Customer Churn Prediction using Artificial Neural Network (ANN)

This project predicts whether a bank customer will **exit the bank (Churn = 1)** or **stay (Churn = 0)** based on demographic, financial, and account activity features.
It uses a **deep learning-based Artificial Neural Network (ANN)** built with **TensorFlow/Keras**.

---

## 📌 Project Overview

Banks lose millions due to customer churn. Predicting which customers are likely to leave helps improve retention and business strategy.

In this project, I built an **end-to-end ANN classification model** that analyzes customer data and predicts churn using advanced machine learning techniques.

---

## 📂 Dataset Description

The dataset contains **14 input features** such as:

- **CustomerId, Surname**
- **Credit Score**
- **Geography (France, Spain, Germany)**
- **Gender**
- **Age**
- **Tenure**
- **Balance**
- **Number of Products**
- **Has Credit Card**
- **Is Active Member**
- **Estimated Salary**

**Target variable:**
`Exited` → 1 (customer left) / 0 (customer stayed)

---

## 🛠️ Tech Stack

- **Python**
- **TensorFlow / Keras**
- **NumPy**
- **Pandas**
- **Scikit-learn**
- **Matplotlib & Seaborn (visualization)**

---

## 🔍 Workflow

### 1️⃣ Data Preprocessing

- Handle missing values
- Encode categorical features:
  - Label Encoding (`Gender`)
  - One-Hot Encoding (`Geography`)
- Feature Scaling using StandardScaler
- Train–test split

### 2️⃣ Model Architecture (ANN)

- Input Layer
- Two Dense Hidden Layers (ReLU activation)
- Dropout layers to prevent overfitting
- Output Layer (Sigmoid activation for binary classification)
- Optimizer: **Adam**
- Loss Function: **Binary Crossentropy**

### 3️⃣ Model Evaluation

Measured using:

- Accuracy
- Confusion Matrix
- Precision, Recall, F1-Score
- ROC Curve

---

## 📊 Results

The ANN achieved strong performance in predicting customer churn and identified key patterns such as:

- Active members are less likely to churn
- Higher balance customers tend to leave more
- Geography has a significant influence on churn rate

_(Customize this section with your exact metrics if you want.)_

---

## 🚀 How to Run This Project

### 1. Clone the repository

git clone https://github.com/Abhaypandy/ANN-classification-churn-prediction.git
churn_env
