# 📦 Inbound Shipment Overview Dashboard (Excel)

## 🔍 Project Overview
This repository contains an **Excel-based Inbound Shipment Dashboard** built using **Power Query, Data Modeling, Pivot Tables, and Charts**.

The dashboard provides an executive-level view of inbound shipment performance, data quality, and network coverage.  
It is designed to be **data-source flexible**, allowing the underlying dataset to be replaced without rebuilding the dashboard.

---

## 🎯 Dashboard Objectives
- Monitor inbound shipment volume, weight(KG), and declared value($)
- Track data quality issues (missing HS codes, misrouted shipments)
- Analyze shipment distribution by origin, product category, and consignee
- Provide a single-page dashboard suitable for reporting and PDF export

---

## 🔄 How the Dashboard Is Updated (Important)

The dashboard is refreshed using **Power Query and the Excel Data Model**.

### Standard Update Process
1. Open the Excel dashboard file
2. Go to **Data → Power Query Editor**
3. Change the **data source** to the new dataset
4. Click **Close & Load**

This loads the new data into the **Data Model**.

---

### Data Model Logic
- New columns and calculated fields are created inside the **Data Model**
- All KPI cards, pivot tables, pivot charts, and visuals are connected to the Data Model
- Once the data is refreshed, all connected visuals update automatically

---

### Exception Tables (Special Handling)
- The **Missing HS Code** and **Misrouted Shipments** tables are created as **pivot tables** in a **separate worksheet**
- This worksheet is hidden from end users
- The pivot table outputs are **copied and pasted** into the dashboard sheet for layout and formatting consistency

📌 When data is refreshed:
- The hidden pivot tables update automatically
- The pasted tables on the dashboard should be **re-copied and refreshed manually** if required

---

## 🖨️ PDF Export
The dashboard is optimized for **single-page PDF export**.

**Recommended settings:**
- Paper size: A5
- Orientation: Portrait
- Scaling: Fit to 1 page wide × 1 page tall
- Print Area: Dashboard area only

---

## 🛠️ Tools & Technologies
- Microsoft Excel
- Power Query
- Excel Data Model
- Pivot Tables & Pivot Charts

---

  ## 👥 Intended Audience
- Supply Chain Analysts
- Logistics & Operations Teams
- Finance & Reporting Teams
- Managers and Decision Makers

---

## 📄 License
This project is shared for educational, portfolio, and internal analytics use.
