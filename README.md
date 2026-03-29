# 🏦 Bank Customer Churn Analysis & Dashboard

> **Uncovering why 20% of bank customers leave — and what to do about it.**

![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Methodology](https://img.shields.io/badge/Methodology-CRISP--DM-0057A8?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![Domain](https://img.shields.io/badge/Domain-Banking%20%7C%20Customer%20Analytics-FF6B35?style=for-the-badge)

---

## 📌 Project Overview

This end-to-end data analytics project focuses on diagnosing and understanding **customer churn** within the banking sector. With a churn rate of **20% across 10,000 customers**, the bank faced a critical challenge: retaining financially stable, long-term clients who were actively moving their capital to competitors.

The analysis was conducted using the **CRISP-DM (Cross-Industry Standard Process for Data Mining)** methodology — moving beyond surface-level visualization into deep business understanding and strategic evaluation.

| Detail | Description |
|---|---|
| 👤 **Role** | Data Analyst |
| 🛠️ **Tools** | Microsoft Excel (Pivot Tables, Advanced Charting, Slicers, Custom Binning) |
| 📐 **Methodology** | CRISP-DM |
| 📦 **Dataset** | 10,000 bank customers |
| 🎯 **Deliverable** | Interactive Excel Dashboard + Business Recommendations |

---

## 🎯 Business Problem

> *"Why are our customers leaving, and how do we stop them?"*

The bank identified an urgent need to understand the **demographic, financial, and product-usage profiles** of churned customers. Preventing further capital outflow and optimizing retention budgets required moving past assumptions — and letting the data tell the real story.

---

## 📊 Dashboard Preview

![Dashboard Screenshot](Dashboard_Screenshot.png)

> *Interactive dashboard with dynamic Slicers filtering by Country, Gender, Credit Card Status, and more.*

---

## 🔍 Key Findings

### 🚨 1. The Product Cross-Selling Anomaly *(Critical Finding)*

| Products Held | Churn Rate |
|---|---|
| 1 Product | ~27% |
| 2 Products | **7.58%** ✅ |
| 3 Products | **82.71%** 🔴 |
| 4 Products | **100%** 🚨 |

Cross-selling to a **2nd product dramatically increases loyalty**. However, pushing customers beyond that point triggers catastrophic churn — indicating severe hidden fees, service friction, or forced bundling issues.

---

### 🌍 2. Geographic & Demographic Red Zones

- **Germany** churn rate: **32.44%** — nearly double France and Spain (~16%)
- Churn is dominated by the most financially stable age groups:
  - **45–59 years: 44.04% churn rate**
  - **30–44 years: 42.66% churn rate**

The customers leaving are not the bank's weakest — they are the most valuable.

---

### 💰 3. They Leave With Money

**75.45% of churned customers still had an active balance** at the time of exit.

This disproves the assumption that churn is driven by financial distress. Instead, these customers are **consciously and actively moving their capital to competitors**.

---

### 📉 4. The Inactive Customer Threat

- **Inactive customers contribute nearly 27% churn rate** — the highest of any engagement segment.
- Metrics like **Customer Tenure** and **Credit Card Ownership** showed flat churn distributions (~20%), proving that loyalty cannot be assumed based on seniority or product ownership alone.

---

## 💡 Actionable Recommendations

### 1. 🛑 Investigate Product 3 & 4 Services
Immediately **halt aggressive upselling campaigns** for the 3rd and 4th products. Conduct an internal audit to identify hidden fees or service bottlenecks causing extreme customer frustration. Refocus marketing energy on converting 1-product customers to 2 products.

### 2. 🔔 Automated Re-engagement Campaigns
Build a **CRM alert system** that automatically identifies and targets Inactive customers with personalized retention promos or cashback offers *before* they initiate capital transfers.

### 3. 🇩🇪 Targeted Retention Strategy in Germany
Launch a **Customer Satisfaction Survey** specifically targeting the 30–59 age demographic in Germany to identify which competitor offerings are driving attrition and improve local service quality.

---

## 📂 Repository Contents

```
📦 Bank-Customer-Churn-Analysis/
├── 📊 Bank_Customer_Churn_Dashboard.xlsx   # Main Excel file: raw data, prep, Pivot Tables & Dashboard
├── 🖼️  Dashboard_Screenshot.png            # High-resolution dashboard preview
├── 📄 Presentation_Script.txt              # Narrative script used for stakeholder presentation
└── 📝 README.md                            # Project documentation (this file)
```

---

## 🚀 How to Use the Dashboard

1. **Download** `Bank_Customer_Churn_Dashboard.xlsx` and open it in **Microsoft Excel** (2016 or later recommended).
2. Navigate to the **`Dashboard`** sheet.
3. Use the **interactive Slicers** at the top of the dashboard to filter by:
   - 🌍 Country
   - 👤 Gender
   - 💳 Credit Card Status
   - ✅ Active / Inactive Status
4. All **KPI Scorecards** and **Charts** will update dynamically based on your selections.

---

## 🧠 Methodology: CRISP-DM

```
Business Understanding  →  Identify churn problem and define business objectives
        ↓
Data Understanding      →  Explore 10,000 customer records across demographics & financials
        ↓
Data Preparation        →  Binning age groups, balance flags, product counts (Excel)
        ↓
Modeling / Analysis     →  Pivot Tables, cross-tabulations, KPI calculations
        ↓
Evaluation              →  Validate findings against business assumptions
        ↓
Deployment              →  Interactive Dashboard + Stakeholder Recommendations
```

---

## 🛠️ Technical Implementation (Excel)

- **Data Preparation:** Custom age binning, balance segmentation flags, derived churn ratio columns
- **Pivot Tables:** Multi-dimensional cross-tabulations for churn by geography, age, product count, and engagement
- **Advanced Charting:** Stacked bar charts, donut charts with conditional color gradients, KPI scorecards
- **Interactivity:** Dynamic Slicers connected to all charts for real-time dashboard filtering
- **Dashboard Layout:** Single-sheet master dashboard with structured zones (KPIs → Geography → Demographics → Financial → Engagement)

---

## 📈 Business Impact

| Metric | Value |
|---|---|
| Total Customers Analyzed | 10,000 |
| Churn Rate Identified | 20% (2,000 customers) |
| Avg. Customer Tenure (before churn) | ~5 years |
| Churned Customers with Active Balance | 75.45% |
| Highest-Risk Product Stage | 3 Products (82.71% churn) |
| Highest-Risk Geography | Germany (32.44% churn) |

---

## 👤 Author

**Irfan**
Data Analytics Portfolio Project

---

*This project was developed as part of an end-to-end data analytics portfolio, demonstrating skills in business problem framing, data preparation, exploratory analysis, dashboard design, and data storytelling.*
