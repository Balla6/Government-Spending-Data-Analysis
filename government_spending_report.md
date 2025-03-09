# Government Spending Data Analysis Report

## Executive Summary
This report presents an analysis of **government spending transactions** to identify key trends, visualize financial distributions, and detect anomalies using machine learning. The analysis was conducted using **Python, Power BI, and machine learning models**, with a focus on detecting unusual transactions and understanding budget allocations.

## Key Findings

### **1. Total Spending Overview**
- **Total Obligations Incurred:** $335.73 trillion
- **Total Budgetary Resources:** $461.81 trillion
- **Total Unobligated Balance:** $126.08 trillion

### **2. Top Agencies by Spending**
The highest-spending agencies in **December 2024** include:
- **Department of Defense**: $29.8 trillion
- **Department of Agriculture**: $18.0 trillion
- **Corps of Engineers - Civil Works**: $14.6 trillion

### **3. Top Programs by Spending**
The largest government-funded programs include:
- **Reimbursable Activities**: $14.1 trillion
- **Vaccines for Children Program**: $13.8 trillion
- **Undistributed Programs**: $7.8 trillion

### **4. Spending Breakdown by Budget Category**
- **Department of Defense - Military**: $118.3 trillion
- **Health Care Services**: $24.03 trillion
- **Pollution Control and Abatement**: $24.02 trillion

### **5. Anomalies & Outlier Detection**
- **11.85% of transactions were flagged as outliers**.
- The highest anomalies were detected in:
  - **Department of Defense**
  - **Department of Veterans Affairs**
  - **Department of Homeland Security**
- **Top programs with anomalies**: **Reimbursable Activities, Undistributed, and Unknown Programs**.

## Machine Learning Model Performance
- **Algorithm Used**: Random Forest Classifier
- **Train Accuracy**: 99.15%
- **Test Accuracy**: 98.76%
- **Key Features in Outlier Detection**:
  - **Obligations Incurred Balances**: 10.3%
  - **Total Budgetary Resources**: 7.8%
  - **Unobligated Balance**: 6.1%

## Power BI Dashboard Insights
The **interactive Power BI dashboard** visualizes:
- **Total spending and obligations** through KPIs.
- **Top agencies and programs by spending** using bar charts.
- **Outlier transactions** using pie charts and bar charts.

**View the Power BI Dashboard Here**:  
[Government Spending Dashboard](https://app.powerbi.com/groups/me/reports/353aaea2-288a-4a12-a846-71b48bdb8904/4f73d7e235ed83523939?experience=power-bi)

## Recommendations
Based on the analysis, the following actions are recommended:

1. **Investigate High Outlier Transactions**  
   - Departments with the most outliers, such as **Defense and Veterans Affairs**, should undergo a **detailed audit** to understand why these anomalies exist.  
   - Special focus should be placed on **reimbursable activities** and **undistributed funds** since they have a large share of flagged transactions.

2. **Optimize Budget Allocation**  
   - **Health care services and pollution control** are among the highest-funded areas. Policymakers should ensure that these funds are being used effectively.  
   - **Departments with large unobligated balances** should be analyzed to determine if funds can be reallocated to areas in greater need.

3. **Enhance Financial Oversight with Machine Learning**  
   - The **machine learning model successfully identified anomalies**, proving that AI can be integrated into **fraud detection** systems for government spending.  
   - Continuous monitoring should be implemented to flag transactions **before** they become an issue.

4. **Improve Data Transparency & Accessibility**  
   - Government agencies should **increase transparency** by making spending data easily available and categorized properly.  
   - Future spending reports should **include multi-year data** instead of just December 2024 to identify long-term trends.

## Conclusion
This analysis provides a comprehensive view of **government financial transactions**, helping policymakers monitor **spending trends** and detect **potential anomalies**. The **machine learning model** successfully identifies irregularities, while **Power BI dashboards** enhance the ability to explore data interactively.

---
