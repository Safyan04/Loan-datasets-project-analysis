# 🏦 Loan Data Analysis Project

This project is a complete data analysis on a Loan Dataset using Python (Pandas, Matplotlib, Seaborn) in Jupyter Notebook (VS Code). The goal is to understand the key factors that influence loan approval decisions.

---

## 📁 Dataset Source

* Dataset Name: **Loan Dataset**
* Source: [Kaggle](https://www.kaggle.com/datasets/ayushmanyashaswi/loan-dataset-easy-to-understand-yashaswi)

---

## 🔍 Objective

To analyze and extract insights from the loan data, such as:

* Which applicant types are more likely to get approved
* How income, education, marital status affect loan approval
* Clean, prepare, and transform data for possible future modeling

---

## 📊 Technologies Used

* **Python** (Pandas, NumPy)
* **Data Visualization:** Matplotlib, Seaborn
* **Jupyter Notebook (VS Code)**
* **Data Cleaning & Feature Engineering**
* **StandardScaler** for feature scaling

---

## 🧹 Steps Performed

1. **Data Loading**
2. **Initial Exploration**
3. **Missing Value Handling**
4. **Data Cleaning**
5. **Exploratory Data Analysis (EDA)**
6. **Feature Engineering**
7. **Feature Scaling**
8. **Final Insights**

---

## 📈 Key Insights

* Applicants with a **credit history** of 1 are more likely to get loans.
* **Married and graduate** applicants have higher approval rates.
* **Self-employed** applicants have slightly lower approval chances.
* **Total Income** is a better indicator than individual income columns.
* Log transformation helped normalize skewed income and loan amount distributions.

---

## 📈 Final Insights

Based on the analysis performed, we found:

* Applicants with a good credit history have significantly higher chances of loan approval.
* Total income (sum of applicant and co-applicant income) gives better insights than individual incomes.
* Married, educated, and male applicants tend to have higher loan approval rates.
* Log transformation helped reduce skewness in `LoanAmount` and `Total_Income`.

---

## 📎 Files Included

* `loan_data_analysis.ipynb` – Main notebook with code and insights
* `loan_data.csv` – Data File
* `README.md` – This project description

---

---

## 🙌 Author

* **Name:** Safyan
* **Tools Used:** VS Code, Jupyter Notebook
* **Profile:** [https://github.com/Safyan04](https://github.com/Safyan04)

---

## 📌 Note

This is a data analysis-only project. No machine learning models were used intentionally to keep the focus on insights and data understanding.
