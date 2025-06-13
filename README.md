# 🔄 Customer Churn Prediction using PyTorch

This project builds an Artificial Neural Network (ANN) using PyTorch to predict whether a customer will **churn** or not based on features such as contract type, monthly charges, tenure, etc. It is a **binary classification** problem.

---

## 🗂️ Project Files

- `BinaryclassificationAnn(customer_churn_prediction).ipynb`: Main notebook containing data preprocessing, model training, evaluation, and predictions.
- `requirements.txt`: List of required libraries.
- `customer_churn.csv`: (Assumed input dataset)
- `README.md`: Documentation for setup and understanding the project.

---

## 🧾 Objective

To predict if a customer is likely to **churn** (i.e., discontinue the service), based on features like:

- Tenure
- Monthly and Total Charges
- Type of Contract
- Internet and Streaming Services
- Customer Support History
- Demographic Details

---

## ⚙️ Tech Stack

- **Language:** Python
- **Framework:** PyTorch
- **Data Handling:** Pandas, NumPy
- **Preprocessing:** Scikit-learn (Label Encoding, StandardScaler)
- **Evaluation:** Accuracy, Precision, Recall, F1 Score, Confusion Matrix

---

## 🔁 Pipeline Overview

1. **Data Loading**: Load customer churn dataset using pandas.
2. **Preprocessing**:
   - Convert categorical columns using LabelEncoder / OneHotEncoder
   - Handle missing values
3. **Train-Test Split** (80/20)
4. **Feature Scaling** using `StandardScaler`
5. **Dataset & DataLoader**:
   - Custom `Dataset` class
   - PyTorch `DataLoader` for batching
6. **Model Architecture**:
   - Input → Hidden Layers (ReLU, Dropout, BatchNorm) → Output (Sigmoid)
7. **Training Loop**:
   - Forward pass, compute `BCELoss`
   - Backpropagation and optimization with `Adam`
8. **Validation Loop**:
   - Accuracy and loss tracking
   - Convert predictions using sigmoid threshold
9. **Evaluation**:
   - Classification Report
   - Confusion Matrix
10. **Inference**:
   - Predict churn on new customer data

---

## 🧠 Model Structure

```text
Input → Linear(128) → ReLU → Dropout
      → Linear(64) → ReLU → Dropout
      → Linear(1) → Sigmoid
