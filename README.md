# Cybersecurity Breach Monitoring & Operational Analytics Dashboard

##  Project Overview

Organizations generate large volumes of cybersecurity incident data across departments, branches, and operational teams. Monitoring breach activity is critical for understanding security exposure, measuring response effectiveness, and identifying areas that require attention.

This project analyzes cybersecurity breach records and presents key operational security metrics through an interactive Power BI dashboard.

The dashboard enables stakeholders to monitor breach trends, evaluate department and branch performance, track incident resolution status, and assess organizational exposure to cybersecurity incidents.

---

##  Business Problem

Security teams require a centralized view of breach activity to answer key operational questions:

- How many cybersecurity breaches have occurred?
- How many incidents remain unresolved?
- Which departments experience the highest breach volume?
- Which branches are most affected?
- How much data has potentially been compromised?
- Which employees identify the most breaches?
- What is the average time taken to close incidents?

Without a consolidated reporting system, monitoring organizational security performance becomes difficult.

---

##  Dataset Information

The dataset contains cybersecurity breach records including:

| Column | Description |
|----------|----------|
| Number | Unique breach identifier |
| Name_of_Covered_Entity | Organization affected |
| Business_Associate_Involved | Third-party involvement indicator |
| Total Individuals | Number of individuals impacted |
| Individuals_Affected | Employees affected by breach |
| Type_of_Breach | Breach category |
| Location_of_Breached_Information | Source of compromised information |
| breach_start | Incident start date |
| breach_end | Incident closure date |
| Branch | Branch affected |
| Department | Department affected |
| CountryBranch | Geographic location |
| Employee(who find out breach) | Reporting employee |
| Employee URL | Employee profile image |
| Estimate Stole Data(GB) | Estimated data compromised |

---

##  Tech Stack

- **Python**
  - Pandas
  - NumPy
  - matplotlib
  - seaborn

- **Power BI**
  - DAX
  - Data Modeling
  - Interactive Dashboards

---

##  Project Workflow

### 1. Data Preparation

- Imported breach records
- Cleaned missing values
- Standardized categorical fields
- Processed date columns
- Created calculated metrics

### 2. SQL Analysis

Performed exploratory analysis including:

- Breach distribution analysis
- Department-level breach tracking
- Branch-wise incident analysis
- Data exposure calculations
- Incident closure monitoring

### 3. Dashboard Development

Built a multi-page Power BI dashboard for:

- Executive monitoring
- Department analysis
- Branch analysis
- Employee ranking
- Operational reporting

---

## 📊 Dashboard Pages

### Home Dashboard

Provides a high-level overview of organizational cybersecurity performance.

KPIs Included:

- Total Breaches
- Open Breaches
- Closed Breaches
- Employee Strength
- Average Breach End Days
- Estimated Stolen Data (GB)
- Affected Employees
- Secured Employees
- Affected Employee %
- Secured Employee %
- Breach Detection Employees

---

### Employee Ranking Dashboard

Analyzes employee contribution in identifying cybersecurity incidents.

Key Insights:

- Top breach reporting employees
- Open vs closed breaches by employee
- Employee contribution percentage
- Breach discovery rankings

---

### Department Analysis Dashboard

Evaluates cybersecurity performance across departments.

Key Metrics:

- Total breaches by department
- Open vs closed breaches
- Estimated data loss
- Average breach resolution time
- Employee impact analysis

---

### Branch Analysis Dashboard

Analyzes cybersecurity exposure across organizational branches.

Key Metrics:

- Branch-wise breach volume
- Data exposure by branch
- Employee impact by branch
- Average breach closure duration

---

### Executive Summary Dashboard

Provides consolidated security KPIs for management reporting and operational monitoring.

---

## Key Business Insights

The dashboard helps stakeholders:

- Monitor active cybersecurity incidents
- Track incident resolution performance
- Identify departments with higher breach activity
- Compare branch-level security exposure
- Measure organizational impact of breaches
- Evaluate employee contribution to breach detection
- Assess potential data loss from incidents

---

##  Skills Demonstrated

- Data Cleaning & Transformation
- SQL Querying
- Exploratory Data Analysis (EDA)
- Data Modeling
- KPI Development
- DAX Measures
- Dashboard Design
- Business Intelligence Reporting
- Cybersecurity Operations Analytics
- Data Visualization

---

##  Business Value

This dashboard demonstrates how cybersecurity incident data can be transformed into actionable business intelligence by enabling security teams and decision-makers to:

- Monitor organizational security posture
- Track breach resolution effectiveness
- Identify high-risk departments and branches
- Improve operational visibility
- Support data-driven security decisions
