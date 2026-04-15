# loan-default-risk-analysis-powerbi
## 📥 Download Dashboard
The Power BI file is available in compressed format:[Download PBIX File](loan-default-dashboard.zip
# 📊 Loan Default Risk Analysis & Dashboard (Power BI)

## 🔍 Overview

This project analyzes loan default patterns using Power BI to identify high-risk customer segments and uncover financial trends. The dashboard enables data-driven decision-making through insights into loan distribution, customer demographics, and financial risk metrics.

---

## 🎯 Objectives

* Analyze loan default trends across multiple dimensions
* Identify high-risk customer segments
* Track year-over-year (YOY) changes in loan and default rates
* Provide actionable insights for financial risk management

---

## 📁 Dataset

* Source: Loan dataset (CSV format)
* Total Loan Amount: ₹32.58B+
* Features include:

  * Income, Employment Type
  * Credit Score
  * Age Group, Marital Status
  * Loan Purpose

---

## 🔄 Project Workflow

### 🔹 Data Collection

* Imported structured loan dataset containing financial and demographic attributes

### 🔹 Data Cleaning & Preprocessing

* Handled missing values and ensured data consistency
* Standardized categorical variables
* Converted data types for accurate analysis

### 🔹 Data Modeling

* Created derived columns:

  * Age Groups (Teen, Adults, Middle Age, Senior Citizens)
  * Income Brackets (Low, Medium, High)

### 🔹 DAX Calculations

* Built key measures:

  * Total Loan Amount
  * Default Rate (%)
  * Average Income
  * YOY Loan Change (%)
  * YOY Default Change (%)

---

## 📊 Dashboard Preview

### 🔹 Loan Overview

![Loan Overview](page1_overview.png)
### 🔹 Applicant Demographics

![Demographics](page2_demographics.png)
### 🔹 Financial Risk Metrics
![Risk Metrics](page3_risk_metrics.png)

---

## 📈 Key Insights

* Unemployed individuals have the highest default risk (~3.39%)
* High-income customers contribute the majority of loan volume (~₹21.73B)
* Default rates fluctuate over time indicating financial volatility
* Credit score significantly influences loan distribution

---

## 🛠 Tools & Technologies

* Power BI
* DAX
* Data Modeling
* Data Visualization

---

## 📂 Project Files

* Dataset: `/data/loan_default.csv`
* Dashboard: `loan-default-dashboard.pbix`
* Screenshots: `/images/`
* Report (PDF): `/reports/loan-default-dashboard-report.pdf`

---

## 🚀 Business Impact

This project helps financial institutions:

* Identify high-risk customers
* Optimize loan approval strategies
* Monitor default trends
* Improve data-driven decision-making

---

## 🔮 Future Improvements

* Add machine learning model for default prediction
* Integrate SQL database for real-time analysis
* Automate data pipeline

---

## 👤 Author

Brijesh Kumar
