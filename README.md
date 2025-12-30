# Inbound-Shipment-Overview-Dashboard
# 📦 Inbound Shipment Overview Dashboard (Excel)

## 🔍 Overview
This repository contains an **Excel-based Inbound Shipment Dashboard** designed to monitor shipment performance, value, weight, data quality, and network coverage.

The dashboard is fully built in **Microsoft Excel** using pivot tables, charts, KPI cards, and slicers.  
It is optimized for **one-page PDF export** for reporting and executive presentations.

---

## 🎯 Objectives
- Track inbound shipment volume, weight, and declared value
- Monitor data quality issues such as missing HS codes and misrouted shipments
- Analyze shipment distribution by origin, product category, and consignee
- Provide a clean, executive-level summary for decision-making

---

## 📊 Dashboard Features

### 🔹 KPI Cards
**Volume & Value**
- Total Packages  
- Single Packages  
- Multiple Packages  
- Total Weight (KG)  
- Total Declared Value ($)

**Data Quality & Network**
- Unique Shippers  
- Unique Consignees  
- Packages with Missing HS Codes  
- Misrouted Shipments  

---

### 🔹 Analytical Sections
- Declared Value Distribution
- Weight Distribution
- Number of Shipments by Origin
- Weight by Origin
- Declared Value by Origin
- Declared Value by Product Category
- Weight by Product Category
- Declared Value by Consignee
- Weight by Consignee
- Pieces vs Declared Value
- Weight vs Declared Value

---

### 🔹 Data Quality Exception Tables
- Shipments with Missing HS Codes
- Misrouted Shipments

These tables dynamically respond to slicers and KPI filters.

---

## 🖨️ One-Page PDF Export (Correct Method)

The dashboard is optimized to export as **one single PDF page** without cutting content.

**Steps:**
1. Select the entire dashboard area
2. Go to **Page Layout → Print Area → Set Print Area**
3. Open **Page Setup**
   - Orientation: Landscape  
   - Paper Size: A3  
   - Scaling: Fit to **1 page wide × 1 page tall**
4. Set margins to small values (~0.3")
5. Disable gridlines and headings
6. Export using:
   - `File → Save As → PDF`
   - or `File → Print → Microsoft Print to PDF`

---

## 📂 Repository Contents

| Folder | Description |
|------|------------|
| `dashboard/` | Excel dashboard and PDF export |
| `screenshots/` | Dashboard preview image |
| `data/` | Data documentation |
| `README.md` | Project documentation |

---

## 🛠️ Tools Used
- Microsoft Excel
- Pivot Tables & Pivot Charts
- Slicers
- Microsoft Print to PDF

---

## 👥 Intended Audience
- Supply Chain Analysts  
- Logistics & Operations Managers  
- Finance Teams  
- Executives & Decision Makers  

---

## 📄 License
This project is shared for educational, portfolio, and internal analytics use.
