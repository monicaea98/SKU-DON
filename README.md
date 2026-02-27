# 📊 SKU-DON | End-to-End HR Analytics Dashboard (Power BI)

## 📌 Project Overview

This project is an end-to-end **HR Analytics solution** developed in Power BI.  
It transforms raw employee data into interactive dashboards that support data-driven decision-making in Human Resources.

The solution includes data cleaning, modeling, KPI development, and executive-level dashboard design.

---

## 🎯 Business Objectives

- Analyze employee performance across departments and managers  
- Evaluate salary distribution by age, gender, and department  
- Understand workforce demographics  
- Visualize employee distribution by state  
- Identify potential performance or compensation patterns  

---

## 📂 Dataset Description

The dataset includes the following fields:

- Employee Name  
- Department  
- Position  
- State  
- Gender  
- Salary  
- Performance Evaluation  
- Age  

**Total Employees:** 194  

---

## 🛠 Tools & Technologies Used

- Power BI Desktop  
- Power Query (ETL & Data Transformation)  
- DAX (Calculated Columns & Measures)  
- Data Modeling (Relationships & Aggregations)  

---

## 📊 Dashboard Pages

### 1️⃣ Employee Overview
- Total Employees  
- Average Age  
- Average Salary  
- Average Performance Score  
- Employee distribution by department  
- Employee distribution by state  
- Gender breakdown

---

### 2️⃣ Salary Analysis
- Total Salary Cost ($14.5M)  
- Average Salary ($75K)  
- Salary distribution by age groups  
- Salary distribution by department  
- Geographic salary distribution  
- Gender salary comparison  

---

### 3️⃣ Performance Analysis
- Average performance by gender  
- Average performance by manager  
- Average performance by department  
- Performance distribution ranges  
- Geographic performance insights  

---

## 📈 Key Insights

- Production and Information Technology have the highest workforce concentration.  
- Salary distribution tends to increase with age and seniority.  
- Performance scores are relatively balanced across genders.  
- Some departments show stronger overall performance averages.  
- Salary allocation varies significantly by state.  

---

## 🧹 Data Cleaning Process

- Removed null and duplicate records  
- Standardized salary formatting  
- Created calculated columns for:
  - Salary ranges  
  - Age groups  
  - Performance categories  
- Developed DAX measures for:
  - Average Salary  
  - Total Salary  
  - Average Performance  
  - Employee Count  

---

## 🧠 Data Modeling

- Star schema structure  
- Fact table: Employee Data  
- Dimension tables: Department, State, Gender  
- Optimized relationships for performance and scalability  
