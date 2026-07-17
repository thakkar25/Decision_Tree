# 🌳 Decision Tree Classification

## 📖 Overview

This project demonstrates the implementation of the Decision Tree Classification algorithm using Python and Scikit-learn.

The model predicts a student's grade based on academic performance using multiple input features.

---

# 📚 What is a Decision Tree?

A Decision Tree is a Supervised Machine Learning algorithm used for both Classification and Regression problems.

It works by splitting the dataset into smaller groups based on the feature that gives the highest Information Gain (or lowest impurity). The result is a tree-like structure where each internal node represents a decision and each leaf node represents the final prediction.

---

# 🎯 Objective

Predict the student's grade using academic performance.

---

# 📂 Dataset

student_ml_dataset.csv

### Features

- Weekly Self Study Hours
- Attendance Percentage
- Class Participation
- Previous Score
- Total Score

### Target

- Grade (A, B, C, D)

---

# ⚙️ Technologies Used

- Python
- Pandas
- Matplotlib
- Scikit-learn

---

# 🔄 Workflow

1. Load Dataset
2. Select Features and Target
3. Split Dataset into Training and Testing
4. Train Decision Tree Model
5. Predict Test Data
6. Calculate Accuracy
7. Generate Classification Report
8. Visualize Decision Tree
9. Predict New Student Grade

---

# 🌳 Decision Tree Parameters

- Criterion = Entropy
- Max Depth = 8
- Min Samples Split = 2
- Random State = 42

---

# 📈 Outputs

- Accuracy Score
- Classification Report
- Decision Tree Visualization
- Predicted Grade

---

# 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score

---

# 🌍 Real World Applications

- Student Grade Prediction
- Loan Approval
- Medical Diagnosis
- Fraud Detection
- Customer Segmentation
- Employee Performance Evaluation
- Credit Risk Analysis

---

# ✅ Advantages

- Easy to understand
- Easy to visualize
- Handles numerical and categorical data
- No feature scaling required
- Fast prediction

---

# ❌ Disadvantages

- Can overfit small datasets
- Sensitive to noisy data
- Small data changes can generate different trees

---
