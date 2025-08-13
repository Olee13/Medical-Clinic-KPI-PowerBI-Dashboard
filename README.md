# Medical Clinic KPI & Patient Analysis Dashboard 🏥

An interactive **Power BI dashboard** built from a **SQL database** extracted from a medical clinic's **Practice Management System**.  
The dashboard provides insights into clinic performance, operational KPIs, and patient demographics.

---

## Features
- **Clinic KPIs**
  - Total appointments, patient counts, and gender distribution.
  - Revenue tracking by doctor.
- **Patient Analysis**
  - Age group distribution.
  - Common diagnoses with appointment counts.
  - Appointment trends by day of the week and year.
- **Date Range Filtering**
  - Interactive slider for custom date ranges.

---

## Tools & Skills Used
- **SQL** – Extracted and prepared data from the Practice Management System database.
- **Power BI** – Designed and built an interactive dashboard.
- **DAX Calculations**:
  - `Total Revenue = SUM(Appointments[BillingAmount])`
  - `Patient Gender % = DIVIDE([Gender Count], [Total Patients], 0)`
- **Data Cleaning**
  - Removed duplicates and invalid entries.
  - Standardized date/time formats.
  - Ensured consistent diagnosis naming.

---

## Dashboard Preview
![Medical Clinic Dashboard]([https://github.com/Olee13/Medical-Clinic-KPI-PowerBI-Dashboard/blob/main/MedicalDashboard.png])

---

## Insights
- Majority of patients fall in the **40–55 age group**.
- **Females account for 70%** of total patients.
- **Thursday** is the busiest day of the week.
- **Top revenue-generating doctor**: Siphilele at R80.50K.
- Most common diagnosis: Pneumonia, Nose Bleeding, and Pink Eye.

---

**Author:** Olwethu Nxasana  
**Year:** 2025
