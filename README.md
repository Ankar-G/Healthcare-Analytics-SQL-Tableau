# 🏥 Hospital Operations & Patient Analytics

> An end-to-end Healthcare Analytics solution built with **SQL** and **Tableau** to help hospital management optimize operations, reduce patient wait times, improve resource allocation, and enhance patient satisfaction.

---

## 📌 Problem Statement

A multi-specialty hospital is experiencing:

- Increasing patient wait times
- Inefficient resource utilization
- Rising treatment costs
- Declining patient satisfaction

Hospital management lacked a centralized analytics solution to monitor patient flow, department performance, doctor workload, revenue, and operational efficiency. This project delivers a data-driven system to identify bottlenecks and empower smarter decision-making.

---

## 🎯 Project Goal

Develop a comprehensive Healthcare Analytics dashboard using **SQL** for data extraction and transformation and **Tableau** for interactive visualization — enabling hospital leadership to:

- Monitor patient admissions, flow, and demographics
- Evaluate department and doctor performance
- Track revenue trends and treatment costs
- Identify factors affecting patient satisfaction
- Optimize resource allocation across departments

---

## 📊 Dashboards

### 1. Executive Overview Dashboard
High-level KPIs for hospital leadership at a glance.

![Executive Overview Dashboard](assets/dashboard_executive_overview.png)

**Includes:**
- Total Patients, Admissions, Revenue, Avg. Wait Time, Avg. Length of Stay, Avg. Satisfaction Score
- Revenue Trend (Monthly)
- Admissions Trend (Monthly)
- Avg. Wait Time Trend (Monthly)
- Appointment Status Breakdown (Completed, Cancelled, No Show, Rescheduled)

---

### 2. Hospital Operations & Department Performance
Drill-down view of departmental efficiency and resource utilization.

![Operations Dashboard](assets/dashboard_operations.png)

**Includes:**
- Revenue by Department
- Admissions by Department
- Avg. Wait Time by Department
- Avg. Length of Stay by Department
- Admissions per Doctor (Top 5 Departments)
- Department Performance Ranking

---

### 3. Patient & Doctor Insights Dashboard
Demographic and doctor-level performance analytics.

![Patient & Doctor Dashboard](assets/dashboard_patient_doctor.png)

**Includes:**
- Patient distribution by Gender, Age Group, and Insurance Type
- Revenue by Gender
- Top 10 Doctors by Revenue
- Top 10 Doctors by Admissions
- Top Treatment by Volume
- Treatment Generating Highest Revenue
- Low Satisfaction Alert

---

## 📐 Key Business Questions Answered

| # | Business Question |
|---|-------------------|
| 1 | Which departments receive the highest patient volume? |
| 2 | What are the peak admission periods? |
| 3 | Which departments have the longest patient wait times? |
| 4 | Which doctors handle the most patients? |
| 5 | What is the average length of stay by department? |
| 6 | Which treatments generate the highest revenue? |
| 7 | Which patient demographics visit most frequently? |
| 8 | How efficiently are hospital resources being utilized? |
| 9 | What factors are associated with lower patient satisfaction? |

---

## 📈 KPIs Tracked

| KPI | Value (Sample) |
|-----|----------------|
| Total Patients | 9,419 |
| Total Admissions | 30,000 |
| Total Revenue | ₹5,422M |
| Avg. Wait Time | 122.2 minutes |
| Avg. Length of Stay | 9.98 days |
| Avg. Satisfaction Score | 3.693 / 5 |
| Peak Admission Day | Monday (4,609) |
| Top Department by Revenue | Emergency (₹1,164.06M) |
| Top Doctor by Revenue | Dr. Dinesh Singh (₹104.60M) |
| Top Doctor by Admissions | Dr. Kavita Mehta (584) |

---

## 🔍 Key Insights

- **Emergency** is the highest-performing department by both revenue (21.47% share) and admissions (5,406), but also has the highest avg. wait time (~180 min).
- **Oncology** has the longest avg. length of stay (35.73 days), indicating complex, resource-intensive cases.
- **Monday** is the peak admission day, suggesting a need for higher staffing and resource allocation at the start of the week.
- **65+ age group** represents the largest patient segment (3,084), pointing to a need for geriatric care focus.
- **Government insurance** is the most common coverage type (38.44%), affecting billing and revenue planning.
- **Wound Management** received the lowest satisfaction score (3.35), flagging it as a priority for service improvement.
- Appointment **No-Shows (2,110)** and **Cancellations (2,451)** out of 35,000 total represent significant operational loss (~13%).

---

## 🛠️ Tech Stack

| Tool | Usage |
|------|-------|
| **SQL** | Data extraction, cleaning, transformation, and KPI calculation |
| **Tableau** | Interactive dashboard design and visualization |
| **Excel / CSV** | Raw data source |

---

## 📁 Project Structure

```
hospital-analytics/
│
├── assets/                          # Dashboard screenshots
│   ├── dashboard_executive_overview.png
│   ├── dashboard_operations.png
│   └── dashboard_patient_doctor.png
│
├── sql/                             # SQL queries
│   ├── 01_data_cleaning.sql
│   ├── 02_kpi_calculations.sql
│   ├── 03_department_analysis.sql
│   ├── 04_doctor_performance.sql
│   └── 05_patient_demographics.sql
│
├── data/                            # Raw / processed data
│   └── hospital_data.csv
│
├── tableau/                         # Tableau workbook
│   └── hospital_analytics.twbx
│
└── README.md
```

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/hospital-analytics.git
   cd hospital-analytics
   ```

2. **Set up the database**
   - Import `data/hospital_data.csv` into your SQL environment (MySQL / PostgreSQL / SQL Server)
   - Run scripts in the `sql/` folder in numbered order

3. **Open Tableau**
   - Open `tableau/hospital_analytics.twbx` in Tableau Desktop
   - Connect to your database or use the embedded extract
   - Explore the three dashboard tabs

---

## 📬 Contact

**Your Name**
- 📧 your.email@example.com
- 💼 [LinkedIn](https://linkedin.com/in/yourprofile)
- 🐙 [GitHub](https://github.com/yourusername)

---

## ⭐ Show Your Support

If you found this project useful, please consider giving it a ⭐ on GitHub — it helps others discover it!

---

*Built with ❤️ using SQL & Tableau*
