# 📊 HR Dashboard Data Analysis using Excel
![LOGO](https://github.com/analyticsaq/HR_DashBoard_Excel/blob/main/Logo.jpg)

## 📌 Overview

This project involves a comprehensive analysis of HR Dashboard dataset using Excel. The goal is to extract actionable insights and answer KPIs related to Total Active Employees, Active by Ethnicity, Average Tenure Months, Actives by Region, Separations, Termination Reasons and more.

This README outlines the project’s objectives, KPIs, Excel Approach, and key findings.

---

## 🎯 Objectives

- Data Cleaning for Analyzing and Visualization using Excel
- Choosing KPI for available data.
- Visualization for the KPI defined.

---

## 📁 Dataset

- Source: HR Dashboard Files: https://www.myonlinetraininghub.com/workbook-downloads
- Format: CSV
- Cleaned and structured into a Excel

---

## 🧱 Cleaning

```
-Cleaning the TermDate COLUMNS values using CLEAR ALL FILTER where row was blank.
-Majority of the Data was already cleaned.
-Created 6 Calculated Measures in Data Models named EmpCount, Active Employees, New Hire, Average Tenure, Seperations,TO%.

```

---

## 🧠 KPIs

### 1️⃣ Total Active Employees

```
-Pivot Table
	Rows: Date(Year), Date(Quarters)
	Values: New Hire, Active Emoloyees
-Pivot Chart
	Choose Column Chart

```
![KPI1](https://github.com/analyticsaq/HR_DashBoard_Excel/blob/main/KPI1.png)

---

### 2️⃣ Active by Ethnicity

```
-Pivot Table
	Rows: EthnicGroup, Gender
	Values: Active Employees
    Legend: FP
-Pivot Chart
	Choose Column Chart

```
![KPI2](https://github.com/analyticsaq/HR_DashBoard_Excel/blob/main/KPI2.png)

---

### 3️⃣ Average Tenure Months

```
	Rows: EthnicGroup, Gender
	Values: Average Tenure
    Legend: FP
-Pivot Chart
	Choose Column Chart

```
![KPI3](https://github.com/analyticsaq/HR_DashBoard_Excel/blob/main/KPI3.png)

---

### 4️⃣ Active by Region

```
-Pivot Table
	Rows: BU Region
	Values: Active Employees
    Legend: FP
-Pivot Chart
	Choose Bar Chart

```
![KPI4](https://github.com/analyticsaq/HR_DashBoard_Excel/blob/main/KPI4.png)
---

### 5️⃣ Termination Reason

```
-Pivot Table
	Rows: Date(Year)
	Values:  Count of TermReason
    Legend: TermReason
-Pivot Chart
	Choose Column Chart

```
![KPI5](https://github.com/analyticsaq/HR_DashBoard_Excel/blob/main/KPI5.png)

---

### 6️⃣ Separations

```
-Pivot Table
	Rows:  Date(Year)
	Values:  Seperations,Sum of BadHires
    Legend: Values
-Pivot Chart
	Choose Line Chart

```
![KPI6](https://github.com/analyticsaq/HR_DashBoard_Excel/blob/main/KPI6.png)

---


## 🎦 Visualization

```
-Removed Gridline
-Fill color
-Added a ROW at Left and a COLUMN at top like structure which have many useful information
-Added Text, ICONS and used GETPIVOTDATA to call the Pivot values on the Dashboard.
-Copy and Past all SIX Pivot Chart
-Added Slicers for making it more interactive and dynamic.


```
![Dashboard](https://github.com/analyticsaq/HR_DashBoard_Excel/blob/main/Dashboard.png)
---

## 📌 Findings & Conclusions

- **Total Active Employees:** It provide the information about Total Active Employees including Active Employees and New Hires.  
- **Active by Ethnicity:** All detail about Active employees on the bases of Ethnicity.
- **Average Tenure Months:** It gives the brief about Average Tenure of Employees on the bases of Months.
- **Active by Region:**  Active Employees details is visible, categories into Region.
- **Termination Reason:** What is the reason of termination of Employees not working any longer. 
- **Seperations:** Provides the comparison between Seperations and BadHires.

---

## 🚀 Final Thoughts

This Excel-based exploratory HR Data analysis offers a strategic overview of HR Database. These insights can help strategists, analysts, and other stakeholders to make impactful planning and strategies for the company and can change the existing plan according to the needs.
