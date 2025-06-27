# 🏦 Bank Customer Churn Prediction

A machine learning project to predict if a bank customer is likely to leave (“churn”), using logistic regression and random forest models. Built in Python with a focus on interpretable results and real-world use cases.

---

## 📊 Project Overview

Many banks face revenue loss when clients close their accounts. By predicting churn early, banks can take proactive measures—like offering personalized deals or improving service—to retain customers  [oai_citation:0‡github.com](https://github.com/shahin-alipanahi/bank_customer_churn/tree/main?utm_source=chatgpt.com) [oai_citation:1‡researchgate.net](https://www.researchgate.net/publication/377232894_Bank_Customer_Churn_Prediction_with_Machine_Learning_Methods?utm_source=chatgpt.com) [oai_citation:2‡en.wikipedia.org](https://en.wikipedia.org/wiki/Customer_attrition?utm_source=chatgpt.com).

---

## 🧠 Data

- Source: Kaggle “Predicting Churn for Bank Customers” (~10,000 records)
- Features include:
  - Demographics: Age, Gender, Geography
  - Financial: Credit Score, Balance, Estimated Salary
  - Engagement: Tenure, Number of Products, Card ownership, Active status  
- Target: Exited (0 = stayed, 1 = churned).  
- ~20% of customers have churned  [oai_citation:3‡github.com](https://github.com/Pranjal-Soni/Bank-Customer-Churn-Prediction/blob/main/README.md?utm_source=chatgpt.com) [oai_citation:4‡huggingface.co](https://huggingface.co/AnilKumarK2004/bank-customer-churn-prediction-gbclassifier?utm_source=chatgpt.com) [oai_citation:5‡researchgate.net](https://www.researchgate.net/publication/377232894_Bank_Customer_Churn_Prediction_with_Machine_Learning_Methods?utm_source=chatgpt.com).

---

## 🔧 Tech Stack

- 🐍 Python (pandas, scikit‑learn)  
- 💻 Jupyter notebooks for EDA & feature engineering  
- 🔁 Scikit‑learn pipelines for preprocessing (encoding, scaling)  
- 📈 Models: logistic regression & random forest (k‑fold cross‑validation)  
- 📖 Feature importance & model comparison

---

## 🚀 How to Run

```bash
git clone https://github.com/shahin-alipanahi/bank_customer_churn.git
cd bank_customer_churn

python -m venv env
source env/bin/activate        # or .\env\Scripts\activate on Windows
pip install -r requirements.txt

# To run EDA, feature engineering, and modeling
jupyter notebook
