# 📉 Customer Churn Prediction using PyTorch

This project builds an Artificial Neural Network (ANN) to predict whether a customer will **churn (leave the company)** based on features like contract type, charges, tenure, and more. It is a **binary classification** problem.

---

## 📁 Project Files

- `BinaryclassificationAnn(customer_churn_prediction).ipynb`: Main notebook with full implementation.
- `requirements.txt`: Python dependencies required to run the project.
- `customer_churn.csv`: Input dataset (assumed, replace with your actual filename if needed).

---

## 🧾 Problem Statement

Given historical customer data, the model predicts whether a customer is likely to **churn** or **stay**. This helps businesses proactively reduce churn and retain customers.

---

## 🛠️ Tech Stack

- **Language**: Python
- **Framework**: PyTorch
- **Libraries**:
  - `pandas`, `numpy`
  - `sklearn` for preprocessing and metrics
  - `torch` for model development

---

## 🔄 Workflow

1. **Load Dataset**
2. **Encode Categorical Features** using LabelEncoder or OneHotEncoder
3. **Scale Numerical Features** using StandardScaler
4. **Split Data** into training and testing sets
5. **Create PyTorch Dataset & DataLoader**
6. **Define ANN Model** with:
   - Input Layer → Hidden Layers → Output Layer
7. **Train Model** using `BCELoss` and `Adam` optimizer
8. **Validate & Evaluate** using accuracy and classification metrics
9. **Make Predictions** on new data

---

## 🧠 Model Architecture

