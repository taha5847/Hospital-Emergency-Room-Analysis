# 🏥 Hospital Emergency Room Analysis — Power BI

## 📌 Project Overview

This project is a **Hospital Emergency Room Analysis Dashboard** built in **Microsoft Power BI** using hospital emergency room patient data.

The dataset contains **9,216 patient records** and **12 columns** covering patient information, admission details, wait times, referrals, and satisfaction scores.

The purpose of the dashboard is to analyze emergency room activity through **patient volume, waiting time, satisfaction, referrals, admission status, demographics, and patient-level details**.

---

## 📊 Dataset

The project uses:

**`Hospital ER_Data.csv`**

The dataset contains the following fields:

| Column | Description |
|---|---|
| Patient Id | Unique patient identifier |
| Patient Admission Date | Date and time of patient admission |
| Patient First Initial | Patient first-name initial |
| Patient Last Name | Patient last name |
| Patient Gender | Patient gender |
| Patient Age | Patient age |
| Patient Race | Patient race |
| Department Referral | Referred department |
| Patient Admission Flag | Admission status |
| Patient Satisfaction Score | Patient satisfaction score |
| Patient Waittime | Patient waiting time |
| Patients CM | Patient-related CM field |

---

# 🛠️ Tools Used

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **CSV Dataset**

---

# 📑 Dashboard Pages

The Power BI report contains **three main pages**:

1. Monthly View
2. Consolidated View
3. Patient Details

---

# 1️⃣ Monthly View

The **Monthly View** provides a time-based analysis of emergency room activity.

### Key Metrics

The page includes:

- Number of Patients
- Average Wait Time
- Patient Satisfaction Score
- Number of Patients Referred

### Time-Based Analysis

The dashboard includes daily trends for:

- Number of Patients
- Patient Satisfaction Score
- Number of Patients Referred
- Patient Wait Time

### Filters

The page provides filters for:

- Month
- Year

### Patient Analysis

The page also analyzes patients by:

- Admission Status
- Age Group
- Department Referral
- Wait Time Status
- Gender
- Race
- Day of Week
- Wait Time Interval

---

# 2️⃣ Consolidated View

The **Consolidated View** provides a broader summary of emergency room performance.

### Key Metrics

- Number of Patients
- Average Wait Time
- Patient Satisfaction Score
- Number of Patients Referred

### Monthly Analysis

The dashboard visualizes monthly:

- Patient volume
- Patient satisfaction
- Patient referrals
- Average wait time

### Patient Demographics & Operations

The page includes analysis by:

- Admission Status
- Age Group
- Department Referral
- Wait Time Status
- Gender
- Race
- Day of Week
- Wait Time Interval

### Filter

A date filter is available to analyze the dashboard for a selected period.

---

# 3️⃣ Patient Details

The **Patient Details** page provides patient-level information.

A date filter is available to filter the displayed records.

### Patient Details Table

The table contains:

- Patient ID
- Patient Name
- Patient Gender
- Patient Age
- Admission Date
- Patient Race
- Patient Wait Time
- Department Referral
- Admission Status

This page allows the user to move from the summarized dashboard analysis to individual patient records.

---

# 📈 Analysis Performed

The project focuses on understanding emergency room activity through several areas.

### Patient Volume

Analyzed the number of patients and how patient volume changes over time.

### Waiting Time

Analyzed:

- Average wait time
- Patient wait time
- Wait time status
- Wait time intervals
- Wait time by day

### Patient Satisfaction

Analyzed patient satisfaction scores over time and alongside the emergency room activity.

### Patient Referrals

Analyzed the number of patients referred and how referrals change over time.

### Admission Analysis

Analyzed patients based on their admission status.

### Demographic Analysis

Analyzed patients by:

- Age Group
- Gender
- Race

### Department Analysis

Analyzed the number of patients associated with different department referrals.

### Daily Analysis

Analyzed patient volume by day of the week and examined wait-time intervals across different days.

---

# 🔄 Dashboard Structure

The report follows this structure:

```text
Hospital ER Data
       ↓
Power BI
       ↓
Monthly Analysis
       ↓
Consolidated Analysis
       ↓
Patient-Level Details
```

The dashboard allows users to move from:

**Overall ER Performance → Detailed Analysis → Individual Patient Records**

---

# 📊 Power BI Visualizations

The dashboard uses different Power BI visual types, including:

- Cards
- Area Charts
- Column Charts
- Bar Charts
- Clustered Bar Charts
- Donut Charts
- Tables
- Matrix/Pivot-style visuals
- Slicers

These visuals are used to present patient volume, wait time, satisfaction, referrals, admission status, demographics, and patient details.

---

# 🎯 Key Areas of Analysis

The project answers questions such as:

- How many patients are visiting the emergency room?
- How does patient volume change over time?
- What is the average patient wait time?
- How does patient satisfaction change over time?
- How many patients are referred?
- What is the admission status distribution?
- How are patients distributed across age groups?
- Which departments receive referrals?
- How are patients distributed by gender and race?
- Which days have different levels of patient activity?
- How are patients distributed across wait-time intervals?
- What are the details of individual patients?

---

# 📁 Project Structure

```text
Hospital-Emergency-Room-Analysis/
│
├── Hospital ER_Data.csv
├── Hospital Emergency Analysis.pbix
└── README.md
```

---

# 🚀 Project Objective

The main objective of this project is to use Power BI to create an interactive view of **Hospital Emergency Room activity** and allow users to analyze:

**Patient Volume + Wait Time + Satisfaction + Referrals + Admissions + Demographics + Patient Details**

The project demonstrates how raw hospital emergency room data can be transformed into an interactive Power BI report for analysis and reporting.

---

## 👨‍💻 Author

**Taha Parvaiz**

Data Analyst | Power BI | SQL | Python | Excel

Currently building practical data analytics projects focused on transforming data into clear and useful business insights.
