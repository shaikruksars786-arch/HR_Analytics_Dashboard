# 📊 HR Analytics Dashboard

An interactive **HR Analytics Dashboard** developed using **Microsoft Power BI** to analyze employee attrition, workforce distribution, salary patterns, job satisfaction, age, gender, and employee experience.

The dashboard helps HR teams understand **who is leaving, from which department, and how attrition varies across different employee characteristics**.

---

## 📌 Project Overview

The **HR Analytics Dashboard** provides a visual and interactive way to analyze employee data and identify important workforce trends.

The dashboard focuses on:

- Employee headcount
- Active employees
- Employee attrition
- Attrition rate
- Salary-wise attrition
- Department-wise attrition
- Job role and job satisfaction
- Age group distribution
- Gender-wise attrition
- Experience-wise attrition

The project was developed in **Microsoft Power BI** using data preparation, DAX measures, interactive slicers, and multiple visualization techniques.

---

## 🎯 Objectives

The main objectives of this project are:

1. Analyze employee attrition patterns.
2. Identify departments with employee exits.
3. Compare attrition across different salary slabs.
4. Understand the relationship between job roles and job satisfaction.
5. Analyze employee distribution by age and gender.
6. Study attrition patterns based on employee experience.
7. Provide useful insights for HR workforce planning and employee retention.

---

## 🛠️ Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| **Microsoft Power BI** | Dashboard development and visualization |
| **Power Query** | Data preparation and cleaning |
| **DAX** | Creating calculated measures and KPIs |
| **Excel / Dataset** | Employee data source |

---

## 📂 Dataset

The dataset contains **31 employee records**.

### Main Fields

- Employee information
- Department
- Job Role
- Salary Slab
- Job Satisfaction
- Age
- Age Group
- Gender
- Experience
- Attrition

### Departments

The dataset contains the following departments:

- Administration
- Finance
- Human Resources
- Marketing
- Operations
- Sales

The dashboard view shown in this project is filtered to **Marketing** and the **26–35 age group**.

---

## 📈 Key Performance Indicators

The dashboard displays six major KPIs:

| KPI | Value |
|---|---:|
| 👥 Total Employees | **31** |
| 🟢 Active Employees | **25** |
| ⚠️ Attrition Count | **6** |
| 📉 Attrition Rate | **19.4%** |
| 🎂 Average Age | **34.74 years** |
| 💼 Average Experience | **7.61 years** |

The active employee count is calculated as:

**Total Employees − Attrition Count = 31 − 6 = 25**

The attrition rate is:

**Attrition Count ÷ Total Employees × 100 = 6 ÷ 31 × 100 = 19.4%**

---

## 📊 Dashboard Visualizations

### 1. Attrition by Department

A donut chart showing how employee exits are distributed across departments.

**Purpose:**  
Helps HR identify departments where employee attrition is concentrated.

---

### 2. Attrition by Salary Slab

A bar chart comparing employees who stayed and employees who left across different salary ranges.

**Salary Slabs:**

- 0–3 LPA
- 3–6 LPA
- 6–10 LPA
- 10+ LPA

**Purpose:**  
Helps identify whether employee attrition varies across different salary levels.

---

### 3. Job Role & Job Satisfaction

A matrix showing employee attrition across job roles and job satisfaction scores from **1 to 4**.

**Purpose:**  
Helps analyze whether particular job roles or satisfaction levels are associated with employee exits.

---

### 4. Age Group Distribution

A column chart showing the number of employees in each age group.

**Purpose:**  
Helps HR understand the age distribution of the workforce.

---

### 5. Attrition by Gender

A pie chart showing the gender-wise distribution of employees who left.

**Purpose:**  
Provides a gender-wise view of employee attrition.

---

### 6. Attrition Trend by Experience

An area chart showing employee exits across different experience levels.

**Purpose:**  
Helps identify experience ranges where employee exits occur.

---

### 7. Department-wise Employee Count

A horizontal bar chart showing the number of employees in each department.

**Purpose:**  
Provides a quick view of workforce distribution across departments.

The project report documents these seven dashboard visuals and their purposes.

---

