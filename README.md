# 🏥 Healthcare Appointment No-Show Analysis | SQL Portfolio Project

## 📌 Project Overview

This project analyses **medical appointment no-show behaviour** using SQL to identify patterns that can help hospital and clinic management improve appointment attendance, scheduling efficiency, patient communication, and operational planning.

The analysis is based on the **Medical Appointment No Shows** dataset containing **110,526 valid appointment records** and **62,298 unique patients**.

Rather than analysing the dataset using only one method, I developed **six different analytical approaches** to demonstrate how the same healthcare business problem can be investigated from different business, stakeholder, statistical, and technical SQL perspectives.

---

## 🎯 Business Problem

Patient no-shows can result in:

- Unused appointment slots
- Lost clinical capacity
- Inefficient staff utilisation
- Longer waiting times for other patients
- Delays in patient care

The main objective of this project is to use SQL to answer:

> **What factors are associated with medical appointment no-shows, and how can hospital or clinic management use these insights to improve attendance and scheduling efficiency?**

---

## 👥 End Consumer

The primary end consumer is:

**Hospital / Clinic Operations & Management**

Additional stakeholders considered during the analysis include:

- Appointment Scheduling Team
- Patient Services Team
- Healthcare Operations Manager
- Healthcare Planning / Quality Improvement Team
- Senior Management

---

## 📊 Dataset

**Dataset:** Medical Appointment No Shows  
**Source:** Kaggle  
**Records analysed:** 110,526 valid appointments  
**Unique patients:** 62,298  
**Domain:** Healthcare  
**Primary outcome:** Appointment attendance / No-show

### Key Variables

| Category | Variables |
|---|---|
| Patient | PatientId, Gender, Age |
| Appointment | AppointmentID, ScheduledDay, AppointmentDay |
| Location | Neighbourhood |
| Health | Hypertension, Diabetes, Alcoholism, Handicap |
| Support | Scholarship |
| Communication | SMS_received |
| Outcome | No-show |

Additional analytical variables were derived for areas such as **waiting time, age groups, appointment weekdays and waiting-time bands**.

---

## 🛠️ Tools & Technologies

- **SQL**
- **SQLite**
- **Healthcare Analytics**
- **Exploratory Data Analysis**
- **Business Analysis**
- **Data Segmentation**
- **KPI Analysis**

---

# 🔍 Six Analytical Approaches

## 1️⃣ Approach 1 — Business Perspective Analysis

**50 SQL business questions** focused on appointment no-show performance from a Hospital / Clinic Management perspective.

Analysis includes:

- Overall no-show performance
- Patient demographics
- Geographic performance
- SMS reminder performance
- Appointment lead time
- Weekday/time analysis
- Patient health characteristics
- Repeat no-show behaviour
- Management priority analysis

---

## 2️⃣ Approach 2 — Perspective + Difficulty Analysis

**75 SQL business questions** across five analytical areas.

Each area progresses through:

**Easy → Medium → Difficult**

This approach demonstrates progression from basic SQL calculations to more advanced segmentation and ranking analysis.

---

## 3️⃣ Approach 3 — Multi-Stakeholder Analysis

A single **Appointment No-Show Performance** perspective is analysed for five different healthcare stakeholders:

1. Hospital / Clinic Management
2. Appointment Scheduling Team
3. Patient Services Team
4. Healthcare Operations Manager
5. Healthcare Planning / Quality Improvement Team

Each stakeholder receives analysis relevant to their own operational decisions.

---

## 4️⃣ Approach 4 — Statistical Analysis

**60 SQL questions** structured using three analytical levels:

### Univariate Analysis
20 questions analysing individual variables and distributions.

### Bivariate Analysis
20 questions investigating relationships between two variables.

### Multivariate Analysis
20 questions combining multiple variables to identify more complex no-show patterns.

---

## 5️⃣ Approach 5 — SQL Difficulty Progression

**60 SQL questions** organised according to technical difficulty:

