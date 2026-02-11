# 📊 HRvAnalytics Dashboard (Power BI)

## 📌 Project Overview
This project analyzes employee attrition using an HR Analytics dataset.  
The objective is to identify key factors influencing employee turnover and present insights using an interactive Power BI dashboard.

---

## 🔄 Data Preprocessing (Power Query Editor)

The following data cleaning steps were performed:

- Removed unnecessary columns 
- Handled missing values in YearsWithCurrManager
- Removed duplicate records in EmpID
- Corrected data types (numeric, categorical)
- Created Attrition_Flag column for KPI calculation

---

## 📊 Dashboard Features

The dashboard includes:

- Total Employees KPI
- Attrition Count
- Attrition Rate (%)
- Department-wise Attrition
- Job Role-wise Attrition
- Age Group Analysis
- Salary vs Attrition Insights
- Interactive slicers for filtering

---

## 🛠 Tools Used

- Power BI Desktop
- Power Query Editor
- DAX
-Excel

---

## 📁 Repository Structure

data/HR_Analytics_Raw.csv  
→ Original dataset  

data/HR_Analytics_Cleaned.csv  
→ Cleaned dataset used in dashboard  

dashboard/HR_ANALYTICS.pbix  
→ Final Power BI dashboard  

screenshots/dashboard_preview.png  
→ Dashboard preview image  

---

## 🚀 How to Use

1. Download the `.pbix` file
2. Open using Power BI Desktop
3. Refresh the data source if required

---

## 📈 Key Insight

The dashboard helps HR teams understand patterns behind employee attrition and supports data-driven decision making.
The analysis reveals higher attrition among younger employees, lower salary groups, overtime workers, and specific departments and early-career engagement as major influencing factors.
