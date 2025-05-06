# Customer Churn Prediction Using ANN

This project focuses on predicting customer churn using an Artificial Neural Network (ANN). Churn prediction is crucial for businesses aiming to retain customers by identifying those likely to leave. Leveraging deep learning, this model learns complex patterns in customer behavior and demographics to predict churn with high accuracy.

## 📌 Project Highlights

* Implemented a fully connected ANN using TensorFlow/Keras (or PyTorch).
* Comprehensive data preprocessing: encoding, normalization, and feature selection.
* Trained on real-world customer data to predict churn outcomes.
* Evaluated using accuracy, precision, recall, F1-score, and confusion matrix.

## 🚀 Technologies Used

* Python
* TensorFlow / Keras (or PyTorch)
* Pandas, NumPy for data handling
* Scikit-learn for preprocessing and evaluation
* Matplotlib / Seaborn for visualization

## 📂 Dataset

The dataset includes customer information such as customer_id,	credit_score,	country,	gender,	age,	tenure,	balance,	products_number,	credit_card,	active_member and	estimated_salary. Each record is labeled with a binary churn indicator (1: churned, 0: retained). Dataset source: https://www.kaggle.com/datasets/gauravtopre/bank-customer-churn-dataset

## 🧠 Model Overview

The ANN architecture includes:

* Input layer corresponding to the number of features
* One or more hidden layers with ReLU activation
* Dropout layers to prevent overfitting
* Output layer with sigmoid activation for binary classification

## ✅ Results

The model successfully identifies potential churners, achieving a validation accuracy of 86%. Evaluation metrics and visualizations provide clear insights into the model’s performance and reliability.
