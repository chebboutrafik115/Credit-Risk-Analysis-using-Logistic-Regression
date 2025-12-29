# Credit Risk Analysis with Logistic Scoring Model

## 📌 Overview
This project focuses on **Credit Scoring**, a critical tool for financial institutions to evaluate the risk of loan default. Using the **German Credit Data (Statlog)** dataset, we built a supervised machine learning model based on **Logistic Regression** to classify clients as either solvent ("good payers") or risky ("bad payers").

[cite_start]This work was presented as a mini-project for the completion of a **Bachelor's Degree (Licence) in Applied Mathematics** at Université Abderrahmane Mira de Béjaia[cite: 1].

## 📂 Dataset
[cite_start]The project uses the **Statlog (German Credit Data)** dataset from Kaggle, consisting of **1000 observations** and **20 features**[cite: 156, 157], including:
- **Personal Info:** Age, sex, marital status, housing.
- **Financial Info:** Job, income, credit amount, duration.
- **Banking History:** Saving accounts, checking account status.

## ⚙️ Methodology
[cite_start]The workflow was implemented in **Python** using **Google Colab** [cite: 152] and followed these key steps:

1.  **Data Cleaning:**
    - [cite_start]Imputation of missing values for categorical variables (`Saving accounts`, `Checking account`) using the mode[cite: 174, 175].
    - [cite_start]Outlier detection and removal for numerical variables (`Credit amount`, `Duration`) using the Interquartile Range (IQR) method[cite: 176, 177].

2.  **Preprocessing:**
    - [cite_start]**One-Hot Encoding** for categorical variables to convert them into binary indicators[cite: 183].
    - [cite_start]**Standard Normalization** (StandardScaler) for numerical variables to ensure consistent scaling[cite: 185].

3.  **Exploratory Data Analysis (EDA):**
    - Analysis of target variable distribution.
    - [cite_start]Correlation analysis and visualization using **Matplotlib** and **Seaborn**[cite: 148].

4.  **Modeling:**
    - [cite_start]Implementation of **Logistic Regression**, a robust linear classifier for binary classification problems[cite: 110, 151].
    - Splitting data into training and testing sets.

## 🚀 Results
The model was evaluated using a Confusion Matrix, Precision, Recall, F1-Score, and the ROC Curve.
- **Accuracy:** 92.48%
- **F1-Score:** 0.92
- **AUC (Area Under Curve):** 0.98

These results highlight the relevance of Logistic Regression as an interpretable and effective method for credit risk assessment.

## 🛠️ Technologies Used
- [cite_start]**Language:** Python 3.x [cite: 141]
- [cite_start]**Environment:** Google Colab [cite: 152]
- **Libraries:**
    - [cite_start]`Pandas` & `NumPy`: Data manipulation and numerical operations[cite: 145, 146].
    - [cite_start]`Matplotlib` & `Seaborn`: Data visualization[cite: 148].
    - [cite_start]`Scikit-learn`: Machine Learning modeling and evaluation[cite: 150].

## 👥 Authors
- **CHEBBOUT Rafik**
- **KAHLOUL Aziz**
- **DJOUADI Aymen**
- **BOURGHADEN Salah**

**Supervisor:** Mlle Z. CHIBANE

[cite_start]**University:** Université Abderrahmane Mira de Béjaia (2024 - 2025) [cite: 1]

## 📜 License
This project is for educational purposes.
