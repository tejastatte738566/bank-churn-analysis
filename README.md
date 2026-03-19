# 🏦 Bank Customer Churn Analysis

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=flat&logo=python)
![SQL](https://img.shields.io/badge/SQL-SQLite-orange?style=flat&logo=sqlite)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?style=flat&logo=pandas)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat)

## 📌 Project Overview

Is project mein ek bank ke **10,000 customers** ka data analyze kiya gaya hai.  
Main question yeh tha — **"Kaunse customers bank chhod rahe hain aur kyun?"**

SQL aur Python dono ka use karke deep analysis ki gayi hai aur business recommendations diye gaye hain.

---

## 🎯 Objective

- Overall churn rate nikalna
- Country, Gender, Age group ke basis pe churn pattern samajhna
- High risk customers identify karna
- Business ke liye actionable insights dena

---

## 🛠️ Tools & Technologies

| Tool | Use |
|---|---|
| Python | Data analysis aur visualization |
| Pandas | Data manipulation |
| SQL (SQLite) | Business queries |
| Matplotlib | Charts aur graphs |
| Seaborn | Advanced visualizations |
| Google Colab | Development environment |

---

## 📂 Project Structure

```
bank-churn-analysis/
│
├── Bank_Customer_Churn_Analysis.ipynb   # Main notebook
├── README.md                            # Project description
└── images/                              # Charts
    ├── churn_overview.png
    ├── churn_demographics.png
    ├── churn_financial.png
    ├── churn_products.png
    └── churn_correlation.png
```

---

## 📊 Key Findings

| Finding | Result |
|---|---|
| Overall Churn Rate | ~20% customers ne bank chhoda |
| Highest Churn Country | Germany (40%+ churn rate) |
| High Risk Gender | Female customers zyada churn karti hain |
| High Risk Age | 46-55 age group sabse zyada churn karta hai |
| Product Risk | 3-4 products wale customers = highest churn |
| Activity | Inactive members = 2x zyada churn |

---

## 📈 Visualizations

### 1. Overall Churn Distribution
![Churn Overview](images/churn_overview.png)

### 2. Demographics Analysis
![Demographics](images/churn_demographics.png)

### 3. Financial Profile
![Financial](images/churn_financial.png)

### 4. Products & Activity Impact
![Products](images/churn_products.png)

### 5. Correlation Heatmap
![Correlation](images/churn_correlation.png)

---

## 🗃️ SQL Queries Used

```sql
-- Example: Country wise churn rate
SELECT
    Geography,
    COUNT(*) AS Total_Customers,
    SUM(Exited) AS Churned,
    ROUND(AVG(Exited)*100, 2) AS Churn_Rate_Pct
FROM customers
GROUP BY Geography
ORDER BY Churn_Rate_Pct DESC;
```

---

## 💡 Business Recommendations

1. **Germany pe focus karo** — sabse zyada churn, targeted retention campaigns chalao
2. **Older customers** (46-55+) ke liye special loyalty offers banao
3. **Inactive members** ko re-engage karo — monthly engagement emails bhejo
4. **3-4 products** wale customers pe nazar rakho — wo sabse zyada risk mein hain
5. **High balance churners** ko personal relationship manager assign karo

---

## 🚀 How to Run

1. Google Colab kholo: [colab.research.google.com](https://colab.research.google.com)
2. `Bank_Customer_Churn_Analysis.ipynb` upload karo
3. **Runtime → Run All** click karo
4. Dataset automatically generate hoga — kuch download karne ki zaroorat nahi!

---

## 👤 About Me


**Tejas Tatte** — Aspiring Data Analyst  
📧 Email: tejastatte97@gmail.com  
💼 LinkedIn: [linkedin.com/in/tejas-tatte](https://linkedin.com/in/tejas-tatte)  
🐙 GitHub: [github.com/tejastatte738566](https://github.com/tejastatte738566)

---

> ⭐ Agar yeh project helpful laga toh **Star** zaroor karo!

