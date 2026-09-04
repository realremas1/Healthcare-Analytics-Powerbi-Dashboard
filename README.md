# 🏥 Hospital Analytics & Operations Management Dashboard

[![Power BI](https://img.shields.io/badge/Power_BI-Desktop-F2C811?logo=powerbi&logoColor=black)](#)
[![Healthcare Analytics](https://img.shields.io/badge/Domain-Healthcare_Intelligence-0A84FF)](#)
[![Author](https://img.shields.io/badge/Author-Remas_Almalki-107C41)](#)

## 📌 Executive Summary
An end-to-end healthcare intelligence solution developed in **Power BI** to evaluate clinical workloads, monitor financial flows, and uncover patient behavioral trends. The system transforms operational records into dynamic executive KPIs and visual drill-throughs, helping hospital administrators optimize resource scheduling and manage clinical revenue pipelines.

---

## 🖥️ Dashboard Architecture & Previews

### 1. Operations Overview
Central executive monitoring page tracking core healthcare KPIs, departmental capacity, and visit continuity.
![Hospital Operations Overview](Hospital%20Operations%20Overview.png)

### 2. Clinical Performance (Physician Workload)
Workforce analytics breaking down consultations per physician, departmental revenue impact, and clinical treatment costs.
![Doctor Performance](Doctor%20Performance.png)

### 3. Patient Demographics & Insurance Analytics
Behavioral segmentation mapping age clusters, gender ratios, and payer coverage contributions.
![Patient Analytics](Patient%20Analytics.png)

### 4. Financial Performance & Revenue Integrity
Revenue cycle audit tracking payment collection health (Paid, Pending, Failed), payment gateways, and seasonal revenue variations.
![Financial Performance](Financial%20Performance.png)

---

## 🎯 Key Strategic Insights

* **Appointment Drop-Off Rate:** Only **25.5%** of scheduled appointments were completed; no-shows (26%) and cancellations (25.5%) represent significant operational capacity loss requiring automated SMS reminders.
* **Top Clinical Driver:** **Pediatrics** is the primary volume driver across all specializations, generating the highest patient appointments.
* **Revenue Cycle Exposure:** Out of **$551.25K** in total billings, **$184.61K** remains in *Pending* status and **32%** of billing events resulted in *Failed* transactions, highlighting an immediate need to re-evaluate collection protocols.
* **Primary Patient Segment:** Working-age adults aged **31–45** make up the largest patient volume, with **MedCare Plus** serving as the largest insurance revenue channel.

---

## 🛠️ Technical Competencies Demonstrated
- **Tool:** Microsoft Power BI Desktop
- **Data Modeling:** Relational Schema connecting Patients, Doctors, Appointments, Treatments, and Billing tables.
- **DAX Measures:** Custom calculations for average patient revenue, dynamic appointment aggregations, and revenue pipeline segmentation.
- **UI/UX Design:** Dark-themed operational UI with consistent sidebar navigation and cross-filtering.

---

## 📁 Repository Structure
```text
├── data/
│   ├── appointments.csv
│   ├── billing.csv
│   ├── doctors.csv
│   ├── patients.csv
│   └── treatments.csv
├── images/
│   ├── Hospital Operations Overview.png
│   ├── Doctor Performance.png
│   ├── Patient Analytics.png
│   └── Financial Performance.png
├── Healthcare_DB.pbix
└── README.md
