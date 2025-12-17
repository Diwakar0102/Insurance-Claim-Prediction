# Insurance Claim Prediction 🚗📊

## 📌 Project Overview

This project focuses on **predicting whether an insurance policyholder will file a claim** using historical policy and customer data. The dataset is highly imbalanced, making it a realistic **industry-style classification problem**.

The goal is to build and compare multiple machine learning models while addressing class imbalance through **undersampling, oversampling, and SMOTE**, and finally identify the most effective approach based on evaluation metrics.

---

## 🧠 Problem Statement

Insurance companies face significant financial risk due to fraudulent or unexpected claims. Accurately predicting claim likelihood helps in:

* Risk assessment
* Pricing strategies
* Fraud prevention
* Operational cost reduction

This project aims to classify policyholders into:

* **Claimed**
* **Did Not Claim**

---

## 📂 Dataset Description

* The dataset contains anonymized policyholder and vehicle-related features
* Target variable: **Claim Status (Binary Classification)**
* Data challenge: **Severe class imbalance**

> Note: Due to anonymized feature names, business interpretation is limited, so the focus is on statistical and model-based analysis.

---

## 🔍 Exploratory & Statistical Analysis

* Basic data checks (null values, data types, shape)
* Target variable distribution analysis
* Feature distribution analysis using distplots
* Outlier detection and treatment using **IQR method**
* Statistical insights derived from feature behavior

---

## ⚙️ Data Preprocessing

* Outlier handling using IQR
* Feature scaling (where required)
* Handling class imbalance using:

  * **Oversampling**
  * **Undersampling**
  * **SMOTE (Synthetic Minority Over-sampling Technique)**

---

## 🤖 Machine Learning Models Implemented

Models were trained and evaluated under different sampling strategies:

### Without Sampling / Baseline

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost

### Oversampled Data

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost

### Undersampled Data

* Logistic Regression
* Random Forest

### SMOTE Data

* Logistic Regression
* Decision Tree
* XGBoost
* Sequential (Neural Network) Model

---

## 📊 Model Evaluation Metrics

Given the imbalanced nature of the data, model performance was evaluated using:

* Precision
* Recall
* F1-score
* Confusion Matrix
* Model comparison report

> Accuracy alone was avoided as a primary metric due to imbalance bias.

---

## 🏆 Key Outcomes & Conclusions

* Class imbalance significantly impacts model performance
* Sampling techniques greatly improved recall and F1-score
* **Tree-based and XGBoost models performed better than linear models**
* SMOTE-based models provided the best balance between precision and recall
* Model selection should depend on business priority (false positives vs false negatives)

---

## 🛠️ Tech Stack & Tools

* **Programming Language:** Python
* **Libraries:**

  * NumPy
  * Pandas
  * Matplotlib / Seaborn
  * Scikit-learn
  * XGBoost
  * Imbalanced-learn (SMOTE)
* **Environment:** Jupyter Notebook

---

## 📁 Project Structure

```
Insurance-Claim-Prediction/
│── Project_3-Insurance_Claim_Prediction-Project.ipynb
│── README.md
```

---

## 🚀 Future Improvements

* Hyperparameter tuning using GridSearchCV
* Feature selection and dimensionality reduction
* Model explainability using SHAP or feature importance
* Deployment using Flask or FastAPI

---

## 👤 Author

**Diwakar Kumar**
Aspiring Data Scientist | Data Analyst
🔗 [LinkedIn](https://www.linkedin.com/in/diwakar-kumar-data-scientist/)
💻 [GitHub](https://github.com/Diwakar0102)

---

⭐ If you find this project useful, feel free to star the repository!
