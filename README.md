# CreditWise Loan Approval System

An end-to-end Machine Learning project that predicts whether a loan application will be approved or rejected using classification algorithms.

---

## 📌 Project Overview

This project uses applicant financial and demographic data to build a supervised ML pipeline for loan approval prediction.

The complete workflow includes:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Preprocessing
- Model Training
- Model Evaluation

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🤖 Machine Learning Models Used

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes

---

## 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

| Model | Accuracy | Precision | Recall | F1 Score |
|---|---|---|---|---|
| Logistic Regression | 86.5% | 0.783 | 0.770 | 0.776 |
| KNN | 76.0% | 0.627 | 0.524 | 0.571 |
| Gaussian Naive Bayes | 86.5% | 0.803 | 0.737 | 0.769 |

---

## 📌 Business Understanding

In loan approval systems, False Positives and False Negatives are important:

- **False Positive (FP):** Loan approved for a risky applicant.
- **False Negative (FN):** Genuine applicant loan rejected.

The models were evaluated not only on accuracy but also on FP/FN trade-offs using the confusion matrix.

✅ **Gaussian Naive Bayes was selected as the best model because it produced the lowest False Positives while maintaining strong overall performance.**

---

## 📂 Dataset Features

The dataset contains features such as:

- Applicant Income
- Coapplicant Income
- Employment Status
- Credit Score
- Savings
- Loan Amount
- Property Area
- Education Level
- Loan Purpose
- Existing Loans
- And more...

### 🎯 Target Variable
`Loan_Approved`

---



## 📁 Project Structure

```bash
CreditWise-Loan-System/
│
├── credit_wise.ipynb
├── loan_approval_data.csv
├── README.md

```

---

## 🔮 Future Improvements

- Hyperparameter Tuning
- Cross Validation
- Streamlit/Flask Deployment
- Real-time Loan Prediction Interface

---
## 👩‍💻 Author

Dimple Saxena  
B.Tech Student | AI & ML Learner
