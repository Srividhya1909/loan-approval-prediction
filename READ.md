# Loan Approval Prediction

## Overview
The Loan Approval Prediction project is a Machine Learning application that predicts whether a loan application will be approved based on applicant information. The project compares the performance of two classification algorithms and deploys the best-performing model for prediction.

---

## Features
- Data preprocessing and cleaning
- Encoding categorical variables
- Train-test split
- Model training using multiple algorithms
- Model evaluation using classification metrics
- Comparison of model performance
- Deployment of the best-performing model

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib/Pickle
- Streamlit (or Flask, if you used Flask)

---

## Dataset
The dataset contains applicant information such as:
- Person Income
- Home Ownership
- Loan Intent
- Loan Amount
- Previous Loan Default Status

**Target Variable:**
- Loan Status
  - 0 → Loan Not Approved
  - 1 → Loan Approved

---

## Machine Learning Algorithms Used

### 1. Logistic Regression
Logistic Regression was trained as a baseline classification model to predict loan approval.

### 2. Decision Tree Classifier
A Decision Tree Classifier was trained and compared with Logistic Regression. It achieved better performance and was selected as the final model for deployment.

---

## Data Preprocessing
- Removed unnecessary columns (if applicable)
- Encoded categorical features into numerical values
- Split the dataset into training and testing sets
- Trained the models using the processed dataset

---

## Model Evaluation
The models were evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

After comparing both models, the **Decision Tree Classifier** was selected as the final model for deployment.

---

## Deployment
The trained Decision Tree model was saved and deployed to predict loan approval for new applicants.

Users can enter applicant details, and the application predicts whether the loan is likely to be approved.

---

## Project Structure

```
Loan-Approval-Prediction/
│
├── dataset/
│   └── loan_data.csv
│
├── model/
│   ├── decision_tree_model.pkl
│
├── app.py
├── loan_approval_prediction.ipynb
├── requirements.txt
└── README.md
```

---

## Future Improvements
- Hyperparameter tuning
- Cross-validation
- Feature engineering
- Random Forest and XGBoost implementation
- Cloud deployment

---

## Author

**Srividhya S**

B.Sc. Computer Science with Artificial Intelligence

Aspiring AI & Data Science Engineer
