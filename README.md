# 📊 Sales Intelligence Report – Excel Dashboard

An end-to-end **Excel-based analytics project** that transforms raw sales data into an interactive, business-ready **Sales Intelligence Report** using Excel’s advanced BI capabilities.

---

## 🔖 Project Summary

This project showcases how **Microsoft Excel** can be used as a full-featured **analytics and BI environment**, combining:

- **Power Query** for data cleaning & transformation  
- **Power Pivot** for data modelling & relationships  
- **Calculated measures (DAX-style logic)** for KPIs  
- **Pivot Tables & Pivot Charts** for analysis & visualization  
- **Slicers & KPI Cards** for interactivity and user experience  

The dashboard delivers insights into:

- Sales performance  
- Profitability  
- Return behavior  
- Category-wise profit  
- Regional contribution  

All wrapped in a **clean, purple–lavender theme** for a professional look.

---

## 🧩 Features

- ✅ Fully **interactive Excel dashboard**
- ✅ **KPI cards** with auto-updating values  
- ✅ Dynamic **Pivot Charts** connected through slicers  
- ✅ Clean **Power Query** transformation flow  
- ✅ Centralized **Data Model** using Power Pivot  
- ✅ Professionally formatted UI & consistent color theme  

---

## 🛠️ Tools & Technologies

| Tool / Feature       | Purpose                                      |
|----------------------|----------------------------------------------|
| **Microsoft Excel**  | Core analysis, modelling & visualization    |
| **Power Query**      | ETL – data import, cleaning, transformation |
| **Power Pivot**      | Data Model & relationships                  |
| **Pivot Tables**     | Aggregation & analytical views              |
| **Pivot Charts**     | Visual insights (line, combo, area, donut)  |
| **Slicers**          | Interactive filtering                       |
| **KPI Cards**        | High-level metric summaries                 |
| **Custom Formatting**| Professional theme & layout                 |

---

## 📈 Dashboard Components

The Excel dashboard consists of the following core visuals:

1. **Monthly Sales Trend (Line Chart)**  
   - Displays sales performance across months.  
   - Helps identify patterns, peaks, and dips.

2. **Sales vs Profit (Combo Chart)**  
   - Columns for Sales, line for Profit.  
   - Highlights months with high sales but low profit (or vice versa).

3. **Category-Wise Profit (Column Chart)**  
   - Shows profit contribution by product category.  
   - Helps identify high and low performing categories.

4. **Return Impact Analysis (Area + Line Chart)**  
   - Area: Order Count  
   - Line: Return Rate (%)  
   - Used to spot months with unusual return behavior.

5. **Regional Performance (Doughnut Chart)**  
   - Visualizes contribution of each region to total sales.  

---

## 📊 Key Performance Indicators (KPIs)

The following KPIs are presented as **KPI cards** at the top of the dashboard:

- **Total Sales**  
- **Total Profit**  
- **Order Count**  
- **Return Rate**

These KPIs are powered by **calculated measures** in the data model and update dynamically with slicer selections.

---

## 🔄 Data Flow & Workflow

1. **Data Import & Cleaning (Power Query)**  
   - Import raw sales data.  
   - Handle nulls, set proper data types, and clean columns.  
   - Load cleaned tables into the **Data Model**.

2. **Data Modelling (Power Pivot)**  
   - Create relationships between fact and lookup tables (if applicable).  
   - Build a structured model suitable for analysis.

3. **Measure Creation**  
   - Create DAX-style measures, e.g.:  
     - `Total Sales`  
     - `Total Profit`  
     - `Order Count`  
     - `Return Rate`

4. **Visualization (Pivot Tables & Charts)**  
   - Build PivotTables for each analysis view.  
   - Convert them into PivotCharts.  
   - Arrange charts on a dedicated **Dashboard** sheet.

5. **Interactivity (Slicers)**  
   - Add slicers for:
     - Region  
     - Category  
     - Order Month  
     - Ship Mode  
   - Connect all slicers to relevant pivot tables (Report Connections).

6. **UI & Theme**  
   - Apply consistent **purple–lavender–lime** color theme.  
   - Format fonts, titles, borders, slicers, and chart layouts for a clean UI.

---

## 📂 Repository Structure

> You can adjust file/folder names as per your actual repo.

```bash
.
├── data/
│   └── Sales_Data.xlsx                # (Optional) Raw/cleaned data source
│
├── dashboard/
│   └── Sales_Intelligence_Report.xlsx # Main Excel dashboard
│
├── documentation/
│   ├── Sales_Intelligence_Report_ColorAccents_Final_v2.pdf  # Project report
│   └── Fraud_Analysis_Dashboard_Styled.pdf                  # (If you include it)
│
├── assets/
│   └── dashboard_screenshot.png       # Screenshot of the Excel dashboard
│
└── README.md
