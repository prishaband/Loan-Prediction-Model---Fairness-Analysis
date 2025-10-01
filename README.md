# Loan Prediction Model

## 📌 Project Overview

This project develops a **predictive model for loan approvals** using home loan application data from Georgia. The dataset includes applicant demographics, loan type, income, loan amount, and outcomes (approved or denied). The objective is to build a **binary classification model** to predict whether a loan will be approved (`action_taken = 1`) or denied (`action_taken = 3`).

---

## 🎯 Objectives

* Understand factors influencing loan approvals.
* Build and evaluate a machine learning model to predict loan approval outcomes.
* Interpret feature importance for actionable insights.

---

## 📂 Dataset

* **Source:** Home loan application data (Georgia).
* **Key Features:**

  * Applicant attributes (income, ethnicity, sex, race).
  * Loan details (type, amount, lending institution).
  * **Target Variable:** `action_taken`

    * `1 = Approved (likely to repay)`
    * `3 = Denied (likely to default)`

---

## 🔧 Tools & Technologies

* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* **Model Used:** Random Forest Classifier

---

## 📊 Methodology

1. **Data Preprocessing**

   * Handling missing values.
   * Encoding categorical features.
   * Standardizing numeric features.

2. **Exploratory Data Analysis (EDA)**

   * Distribution of applicant demographics.
   * Relationship between income, loan amount, and approval outcomes.
   * Bias/fairness considerations in approvals.

3. **Model Building**

   * Random Forest Classifier for prediction.
   * Hyperparameter tuning for optimization.

4. **Evaluation Metrics**

   * Accuracy
   * Precision & Recall
   * Confusion Matrix

---

## ✅ Results

* The Random Forest model achieved strong accuracy in predicting approvals vs. denials.
* **Key predictors:** Income, Loan Amount, Lending Institution.
* Model highlights potential areas of bias in lending decisions.

---

## 📌 Future Improvements

* Apply **fairness-aware machine learning** techniques to mitigate bias.
* Experiment with other models (XGBoost, Logistic Regression).
* Deploy as a web app using **Flask/Streamlit** for interactive predictions.

---


## ✨ Author

**Prisha Bandyopadhyay**
Master’s Student in Data Science, Lehigh University
