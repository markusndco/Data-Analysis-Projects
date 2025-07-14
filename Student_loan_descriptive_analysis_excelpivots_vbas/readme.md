# Student Loan Portfolio Dashboard and Data Modeling

This project analyzes a student loan disbursement dataset using Excel's advanced features, including data modeling, pivot tables, and interactive dashboards. The objective is to provide a dynamic view of portfolio performance, highlight risk segments, and derive insights for decision-making.

---

## 📌 Project Overview

The portfolio under analysis includes over **5,200 Higher Education Loans (HELs)** totaling **₹1178.40 crores** in disbursed value as of **September 30, 2022**. The dashboard and pivot reports reveal critical data on loan performance, aging, tenure, interest brackets, and delinquency buckets.

---

## 🔍 Key Features

### 🔹 1. Dashboard Summary
- Tracks total portfolio value (POS), current vs. overdue split
- Visualizes DPD (Days Past Due) buckets:
  - **1–30 DPD:** ₹5.16 Cr  
  - **31–60 DPD:** ₹1.86 Cr  
  - **>180 DPD:** ₹0.80 Cr
- Provides monthly insights on portfolio health and risk areas

### 🔹 2. Pivot Table Views
- Enables interactive slicing by:
  - Institute name
  - Product segment
  - Tenure band
  - Loan amount and LTV buckets
- Highlights segment-level exposure to delinquencies

### 🔹 3. Data Modeling using Formulas
Excel formulas were used to:
- Classify tenure (`<3Y`, `3–5Y`, `>7Y`)
- Bin interest rates (`<10%`, `10–12%`, `12–14%`)
- Segment CIBIL scores (`<700`, `700–750`, `750+`)
- Calculate LTV and EMI-to-income categories
- Enable dashboard interactivity via named ranges and filters

### 🔹 4. 'Working' Sheet: Descriptive Binning
- Grouped variables into logical bins for filtering:
  - **Loan Amount Bands**: `<5 Lacs`, `5–15 Lacs`, etc.
  - **Interest Rate Ranges**
  - **DPD Buckets**
  - **Country/Institute Classification**

---

## 🛠 Tools Used

- **Microsoft Excel** (Pivot Tables, Slicers, Conditional Formatting)
- **Excel Formulas**: `IF`, `VLOOKUP`, `SUMIFS`, `COUNTIFS`, etc.
- **Manual Data Cleaning & Categorization**

---

## 📈 Insights

- Over **99% of the portfolio** is in the **current** status.
- Early warning signals exist in the **1–30 DPD** bucket.
- Loan delinquency is more concentrated in specific tenures and interest rate bands.

---

## 📁 Files Included

- `Portfolio_Dashboard_Analysis.docx`: Summary report
- Excel file with:
  - `Dashboard` sheet (visuals & KPIs)
  - `PIVOT` sheet (segment analysis)
  - `Working` sheet (data preparation logic)
  - `Data Disb MIS` sheet (raw dataset)

---

## 👤 Author

**Aryan Sharma**  
Data Scientist

---

## 📘 License

This project is intended for educational use and internal reporting. Attribution appreciated if reused or adapted.
