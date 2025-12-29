# Credit Risk Analysis with Logistic Scoring Model

## 📌 Overview
This project focuses on **Credit Scoring**, a critical tool for financial institutions to evaluate the risk of loan default. Using the **German Credit Data (Statlog)** dataset, we built a supervised machine learning model based on **Logistic Regression** to classify clients as either solvent ("good payers") or risky ("bad payers").

This work was developed as a final year mini-project for the **Bachelor's Degree in Applied Mathematics** at Université Abderrahmane Mira de Béjaia.

## 📂 Dataset
The project utilizes the **Statlog (German Credit Data)** dataset, which includes **1000 observations** and **20 features** covering:
- **Personal Info:** Age, sex, marital status, housing.
- **Financial Info:** Job, income, credit amount, duration.
- **Banking History:** Saving accounts, checking account status.

## ⚙️ Methodology
The workflow was implemented in **Python** (Google Colab) following these steps:

1.  **Data Cleaning:** Imputation of missing values (Mode) and outlier detection (IQR method).
2.  **Preprocessing:** One-Hot Encoding for categorical variables and Standard Normalization (StandardScaler) for numerical features.
3.  **EDA:** Visualization of distributions and correlations using Matplotlib and Seaborn.
4.  **Modeling:** Training a Logistic Regression classifier on the processed data.

## 🚀 Results
The model achieved strong performance metrics, validating the effectiveness of the logistic approach:
- **Accuracy:** 92.48%
- **F1-Score:** 0.92
- **AUC (Area Under Curve):** 0.98

## 🛠️ Technologies Used
- **Python 3.x**
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.
- **Environment:** Google Colab / Jupyter Notebook.

## 👥 Authors
- **CHEBBOUT Rafik**
- **KAHLOUL Aziz**
- **DJOUADI Aymen**
- **BOURGHADEN Salah**

**Supervisor:** Mlle Z. CHIBANE
**University:** Université Abderrahmane Mira de Béjaia (2024 - 2025)
