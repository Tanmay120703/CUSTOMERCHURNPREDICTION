# CUSTOMERCHURNPREDICTION

# 🔄 Customer Churn Prediction using Artificial Neural Network (ANN)

This project implements a **Binary Classification** model using **PyTorch** to predict whether a customer will churn or not. The model is built using an Artificial Neural Network (ANN), and the pipeline includes data preprocessing, training, evaluation, and prediction steps.

---

## 📁 Project File

- `BinaryclassificationAnn(customer_churn_prediction).ipynb`: Jupyter notebook containing all code from preprocessing to model evaluation and prediction.

---

## ✅ Features

- End-to-end binary classification pipeline
- Custom PyTorch Dataset and DataLoader
- Fully connected feed-forward neural network (ANN)
- Uses `BCEWithLogitsLoss` for binary classification
- Tracks accuracy and loss during training and validation
- Easily customizable for any binary classification dataset

---

## 🧠 Model Architecture

Input Layer: based on input features (preprocessed)

Hidden Layers: Linear → BatchNorm → ReLU → Dropout

Output Layer: Single neuron (Sigmoid or BCEWithLogitsLoss)
