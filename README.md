# 📊 Telecom Customer Churn Prediction  

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)  
![License](https://img.shields.io/badge/License-MIT-green)  
![Status](https://img.shields.io/badge/Status-Completed-success)  
![ML](https://img.shields.io/badge/Machine%20Learning-Logistic%20Regression-orange)  

---

## 📑 Table of Contents  
1. [Overview](#overview)  
2. [Dataset](#dataset)  
3. [Approach](#approach)  
4. [Models Used](#models-used)  
5. [Technologies](#technologies)  
6. [Results & Insights](#results--insights)  
7. [Future Work](#future-work)  
8. [How to Run](#how-to-run)  
9. [Project Structure](#project-structure)  

---

## 🔎 Overview  
This project explores telecom customer data to **analyze churn behavior** and build predictive models.  
The goal is to help telecom companies **reduce churn** by identifying key drivers and enabling **targeted retention strategies**.  

---

## 📂 Dataset  
**Source:** [Telco Customer Churn Dataset (Kaggle)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  

**Context:**  
- Predict customer churn based on demographics, services, and account information.  
- Enable businesses to implement data-driven retention programs.  

**Key Features:**  
- **Target Variable:** `Churn` (Yes/No – customer left within the last month)  
- **Services:** Phone, multiple lines, internet, online security, backup, device protection, streaming, tech support  
- **Account Info:** Tenure, contract type, payment method, monthly & total charges  
- **Demographics:** Gender, partner, dependents  

---

## ⚙️ Approach  
1. **Data Cleaning & Preprocessing**  
   - Handled missing values  
   - Encoded categorical features  
   - Normalized numerical values  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized churn distribution  
   - Correlation heatmaps  
   - Service usage patterns  

3. **Modeling**  
   - Logistic Regression for churn prediction  
   - Association Rule Mining using Apriori to find service bundling patterns  

4. **Evaluation**  
   - Accuracy, Precision, Recall, F1-score  
   - Confusion matrix visualization  

---

## 🤖 Models Used  
- Logistic Regression  
- Association Rule Mining  
- Apriori Algorithm  

---

## 🛠️ Technologies  
- **Python**  
- **Pandas**  
- **NumPy**  
- **Scikit-learn**  
- **Matplotlib**  
- **Seaborn**  

---

## 📈 Results & Insights  
✔ Logistic Regression showed balanced performance with good interpretability.  
✔ Customers with **month-to-month contracts** and **electronic payment methods** were most likely to churn.  
✔ Association rules revealed that customers with **online security** often subscribed to **tech support**.  

📊 *Sample Visualizations:*  
```markdown
![Churn Distribution](images/churn_distribution.png)  
![Confusion Matrix](images/confusion_matrix.png)  
