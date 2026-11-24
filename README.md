# 🏥 Healthcare Operations Data Analytics Project

An end-to-end Data Analytics capstone project focused on cleaning, modeling, and visualizing hospital operations data to track patient admissions, bed occupancy, waiting times, billing, and overall patient satisfaction.

---
## 📊 Dashboard Preview
![Healthcare Dashboard](Dashboard%20look.png)

## 📂 Repository Contents

* **`healthcare_dataset.xlsx`** — Cleaned and normalized dataset organized into three relational sheets (`Patient Information`, `Admission Details`, and `Billing and Care`).
* **`Healthcare Project..pbix`** — Interactive multi-page Power BI Desktop dashboard featuring dynamic slicers and KPI cards.
* **`Healthcare_Project_Presentation.pptx`** — Executive presentation summarizing key insights, data workflow, and recommendations.

---

## 🛠️ Tools & Technologies Used

* **Microsoft Excel:** Data cleaning, duplicate removal, text normalization, date & currency formatting, and relational table structuring.
* **Power BI Desktop:** Data modeling, DAX measures, interactive KPI cards, slicers, and multi-page dashboard design.

---

## 🔄 Data Preparation & Modeling Workflow

1. **Data Cleaning (Excel):**
   * Removed duplicate patient records to ensure data integrity.
   * Standardized patient names using the `PROPER` function.
   * Formatted admission/discharge dates and standardized billing amounts in Indian Rupees (`₹`).
2. **Relational Structuring:**
   * Split the raw flat dataset into three structured tables: **Patient Information**, **Admission Details**, and **Billing and Care**.
3. **Dashboard Development (Power BI):**
   * Connected the three sheets in Power BI's data model.
   * Built interactive filters (such as **Admission Type** slicers) for dynamic drill-down analysis.

---

## 📊 Key Metrics & KPIs Tracked

* **Total Patient Count** (by Patient ID)
* **Bed Occupancy Rate**
* **Average Patient Waiting Time**
* **Patient Satisfaction Score**
* **Billing & Care Breakdown** across different admission types

---

## 🚀 How to View the Dashboard

1. Download **`Healthcare Project..pbix`** from this repository.
2. Open the file using **Microsoft Power BI Desktop** (free to download on Windows).
3. Use the slicers on the report pages to filter metrics by Admission Type and explore hospital performance trends.
