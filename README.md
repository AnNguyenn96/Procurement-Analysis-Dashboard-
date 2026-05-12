# 📊 Procurement KPI Analysis Dashboard  

## 📑 Table of Contents

* 📊 [Dataset Overview](#-dataset-overview)
* ❓ [Problem Statement](#-problem-statement)
* 🧰 [Tech Stack](#-tech-stack)
* 📐 [Metric Logic](#-metric-logic)
* 📊 [Dashboard Pages](#-dashboard-pages)
* 🔍 [Key Findings](#-key-findings)
* 🚀 [Recommendations](#-recommendations)

This table of contents is based on your Procurement KPI Analysis Dashboard README structure. 

## 📊 Dataset Overview

This dataset contains 777 procurement transaction records capturing purchase order activities across multiple suppliers and categories.

It includes key information such as order dates, delivery dates, supplier details, item categories, pricing, quantities, defective units, and compliance status, enabling analysis of procurement performance and efficiency.

The dataset supports evaluation of spending behavior, supplier reliability, delivery performance, and quality issues, which are critical factors in optimizing procurement operations.

---
## ❓ Problem Statement

This project aims to answer the following key business questions:

- How has procurement spending changed over time?
- Which suppliers and categories contribute the most to total spend?
- How do suppliers perform in terms of lead time and delivery efficiency?
- Where are quality issues occurring, particularly in terms of defective units?
- Which suppliers provide the best balance between cost, quality, and delivery performance?


## 🧰 Tech Stack  

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=Microsoft-Excel&logoColor=white)
![Data Modeling](https://img.shields.io/badge/Data%20Modeling-FF6F00?style=for-the-badge)
![KPI Design](https://img.shields.io/badge/KPI%20Design-6A1B9A?style=for-the-badge)

---
## 📐 Metric Logic  

| Metric | Definition | Business Meaning |
|-------|-----------|----------------|
| Total Spend | Sum of all procurement costs | Reflects overall business activity and purchasing volume |
| Defect Rate | Number of defective orders / Total orders | Measures product quality and supplier reliability |
| Defective Cost | Total cost associated with defective items | Indicates financial loss due to quality issues |
| Net Saving | Total cost savings after accounting for defects | Shows actual efficiency of procurement |
| Delivered Rate | Number of successfully delivered orders / Total orders | Measures delivery reliability |
| Lead Time | Difference between order date and delivery date | Indicates speed of supplier fulfillment |

## 📊 Dashboard Pages  

### 🔹 Executive Overview  
- Monitors overall procurement performance  
- Tracks KPIs:
  - Total Spend  
  - Defect Rate  
  - Net Saving  
  - Delivered Rate  
- Analyzes:
  - Spend trend over time  
  - Cost Saving vs Defect Cost  
  - Spend distribution by supplier and category  

👉 Purpose:  
Provide a **strategic view** of procurement efficiency  

---

### 🔹 Supplier Performance  
- Focuses on individual supplier analysis  
- Tracks:
  - Lead Time  
  - Delivery Performance  
  - Order Status  
  - Spend vs Cost Saving  

👉 Design:
- Analyzes **one supplier at a time** for clarity  
- Supports drill-down from overview  

👉 Purpose:  
Evaluate **supplier-level performance for decision-making**

---

## 🔍 Key Findings  

📌 Executive Summary

This analysis evaluates procurement performance across cost, quality, and delivery dimensions. While total spend and cost savings have increased, supplier-level inefficiencies—particularly high defect costs and inconsistent compliance—highlight opportunities for optimization. A key finding is that Delta_Logistics significantly impacts defect cost despite moderate spend, indicating deeper quality and process issues.

📊 Business Insights

<img width="1296" height="689" alt="{ADB58663-C46D-48C5-8C1A-2550884E8399}" src="https://github.com/user-attachments/assets/d13af35e-42c0-4739-8466-a8c5707bbc4a" />

### 1. Procurement Spending Trend
Total spend reached $25.8M (+10.77% YoY)
Significant monthly fluctuations, with peaks in March and November

👉 Procurement demand is not stable, which may impact supplier efficiency and planning.

### 2. Spend Concentration
Top suppliers:
Beta_Supplies ($6.13M)
Epsilon_Group ($5.84M)
Top categories:
MRO, Raw Materials, Electronics

👉 High dependency on a few suppliers increases operational risk.


<img width="1200" height="600" alt="{B7839139-C795-43EB-92A4-563498D4A7A9}" src="https://github.com/user-attachments/assets/93dabc71-02c3-400b-9cde-cc23c200dc0b" />

### 3. Supplier Performance
Average lead time: ~9.9 days
Delivered rate: 81.79%
Only 12.9% delivered within 3 days

👉 Delivery efficiency is moderate but not optimized, especially for urgent demand.

### 4. Quality & Defect Cost
Total defect cost: $1.33M (+8.91% YoY)
Delta_Logistics has the highest defect cost (~$534K)
Lowest compliance: ~60.82%

👉 Defect issues are supplier-specific, not just driven by volume.

### 5. Supplier Comparison (Cost vs Quality vs Delivery)
Best performers:
Epsilon_Group, Alpha_Inc → high compliance, low defect
Worst performer:
Delta_Logistics → high defect, low compliance

👉 There is a clear imbalance between cost savings and quality performance.

### 🚀 Recommendations

| Area                                       | Issue Identified                                          | Recommendation                                                                    | Expected Impact                                 |
| ------------------------------------------ | --------------------------------------------------------- | --------------------------------------------------------------------------------- | ----------------------------------------------- |
| **Supplier Performance (Delta_Logistics)** | Highest defect cost (~$534K), lowest compliance (~60.82%) | Conduct root cause analysis, enforce KPI/SLA, reduce dependency if no improvement | Reduce defect cost, improve quality consistency |
| **Spend Allocation**                       | Over-reliance on a few suppliers                          | Reallocate spend to high-performing suppliers (Epsilon_Group, Alpha_Inc)          | Better quality without increasing total cost    |
| **Delivery Efficiency**                    | Only 12.9% delivered within 3 days                        | Introduce SLA-based delivery targets and segment suppliers by speed vs cost       | Faster delivery, improved responsiveness        |
| **Procurement Planning**                   | High monthly spend fluctuation                            | Implement demand forecasting and stabilize procurement cycles                     | Better supplier planning, reduced rush orders   |
| **Supplier Monitoring**                    | Lack of performance-driven tracking                       | Track compliance, defect cost, and lead time variability                          | Shift toward performance-based procurement      |
| **Category Optimization**                  | High spend in MRO & Raw Materials                         | Audit suppliers and renegotiate contracts in key categories                       | Cost optimization in high-impact areas          |

---

