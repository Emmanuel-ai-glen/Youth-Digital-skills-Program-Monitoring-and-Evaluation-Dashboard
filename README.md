# Youth Digital Skills Program — Monitoring, Evaluation & Data Analytics

## Project Overview

This project is a simulated Monitoring, Evaluation and Data Analytics case study
for a youth digital-skills training program in Dar es Salaam, Tanzania.

The project demonstrates an end-to-end analytical workflow from simulated field
data collection and data-quality assessment to analysis and Power BI reporting.

The dataset contains 100 youth participants across five Dar es Salaam districts:
Ilala, Kinondoni, Temeke, Ubungo and Kigamboni.

> Note: This is a simulated portfolio project and does not represent a real
> client engagement or actual Archway Consulting project.

---

## Problem / Evaluation Context

The analysis examined program participation, implementation and early observed
participant outcomes.

The key questions included:

- Who participated in the program?
- How strong was participant attendance and completion?
- How did training performance differ across training types?
- What barriers did participants report?
- What support did participants request?
- How did employment and income compare before and after training?
- Was attendance associated with training performance?

---

## Objectives

1. Assess participant reach and characteristics.
2. Assess attendance and training completion.
3. Examine training performance and satisfaction.
4. Identify reported barriers and support needs.
5. Compare observed employment and income before and after training.
6. Examine the relationship between attendance and training score.
7. Develop a management-oriented Power BI dashboard.

---

## Data Collection

The project used a simulated KoboToolbox-based field data collection workflow.

The dataset contains 100 participants from:

- Ilala
- Kinondoni
- Temeke
- Ubungo
- Kigamboni

The unit of analysis is one participant per record.

---

## Dataset

Key variables include:

- Participant_ID
- Enumerator_ID
- District
- Ward
- Interview_Date
- Age
- Gender
- Education_Level
- Training_Type
- Attendance_Rate
- Training_Completed
- Training_Score
- Employment_Before
- Employment_After
- Income_Before_TZS
- Income_After_TZS
- Business_Started
- Satisfaction_Score
- Main_Barrier
- Support_Needed

---

## Data Quality & Validation

The raw dataset was loaded into MySQL for data-quality assessment and
preparation.

Quality checks included examination of:

- Record counts
- Missing information
- Participant identifiers
- Uniqueness
- Variable consistency
- Validity of categorical values

A data-definition issue was identified in the simulated Gender variable,
which contained Yes/No values rather than meaningful gender categories.

The dataset was subsequently prepared as a cleaned CSV for analysis.

---

## Data Preparation

The workflow was:

KoboToolbox / simulated collection
→ CSV / Excel
→ MySQL raw table
→ Data-quality assessment
→ Cleaning
→ Clean CSV
→ Python analysis
→ Power BI reporting

---

## Analysis

The analysis covered:

- Participant distributions
- Attendance
- Completion
- Training performance
- Satisfaction
- Reported barriers
- Support needs
- Employment before vs after
- Income before vs after
- Income change by district
- Attendance and training-score relationship

---

## Key Findings

The Power BI dashboard showed:

- 100 participants in the simulated dataset.
- Employment rate of 18% before training and 29% after training.
- Average reported income of approximately TZS 98.40K before training and
  TZS 131.50K after training.
- Average training score of 74.32 on the implementation dashboard.
- Average satisfaction score of 3.68.
- Average attendance of approximately 82% on the implementation dashboard.
- Business-started rate of 20%.

Dashboard KPI reconciliation is still required for some measures before these
figures should be treated as final project findings.

---

## Dashboard / Reporting

The Power BI dashboard contains three sections:

### Page 1 — Reach & Participation

Examines participant distribution, district reach, education, training type,
attendance and completion.

### Page 2 — Implementation & Learning

Examines training performance, completion, satisfaction, reported barriers
and participant support needs.

### Page 3 — Outcomes & Insights

Examines observed employment and income before and after training and explores
the relationship between attendance and training performance.

---

## Insights

The dashboard was designed to help program managers:

- Monitor participant engagement and completion.
- Identify differences across training types and districts.
- Understand reported participation barriers.
- Monitor observed employment and income changes.
- Identify areas requiring further investigation.

The results should be interpreted as observed patterns rather than causal
program impacts because the project does not use a controlled evaluation design.

---

## Recommendations

- Investigate reported barriers to participation and completion.
- Examine weaker-performing training types and implementation conditions.
- Continue collecting follow-up employment and income data.
- Strengthen validation rules in future data-collection instruments.

---

## Tools & Technologies

- KoboToolbox
- Excel / CSV
- MySQL
- Python / pandas
- Power BI

---

## Skills Demonstrated

- Data collection design
- Data quality assessment
- Data validation
- SQL
- Data cleaning
- Descriptive analysis
- Before/after comparison
- Data visualization
- KPI development
- Dashboard development
- Analytical problem solving
- Management reporting
- Data interpretation
- Documentation
