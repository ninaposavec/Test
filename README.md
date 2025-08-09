# 👥 Employee Satisfaction Report

This Power BI report analyzes employee satisfaction within a company by exploring key HR metrics and visualizing patterns across departments and demographics.

---

## 📂 Data Source

This report uses publicly available HR data from Kaggle:  
🔗 [HR Analytics: Employee Attrition and Performance Dataset](https://www.kaggle.com/datasets/mahmoudemadabdallah/hr-analytics-employee-attrition-and-performance)

---

## 📊 Overview

The report is structured across multiple pages to present a detailed demographic overview of the company and analyze job satisfaction within each department.

### 📄 Page 1: Company Overview

This page provides a high-level summary of the organization, including:

- Total number of employees  
- Average salary  
- Average years at the company  
- Employee breakdown by:
  - Gender  
  - Ethnicity  
  - Age group  
  - Department and job role (using a decomposition tree)  
  - Education level and field (with drill-through capability)

The data reflects the entire company but can be filtered by department (HR, Sales, or Technical).

<img width="975" height="543" alt="image" src="https://github.com/user-attachments/assets/9c550a57-04c1-4c96-981f-d5aa4a38fbbf" />

---

## 🗂️ Department-Level Analysis

Each department page (HR, Sales, Technical) provides department-specific metrics through page filters.

### Metrics shown include:
- Average job satisfaction
- Relationship satisfaction
- Environment satisfaction
- Ratings for:
  - Work-life balance
  - Self-assessment
  - Manager feedback
- Employee attrition

### Available filters:
- Gender  
- Education level  
- Years at company  
- Salary level  
- Year  
- Business travel frequency

<img width="975" height="559" alt="image" src="https://github.com/user-attachments/assets/acc7c710-6d7c-4f60-b20c-b7b7759d4b48" />

---

## 🛠️ Tools Used

- Power BI Desktop
- Power Query for data transformation
- DAX for calculated measures and filters
- Data modeling with defined relationships
- Hierarchies:
  - Department → Job Role
  - Education Level → Education Field
- Custom histogram groupings for employee age
  

### Note on Data Quality
The original dataset included a "Years at Company" column. However, discrepancies were found between this column and the actual difference between hire date and review date. A new calculated column was created to reflect the correct values. Some values were negative — these were filtered out of the visuals using a report-level filter to ensure accurate insights.

---

## 📌 Use Case

This report can support HR teams and leadership in:

- Monitoring employee satisfaction across departments
- Identifying trends based on job roles, salary, and tenure
- Tracking changes in satisfaction over time
- Enabling data-driven decision-making and resource planning



