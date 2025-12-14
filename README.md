# HR-Analytics-Dashboard
# 📊 HR Analytics Dashboard (Power BI)

## 📌 Project Overview

This project presents an **HR Analytics Dashboard** built in **Power BI** to analyze employee attrition patterns and key workforce metrics. The dashboard enables HR teams and leadership to identify **why employees leave**, **which groups are most affected**, and **where retention strategies should be focused**.

The analysis is based on a structured HR dataset containing employee demographics, job roles, income, tenure, and satisfaction levels.

---

## 🎯 Business Problem

Employee attrition leads to:

* Increased hiring & training costs
* Loss of experienced talent
* Reduced team productivity

**Objective:**
To analyze historical HR data and uncover **attrition drivers** across age, income, education, job role, gender, and years at company.

---

## 🛠 Tools & Technologies

* **Power BI** – Data modeling & dashboard creation
* **DAX** – KPI calculations (Attrition Rate, Averages)
* **Excel / CSV** – Data source & preprocessing

---

## 📈 Key KPIs Tracked

* **Total Employees:** 1,470
* **Total Attrition:** 237
* **Attrition Rate:** 16.12%
* **Average Age:** 37 years
* **Average Monthly Income:** 6.5K
* **Average Years at Company:** 7 years

---

## 🔍 Key Insights

### 👥 Attrition by Gender

* Male attrition is significantly higher than female
* Indicates potential role or compensation-related gaps

### 🎓 Attrition by Education

* Highest attrition from **Life Sciences (38%)** and **Medical (27%)** backgrounds
* Suggests higher mobility or external demand in these fields

### 🎂 Attrition by Age Group

* **26–35 age group** shows the highest attrition
* Early to mid-career employees are more likely to switch jobs

### 💼 Attrition by Job Role

* Highest attrition observed among:

  * Laboratory Technicians
  * Sales Executives
  * Research Scientists
* These roles may require better incentives, career paths, or workload balance

### 💰 Attrition by Income Level

* Majority of attrition comes from employees earning **up to 5k**
* Attrition decreases as income increases

### 🕒 Attrition by Years at Company

* Highest attrition occurs within the **first 1–3 years**
* Indicates onboarding, culture fit, or expectation mismatch issues

---

## 📊 Dashboard Features

* Interactive department-level filtering
* KPI cards for instant business overview
* Role-wise and demographic attrition analysis
* Trend analysis based on tenure

---

## 🖼 Dashboard Preview

<img width="988" height="558" alt="Screenshot 2025-12-14 142510" src="https://github.com/user-attachments/assets/03a2d377-2606-48a2-b041-472affc1816e" />


---

## 📂 Dataset Information

**File Name:** `HR_Analytics.csv`

### 📌 Dataset Description
This dataset contains employee-level HR data used to analyze workforce demographics, job attributes, compensation, satisfaction, and attrition patterns.

### 🧾 Key Columns
- **EmployeeID** – Unique identifier for each employee  
- **Age** – Age of the employee  
- **Gender** – Male / Female  
- **Department** – Human Resources, Sales, Research & Development  
- **JobRole** – Employee job designation  
- **EducationField** – Educational background  
- **MonthlyIncome** – Employee monthly income  
- **YearsAtCompany** – Tenure in the organization  
- **JobSatisfaction** – Satisfaction rating (1–4)  
- **Attrition** – Employee left the company (Yes / No)

### 📊 Dataset Size
- **Rows:** 1,480 employees  
- **Columns:** Multiple HR attributes covering demographics, compensation, and performance

*Dataset used for analytical and educational purposes.*

---

## 🐍 Python Analysis (Jupyter Notebook)

In addition to Power BI, a **Python-based Exploratory Data Analysis (EDA)** was performed using a Jupyter Notebook to validate findings and extract deeper insights from the HR dataset.

### 📁 Python Files
- `HR Analytics Notebook.ipynb` – Jupyter Notebook containing Python analysis
- `HR_Analytics.csv` – Dataset used for analysis

### 🛠 Libraries Used
- **Pandas** – Data cleaning and manipulation  
- **NumPy** – Numerical computations  
- **Matplotlib & Seaborn** – Data visualization  

### 🔍 Analysis Performed
- Data cleaning and missing value checks  
- Attrition distribution analysis  
- Age-wise, income-wise, and tenure-wise attrition trends  
- Gender and job-role based attrition comparison  
- Visualizations supporting Power BI insights
  
---

## 🚀 Business Impact

This dashboard helps organizations:

* Identify high-risk attrition segments
* Design targeted retention strategies
* Improve compensation and career planning
* Reduce employee turnover costs

---

## 📌 Conclusion

The HR Analytics Dashboard converts raw HR data into **actionable insights** that support strategic workforce planning and employee retention decisions.

---

## 👤 Author

**Vipul Gupta**
Data Analyst | SQL | Excel | Power BI | Python

📎 LinkedIn: *www.linkedin.com/in/vipulgupta28*
