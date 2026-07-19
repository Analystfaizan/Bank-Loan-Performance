# 🏦 Bank Loan Performance Dashboard

### Power BI | DAX | Power Query | Star Schema Data Modeling

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://github.com/Analystfaizan)
[![DAX](https://img.shields.io/badge/DAX-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://github.com/Analystfaizan)
[![Power Query](https://img.shields.io/badge/Power%20Query-blue?style=for-the-badge)](https://github.com/Analystfaizan)
[![Data Modeling](https://img.shields.io/badge/Data%20Modeling-Star%20Schema-orange?style=for-the-badge)](https://github.com/Analystfaizan)

> An end-to-end Power BI case study analyzing an **82,000-customer loan portfolio worth ₹991Bn**, built to help financial stakeholders assess credit risk, monitor portfolio health, and drive faster, data-backed lending decisions.

---

## 📌 Table of Contents
- [Overview](#-overview)
- [Business Problem](#-business-problem)
- [Tools & Technologies](#-tools--technologies)
- [Dataset](#-dataset)
- [Data Modeling — Star Schema](#-data-modeling--star-schema)
- [Report Structure](#-report-structure-3-page-power-bi-report)
- [Key DAX Measures](#-key-dax-measures)
- [Key Insights & KPIs](#-key-insights--kpis)
- [Dashboard Preview](#-dashboard-preview)
- [Skills Demonstrated](#-skills-demonstrated)
- [How to Use This Report](#-how-to-use-this-report)
- [Repository Structure](#-repository-structure)
- [About the Author](#-about-the-author)

---

## 🔍 Overview

This case study simulates a real-world **banking analytics engagement**, where the goal is to give credit risk teams and portfolio managers a single source of truth for evaluating loan performance. The final deliverable is a **3-page interactive Power BI report** — Executive Summary, Customer Credit Analysis, and Risk Analysis — designed with an app-like navigation experience using bookmarks, drillthrough pages, and custom tooltips.

The project demonstrates the full analytics workflow: **data cleaning → data modeling → DAX-based calculation → visualization → business storytelling.**

---

## 🎯 Business Problem

Banks and lending institutions need continuous visibility into their loan portfolios to:
- Identify high-risk customer segments before defaults occur
- Track credit utilization and debt exposure across the customer base
- Understand how loan purpose, ownership status, and loan term affect risk
- Give leadership a fast, digestible view of portfolio health without digging through raw data

This dashboard was built to answer: **"How healthy is our loan portfolio, and where is our risk concentrated?"**

---

## 🛠 Tools & Technologies

| Category | Tools Used |
|---|---|
| Visualization & Reporting | Power BI |
| Data Transformation | Power Query |
| Calculations & Metrics | DAX (Data Analysis Expressions) |
| Data Modeling | Star Schema |
| Advanced Features | Drillthrough Pages, Bookmarks, Tooltip Pages, Slicers |

---

## 📊 Dataset

- **Portfolio size:** 82,000 customers
- **Total loan value:** ₹991 Billion
- **Data prep:** Cleaned and shaped using Power Query for optimized load performance and consistent reporting logic

---

## 🧩 Data Modeling — Star Schema

A **Star Schema** was implemented to ensure the model was optimized, scalable, and fast to query — separating fact data (loan transactions, credit metrics) from dimension tables (customer attributes, loan purpose, ownership, term, risk category). This structure directly improved report performance and simplified DAX measure creation.

---

## 📑 Report Structure (3-Page Power BI Report)

### 1️⃣ Executive Summary
A high-level overview of portfolio size, total value, and top-line KPIs for leadership at a glance.

### 2️⃣ Customer Credit Analysis
Deep dive into customer credit health — credit score distribution, income vs. loan amount, and open account behavior.

### 3️⃣ Risk Analysis
Segments and flags high-risk customers using risk category, credit utilization, and credit problem indicators.

**Interactive elements across all pages:**
- 🎚️ Slicers: Ownership, Purpose, Term, Risk Category
- 🔎 Drillthrough pages for record-level detail
- 💬 Custom tooltip pages for contextual insights on hover
- 🧭 Bookmarks + navigation buttons for a seamless, app-like user experience

---

## 🧮 Key DAX Measures

Custom DAX measures were built to power the report's core metrics:

- **Average Credit Score:** `925.73`
- **Average Monthly Debt**
- **Credit Utilization Rate**
- **Total Credit Problems:** `13,000` flagged across the customer base

These measures enabled real-time, dynamic recalculation as users filtered the report by ownership, purpose, term, or risk category.

---

## 💡 Key Insights & KPIs

| Metric | Value |
|---|---|
| Total Customers | 82,000 |
| Total Loan Portfolio Value | ₹991 Billion |
| Average Credit Score | 925.73 |
| Total Credit Problems Flagged | 13,000 |
| Report Pages | 3 (Executive Summary, Credit Analysis, Risk Analysis) |
| Data Model | Star Schema |

**Key visuals built:**
- 📈 Credit Score Distribution
- 💰 Income vs. Loan Amount
- 🏦 Open Account Analysis

These visuals allow stakeholders to instantly identify credit risk patterns and drill down into specific customer segments without needing SQL or manual Excel analysis.

---

## 🖼 Dashboard Preview

  ![executive Summary](https://github.com/Analystfaizan/demo/blob/e423203f38752ff990b9537736eeb11c19943773/Executive%20Summary.png)
  ![Customer Analysis](https://github.com/Analystfaizan/demo/blob/6a3e782532fbefd1588f6e623cf268f6e798076a/Customer%20Credit%20Analysis.png)
  ![Risk Analysis](https://github.com/Analystfaizan/demo/blob/5a231f05924c059bf29aaaf957c65e7c39c1e579/Risk%20Analysis.png)
  
```
/screenshots
  ├── executive_summary.png
  ├── customer_credit_analysis.png
  └── risk_analysis.png
```

---

## 🧠 Skills Demonstrated

- Power BI report design & multi-page navigation (Bookmarks, Drillthrough, Tooltips)
- DAX measure creation for financial/credit KPIs
- Power Query data cleaning & transformation
- Star Schema data modeling for performance optimization
- Business insight generation for risk & credit analytics
- Stakeholder-focused dashboard storytelling

---

## ▶️ How to Use This Report

1. Clone or download this repository
2. Open the `.pbix` file in **Power BI Desktop**
3. Use the slicers (Ownership, Purpose, Term, Risk Category) to filter the portfolio
4. Right-click any visual to explore **Drillthrough** for record-level detail
5. Navigate between pages using the in-report **bookmark navigation buttons**

---

## 📁 Repository Structure

```
Bank Loan Performance/
│
├── Dahboard/                          # Power BI report file
├── Source data/                       # Source/cleaned dataset (if shareable)
├── screenshots/                       # Dashboard preview images
└── README.md                          # Project documentation
```


---

## 👤 About the Author

**Syed Faizan**
Data Analyst | SQL • Power BI • DAX • Excel • Data Visualization

- 📧 Email: sdfaizan3126@gmail.com
- 💻 GitHub: [github.com/Analystfaizan](https://github.com/Analystfaizan)
- 📱 Mobile: +91 8483833126

> Data-driven Computer Science graduate passionate about turning raw data into actionable business insight through dashboards, DAX-based analysis, and exploratory data analysis (EDA).

⭐ **If you found this project useful or interesting, consider starring the repo!**
