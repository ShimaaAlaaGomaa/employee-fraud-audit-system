Employee Fraud Audit & Budget Integrity Analysis

A data-driven internal audit project focused on detecting payroll fraud, identifying financial leakages, and evaluating budget integrity through workforce analytics. By transforming raw HR and payroll records into actionable insights, this analysis highlights control weaknesses that contribute to unauthorized compensation, payroll anomalies, and institutional financial losses.

---

Table of Contents

- "Project Overview" (#project-overview)
- "Objective" (#objective)
- "Tools & Technologies" (#tools--technologies)
- "Key Insights & Visualizations" (#key-insights--visualizations)
- "Recommendations" (#recommendations)
- "Next Milestone" (#next-milestone)
- "Connect & Collaborate" (#connect--collaborate)

---

Project Overview

Organizations rely on accurate HR and payroll systems to maintain financial accountability. Weak internal controls, delayed data synchronization, and unauthorized employee record modifications can result in significant budget leakages.

This project audits HR and payroll records to evaluate budget integrity and identify fraudulent activities, including payroll anomalies, status manipulation, ghost employees, and post-termination payments. The objective is to support data-driven internal auditing by converting workforce data into meaningful analytical insights that strengthen financial governance.

---

Objective

The primary objective of this project is to transform raw workforce data into structured analytical insights that expose systemic cost leakages, support internal audit activities, and establish stronger institutional safeguards to ensure employee compensation aligns with legitimate employment status and actual performance.

---

Tools & Technologies

- Programming Language: Python
- Data Manipulation: Pandas, NumPy
- Exploratory Data Analysis (EDA): Matplotlib, Seaborn

---

Key Insights & Visualizations

Budget Integrity & General Distribution

The analysis revealed that approximately 25.3% of the total payroll budget represents fraudulent expenditures or severe financial leakage—equivalent to nearly $4 million. Only 74.7% of payroll spending was classified as legitimate.

A total of 131 anomalous employee records were identified during the audit.

<div align="center">
<img src="budget_integrity.png" alt="Budget Integrity" width="47%"/>
<img src="fraud_flag_distribution.png" alt="Fraud Flag Distribution" width="47%"/>
</div>---

Anomalies Breakdown

Status Manipulation (45 Cases)

Unauthorized modifications to employment records, grades, or job classifications created unjustified compensation increases.

The highest concentration occurred among:

- Technician (13 cases)
- Worker (15 cases)

Ghost Payroll (38 Cases)

Payroll payments were issued to personnel who could not be verified through active employment records.

Performance–Compensation Gap (26 Cases)

Employees with annual performance ratings below 2.0 received unusually high salaries or bonuses, indicating weak compensation governance.

Post-Termination Payments (22 Cases)

Payroll continued after employee termination due to synchronization failures between HR and payroll systems.

The Back Office department showed the highest average inactive employee expense (approximately $78,676), significantly exceeding active employee averages.

<div align="center">
<img src="fraud_type_intensity.png" alt="Fraud Type Intensity" width="48%"/>
<img src="avg_expense_active_inactive.png" alt="Average Expense Active vs Inactive" width="42%"/>
</div>---

Expense Components & Performance Outliers

Most fraudulent expenditures were concentrated within:

- Salary
- Bonus

Leakage was primarily associated with technical, operational, and supervisory roles, indicating elevated financial risk across core workforce functions.

<div align="center">
<img src="fraud_components_dept.png" alt="Fraud Components by Department" width="46%"/>
<img src="performance_vs_compensation.png" alt="Performance vs Compensation" width="46%"/>
<br><br>
<img src="fraudulent_expenses_by_dept.png" alt="Fraudulent Expenses by Department Summary" width="65%"/>
</div>---

Recommendations

- Automate HR–Payroll Integration to immediately stop payroll processing after employee offboarding and eliminate post-termination payments.
- Enforce Dual Authorization & Access Control for modifications to job titles, employment status, grades, and payroll-related fields.
- Implement Performance-Based Validation Rules to prevent bonus allocation for employees below defined performance thresholds.
- Conduct Bi-Annual Payroll Reconciliation by cross-validating payroll records with national identity databases, banking information, and active employee rosters to eliminate ghost payroll.

---

Next Milestone

The next phase of this project focuses on developing an interactive dashboard using Python and Streamlit to support continuous payroll monitoring and fraud detection.

Planned capabilities include:

- Interactive payroll integrity dashboard
- Automated fraud detection checks
- Real-time risk scoring
- Early-warning alerts
- Investigation-ready analytics for auditors and decision-makers

---

Connect & Collaborate

I'm always open to discussing Data Analytics, Internal Audit, Fraud Detection, Financial Analytics, and Data Forensics.

📧 Email: shimaaalaagomaa@gmail.com

💼 LinkedIn: https://www.linkedin.com/in/shimaa-alaa5

If you're interested in collaborating, sharing ideas, or discussing data-driven audit solutions, feel free to connect.
