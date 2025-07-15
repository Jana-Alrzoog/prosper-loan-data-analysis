
<h1 align="center">📊 Loan Data Analysis</h1>

<p align="center">Exploratory and Explanatory Data Visualization Project</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/8dbcbc7f-5356-4904-a586-a4b7c50cc25e" width="400"/>
</p>

## 📁 Project Overview

This project explores and analyzes data from **Prosper**, a peer-to-peer lending platform. The dataset contains information about loan applications, including borrower credit ratings, employment status, income range, loan status, and interest rates.

Our analysis aims to uncover insights about how various factors such as credit ratings, income levels, and employment status affect **Borrower APR (Annual Percentage Rate)** and **loan outcomes**.

---

## 🎯 Key Questions

1. **How does Prosper Rating affect the Borrower APR?**
2. **How does income level relate to loan status (Completed, Defaulted, etc.)?**
3. **Is there a relationship between employment status and APR?**

---

## 🧪 Dataset

* **Source:** [Prosper Loan Dataset](https://www.kaggle.com/)
* **File Used:** `prosperLoanData.csv`
* **Rows:** \~113,000 loans
* **Key Features:**

  * `BorrowerAPR`
  * `ProsperRating (Alpha)`
  * `LoanStatus`
  * `EmploymentStatus`
  * `IncomeRange`

---

## 📌 Tools Used

* Python (Pandas, Matplotlib, Seaborn)
* Jupyter Notebook
* Data Wrangling & Cleaning
* Exploratory Data Analysis (EDA)
* Explanatory Visualizations

---

## 📈 Visualizations

### 📌 1. Borrower APR vs Prosper Rating

📤 *Insight:* Higher Prosper Ratings are associated with lower APRs, reflecting better creditworthiness.

### 📌 2. Loan Status vs Income Range

📤 *Insight:* Loan completion is more common among middle to high-income groups. Defaults are more likely in low-income ranges.

### 📌 3. Borrower APR vs Employment Status

📤 *Insight:* Borrowers who are unemployed tend to have higher APRs, while full-time and retired individuals receive more favorable rates.

---

##  Conclusion

This analysis highlights how borrower characteristics significantly influence loan terms and outcomes. Platforms like Prosper appear to use credit rating and income as major indicators of risk.

---