- 🟢 20 Easy
- 🟡 20 Medium
- 🔴 20 Difficult

The analysis progresses from basic counts and aggregations to CTEs, window functions, benchmarking and multi-factor segmentation.

---

## 6️⃣ Approach 6 — SQL Concept-Based Analysis

This is the most technically comprehensive section of the project.

**100 SQL questions** are organised into four modules:

### Module 1 — SQL Fundamentals & Data Exploration
`SELECT` • `DISTINCT` • `WHERE` • `AND/OR` • `IN` • `BETWEEN` • `LIKE` • `ORDER BY` • `LIMIT` • `CASE`

### Module 2 — Aggregation & Conditional Analysis
`COUNT` • `SUM` • `AVG` • `MIN/MAX` • `GROUP BY` • `HAVING` • Conditional Aggregation • Percentage Calculations

### Module 3 — Subqueries, CTEs & Data Transformation
Subqueries • CTEs • Nested Queries • Segmentation • Derived Columns • Benchmark Comparisons

### Module 4 — Advanced SQL & Business Analytics
`RANK()` • `DENSE_RANK()` • `ROW_NUMBER()` • `LAG()` • `LEAD()` • `PARTITION BY` • Running Totals • Contribution Analysis • Advanced Segmentation

---

# 💡 Key Areas Investigated

The project explores questions such as:

- What is the overall appointment no-show rate?
- Which patient groups have higher no-show rates?
- How does age relate to appointment attendance?
- Which neighbourhoods experience higher non-attendance?
- How does appointment waiting time affect no-shows?
- How does attendance differ between patients who received SMS reminders and those who did not?
- Which weekdays experience greater no-show risk?
- Are there repeat no-show patients?
- Which combinations of patient and appointment characteristics represent higher-risk segments?
- Which areas should management prioritise for attendance improvement?

---

# 🧠 SQL Skills Demonstrated

This project demonstrates practical use of:

- Data filtering
- Data quality checks
- Aggregations
- Conditional logic
- `CASE WHEN`
- `GROUP BY`
- `HAVING`
- Subqueries
- Common Table Expressions (CTEs)
- Date calculations
- Conditional aggregation
- Percentage and rate calculations
- Multi-dimensional segmentation
- Ranking
- Window functions
- Running totals
- Benchmark comparisons
- Business KPI development

---

# 📁 Repository Structure

```text
Healthcare-Appointment-NoShow-SQL-Analysis/
│
├── README.md
├── medical_appointment_no_shows.csv
├── SQL_Question_Report.sql
│
├── Approach - 1 Report.docx
├── Approach - 2 Report.docx
├── Approach - 3 Report.docx
├── Approach - 4 Report.docx
├── Approach - 5 Report.docx
└── Approach - 6 Report.docx
```

---

# 📈 Project Value

This project was designed not simply as a collection of SQL exercises, but as a **business-focused healthcare analytics case study**.

Using six analytical frameworks demonstrates how SQL can be applied to the same operational problem from different perspectives — including business decision-making, stakeholder requirements, statistical analysis and progressive SQL complexity.

The project demonstrates my ability to move from:

**Business Question → SQL Analysis → Result Interpretation → Management Insight**

---

## 🚀 Future Improvements

Future extensions of this project could include:

- Power BI dashboard development
- Python exploratory data analysis
- Automated healthcare KPI reporting
- Patient no-show risk segmentation
- Interactive management dashboard
- Predictive modelling for appointment attendance

---

## 👤 Author

**Kishor Shida**

Aspiring Data Analyst | SQL | Python | Power BI | Excel

📍 United Kingdom

### 🔗 Connect With Me

- 💼 [LinkedIn](https://www.linkedin.com/in/kishor-shida-0a5a98226/)
- 💻 [GitHub](https://github.com/KishoorDataLab)

---

⭐ If you found this project useful, feel free to explore the different analytical approaches in this repository.
