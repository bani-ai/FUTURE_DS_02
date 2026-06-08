# 📊 FUTURE_DS_02 — Customer Retention & Churn Analysis

<div align="center">

![Future Interns](https://img.shields.io/badge/Future%20Interns-Data%20Science%20%26%20Analytics-blue?style=for-the-badge)
![Task](https://img.shields.io/badge/Task-02-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.x-yellow?style=for-the-badge&logo=python)
![Plotly](https://img.shields.io/badge/Plotly-Interactive-blueviolet?style=for-the-badge)

</div>

---

## 🧾 Project Overview

This project is part of the **Future Interns – Data Science & Analytics Internship Program**.

Task 2 involves a comprehensive **Customer Retention & Churn Analysis** on a telecom subscription dataset — uncovering churn patterns, retention drivers, and delivering data-backed business recommendations.

---
## 📊 Dashboard Preview

<img width="2940" height="4092" alt="dashboard" src="https://github.com/user-attachments/assets/1d76ad08-c422-48ba-b24f-21854bdae9a6" />


The dashboard highlights customer churn patterns, retention trends, service insights, payment behavior, tenure analysis, and key business KPIs through interactive visualizations.


## 🎯 Objectives

| # | Objective |
|---|-----------|
| 1 | Analyze churn patterns across customer segments |
| 2 | Identify key drivers that lead to customer churn |
| 3 | Perform cohort-based retention analysis |
| 4 | Understand customer lifetime trends |
| 5 | Build an interactive Plotly analytics dashboard |
| 6 | Deliver actionable business recommendations |

---

## 📂 Repository Structure

```
FUTURE_DS_02/
│
├── dataset/
│   └── telecom_churn_data.csv        # Dataset (1,500 customers, 18 features)
│
├── notebook/
│   └── Analysis.ipynb                # Full EDA + statistical analysis
│
├── dashboard/
│   ├── Dashboard.ipynb               # Interactive Plotly dashboard
│   └── dashboard.png         # Dashboard screenshot
│
├── images/
│   └── *.png                         # Exported chart images
│
├── insights/
│   └── key_insights.md               # Business insights & recommendations
│
├── requirements.txt
└── README.md
```

---

## 🛠️ Technologies Used

| Tool | Purpose |
|------|---------|
| Python 3.x | Core programming |
| Pandas | Data cleaning & transformation |
| NumPy | Numerical operations |
| Matplotlib & Seaborn | Static visualizations |
| Plotly | Interactive dashboard |
| Jupyter Notebook | Development environment |

---

## 📁 Dataset Information

**Dataset:** Telecom Customer Churn | **Size:** 1,500 customers, 18 features

| Column | Description |
|--------|-------------|
| `Tenure_Months` | Subscription duration |
| `Contract` | Month-to-Month / One Year / Two Year |
| `MonthlyCharges` | Monthly billing amount |
| `InternetService` | Fiber Optic / DSL / No Internet |
| `PaymentMethod` | Payment type |
| `Churn` | 1 = Churned, 0 = Retained |
| `ChurnReason` | Reason for leaving |
| `CohortMonth` | Month of joining |

---

## 📈 Analysis Performed

- ✅ Data Cleaning & Preprocessing
- ✅ KPI Summary (Churn Rate, Revenue at Risk, Avg Tenure)
- ✅ Univariate & Bivariate Analysis
- ✅ Cohort Retention Analysis
- ✅ Churn Reasons Breakdown
- ✅ Correlation Heatmap
- ✅ Interactive Plotly Dashboard

---

## 💡 Key Insights

> 📌 **Month-to-Month customers churn ~45%** — 5x higher than Two Year contract holders.

> 📌 **First 6 months are the danger zone** — ~50% churn in early tenure.

> 📌 **Fiber Optic has a quality issue** — highest churn despite being premium.

> 📌 **Electronic Check users churn most** — auto-pay users are far more loyal.

> 📌 **Multi-product customers are sticky** — bundling reduces churn significantly.

---

## 🚀 Business Recommendations

| Priority | Action |
|----------|--------|
| 🔴 High | Incentivize Month-to-Month → Annual contract conversion |
| 🔴 High | 90-day structured onboarding for new customers |
| 🟡 Medium | Audit & improve Fiber Optic service quality |
| 🟡 Medium | Cashback for switching to auto-pay |
| 🟢 Low | Product bundle offers for single-product customers |
| 🟢 Low | Loyalty rewards at 24-month milestone |

---

## ▶️ How to Run

```bash
git clone https://github.com/yourusername/FUTURE_DS_02.git
cd FUTURE_DS_02
pip install -r requirements.txt
jupyter notebook notebook/Analysis.ipynb
jupyter notebook dashboard/Dashboard.ipynb
```

---

## 👩‍💻 Author

**Bani Priya**  
🎓 B.Tech in Artificial Intelligence

🏫 Delhi Skill and Entrepreneurship University (DSEU)



## ⭐ Acknowledgement

I sincerely thank FUTURE Interns for providing this opportunity to work on a real-world Customer Churn Analysis project. It enhanced my practical knowledge of data analytics, visualization, and business decision-making.

