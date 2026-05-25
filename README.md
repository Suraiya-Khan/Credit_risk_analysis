# 💳 Credit Risk Analysis using Machine Learning

## 📌 Overview
This project focuses on **predicting credit risk** by analyzing customer financial and demographic data. It demonstrates skills in **data preprocessing, exploratory data analysis (EDA), feature engineering, and model building** for risk classification. The goal is to support financial institutions in making informed lending decisions.

## 📊 Dataset
- **Source:** [Specify dataset origin, e.g., Kaggle Credit Risk Dataset / Bank Loan Data]  
- **Features:** Customer demographics, income, loan amount, credit history, employment status, etc.  
- **Target:** Loan status (default vs. non-default)

## ⚙️ Methodology
1. **Exploratory Data Analysis (EDA)** – Identified patterns, correlations, and risk factors  
2. **Data Preprocessing** – Handled missing values, outliers, and categorical encoding  
3. **Feature Engineering** – Created risk-related features (e.g., debt-to-income ratio)  
4. **Model Training** – Algorithms tested: Logistic Regression, Random Forest, XGBoost  
5. **Evaluation** – Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC  

## 📈 Results
- Best performing model: **XGBoost** (Accuracy: 87%, ROC-AUC: 0.91)  
- Key insight: Credit history and debt-to-income ratio were the strongest predictors  

## 🛠️ Tech Stack
- **Python**  
- **Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn**  

## 💡 Use Cases
- Helps banks and financial institutions assess loan applicants  
- Reduces risk of defaults by identifying high-risk customers  
- Educational resource for ML in finance  
pip install -r requirements.txt
python main.py
