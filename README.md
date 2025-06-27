# Bank Customer Churn Prediction

A deep learning project to predict if a bank customer is likely to leave (“churn”), using pre-processing methods and a multilayer perceptron (MLP) model. Built in Python with a focus on interpretable results and real-world use cases.

---

## Project Overview

Many banks face revenue loss when clients close their accounts. By predicting churn early, banks can take proactive measures—like offering personalized deals or improving service—to retain customers  [oai_citation:0‡github.com](https://github.com/shahin-alipanahi/bank_customer_churn/tree/main?utm_source=chatgpt.com) [oai_citation:1‡researchgate.net](https://www.researchgate.net/publication/377232894_Bank_Customer_Churn_Prediction_with_Machine_Learning_Methods?utm_source=chatgpt.com) [oai_citation:2‡en.wikipedia.org](https://en.wikipedia.org/wiki/Customer_attrition?utm_source=chatgpt.com).

---

## Data

- Source: Kaggle “Predicting Churn for Bank Customers” (~10,000 records)
- Features include:
  - CreditScore,
  - Gender,
  - Age,
  - Tenure,
  - Balance,
  - NumOfProducts
  - HasCrCard
  - IsActiveMember
  - EstimatedSalary
- Target: Exited (0 = stayed, 1 = churned).  
- The model can predict whether a customer is likely to stay or leave the bank with over 86% of accuracy. 

---

## Tech Stack

-  Python (pandas, scikit‑learn)  
-  Jupyter notebooks for EDA & feature engineering  
-  Scikit‑learn pipelines for preprocessing (encoding, scaling)  
-  Models: multilayer perceptron (MLP) model
-  Feature importance & model comparison

---

## How to Run

```bash
git clone https://github.com/shahin-alipanahi/bank_customer_churn.git
cd bank_customer_churn

python -m venv env
source env/bin/activate        # or .\env\Scripts\activate on Windows
pip install -r requirements.txt

# To run EDA, feature engineering, and modeling
jupyter notebook