## 🎛️ Interactive Features

The dashboard contains interactive slicers for:

### Department
Allows users to select a specific department and analyze its workforce and attrition.

### Age Group
Allows users to filter the dashboard according to employee age groups.

The slicers interact with the dashboard visuals, allowing users to explore different employee segments dynamically.

---

## 🔍 Key Insights

Based on the current dashboard data:

- **6 out of 31 employees** have left, resulting in an attrition rate of **19.4%**.
- All 6 recorded exits in the filtered view belong to **Marketing**.
- The **10+ LPA salary slab** has a **50% attrition rate**.
- The **6–10 LPA** salary slab has a **25% attrition rate**.
- The **3–6 LPA** salary slab recorded **0% attrition**.
- All 6 leavers are **Sales Executives** in the current view.
- **5 of the 6 leavers are male** and **1 is female**.
- All 31 records in the current dashboard view belong to the **26–35 age group**.
- Employee exits occur at several different experience levels rather than following one steady trend. 

> **Note:** The dataset contains only 31 records, so these findings should be treated as observations from the available sample rather than conclusions about a larger workforce.

---

## 💡 Business Use Case

HR teams can use this dashboard to:

- Monitor employee attrition.
- Identify departments with higher employee exits.
- Analyze salary-related attrition patterns.
- Understand workforce distribution.
- Study job satisfaction and job roles.
- Support employee retention planning.
- Improve workforce planning.
- Track HR KPIs through interactive reporting.

---

## 🔄 Project Methodology

The project was developed through the following steps:

### Step 1 — Data Preparation
- Imported the employee dataset into Power BI.
- Checked data types.
- Cleaned blanks and duplicates.

### Step 2 — DAX Measures
Created measures for:

- Total Employees
- Active Employees
- Attrition Count
- Attrition Rate
- Average Age
- Average Experience

### Step 3 — Data Visualization
Created:

- KPI Cards
- Donut Chart
- Bar Chart
- Matrix
- Column Chart
- Pie Chart
- Area Chart

### Step 4 — Interactivity
Added:

- Department slicer
- Age Group slicer

These filters allow the dashboard visuals to update interactively.

---

## 📁 Project Structure

```text
HR-Analytics-Dashboard/
│
├── 📊 HR_Analytics_Dashboard.pbix
├── 📄 HR_Analytics_Project_Report.pdf
├── 📂 Dataset/
│   └── employee_data.csv
├── 🖼️ Screenshots/
│   └── HR_Analytics_Dashboard.png
│
└── README.md
```

> File names can be changed according to the files uploaded to the repository.

---

## 🚀 Future Enhancements

The project can be further improved by:

- Adding more employee records.
- Including all departments and age groups in broader analysis.
- Adding employee performance data.
- Adding exit reasons.
- Adding tenure and promotion information.
- Adding manager-related data.
- Developing an employee attrition prediction model using Machine Learning.
- Publishing the dashboard to Power BI Service.
- Adding scheduled data refresh.

These improvements are also identified as future scope in the project report.

---

## ⚠️ Limitations

- The dataset contains only **31 records**.
- The current dashboard view is filtered to **one department and one age group**.
- Exit-reason information is not available.
- Employee performance information is not available.
- Percentages may change significantly with a larger dataset.



---

## 🎓 Learning Outcomes

Through this project, the following skills were developed:

- Power BI Dashboard Development
- Data Cleaning
- Data Visualization
- DAX Measures
- KPI Development
- Interactive Slicers
- HR Data Analysis
- Business Insight Generation
- Dashboard Design
- Data-driven Decision Making

---

## 👩‍💻 Authors

**Shaik Ruksar**  
**S. Sameer Basha**

---

## 📌 Conclusion

The **HR Analytics Dashboard** converts employee data into an interactive visual report that makes workforce and attrition patterns easier to understand.

The dashboard provides HR teams with a centralized view of important metrics such as employee count, attrition rate, salary-wise attrition, job satisfaction, gender, age, and experience. These insights can support better workforce monitoring, retention planning, and HR decision-making.

---

⭐ **If you find this project useful, consider giving the repository a star!**
