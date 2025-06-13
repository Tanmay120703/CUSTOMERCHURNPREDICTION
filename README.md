
---

### ✅ 2. Customer Churn Prediction using ANN (Binary Classification)

```markdown
# 📉 Customer Churn Prediction using PyTorch

This project builds an Artificial Neural Network (ANN) using PyTorch to predict whether a **customer will churn or not**. It's a **binary classification** problem.

---

## 🗂️ Project Files

- `BinaryclassificationAnn(customer_churn_prediction).ipynb`: Full notebook with all code and outputs.
- `customer_churn.csv`: Dataset used (if any).
- `requirements.txt`: Python dependencies.

---

## 🧾 Objective

Predict whether a customer will **churn (leave the service)** based on features such as:
- Age
- Contract type
- Monthly charges
- Internet service
- Tenure
- Payment method

---

## ⚙️ Tech Stack

- **Language:** Python
- **Framework:** PyTorch
- **Preprocessing:** Scikit-learn (LabelEncoder, StandardScaler)
- **Evaluation:** Accuracy, Precision, Recall, F1-score

---

## 🔁 Pipeline Overview

1. **Load CSV Dataset**
2. **Label Encode Categorical Features**
3. **Standardize Numerical Features**
4. **Train-Test Split**
5. **Custom Dataset + DataLoader**
6. **ANN Architecture**:
   - Input → 128 → 64 → 1 (Sigmoid)
7. **Training Loop with Binary CrossEntropy**
8. **Validation Loop**
9. **Prediction on New Data**

---

## 📦 Installation

```bash
pip install -r requirements.txt
