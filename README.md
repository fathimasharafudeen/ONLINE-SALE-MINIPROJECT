# Online Sales Dashboard – Excel Mini Project

An Excel-based data analysis mini-project that explores an online sales dataset using pivot tables, charts, slicers, and a summary dashboard.

## 📁 Project Structure

The workbook (`EXCEL_MINIPROJECT_XSLV.xlsx`) contains 4 sheets:

| Sheet | Description |
|---|---|
| **Sales Dataset** | Raw dataset (~1,800 records) of online customer transactions, including derived fields for segmentation |
| **lookup** | Reference table mapping Customer ID → Country → Total Spent |
| **Pivot Table and chart** | Pivot tables and supporting analysis |
| **Dashboard** | Consolidated visual dashboard with charts and interactive slicers |

## 📊 Dataset Fields

- `Customer_ID`, `Gender`, `Age`, `Country`
- `Device_Type`, `Product_Category`
- `Time_Spent_Minutes`, `Items_Viewed`, `Items_Purchased`, `Total_Spent_usd`
- Derived fields: `Buyer Status`, `Age Group`, `High Spender`

## 🔍 Key Analysis Performed

- Customer segmentation by buyer status, age group, and spend level
- Country- and device-wise sales breakdown
- Category-wise revenue distribution
- Relationship between time spent on site and purchases
- Answers to targeted business questions, e.g.:
  - Total count of mobile users in India
  - Total spending by female customers on electronics
  - Average time spent by customers with zero purchases

## 📈 Visualizations

The dashboard includes multiple chart types:
- Pie charts (spend distribution by category/segment)
- Bar charts (comparisons across categories/countries)
- Line charts (age group vs. average time spent)
- Scatter charts (spend vs. engagement relationships)

Interactive **slicers** are used to filter the dashboard dynamically.

## 🛠️ Tools Used

- Microsoft Excel
  - Pivot Tables & Pivot Charts
  - Slicers
  - Data segmentation / categorical formulas

## 🎯 Purpose

This project was built as a mini-project to practice core Excel data analysis skills: cleaning and structuring raw data, building pivot tables, creating charts, and assembling an interactive dashboard for business insight reporting.

## 📌 How to Use

1. Download `EXCEL_MINIPROJECT_XSLV.xlsx`
2. Open in Microsoft Excel (2016 or later recommended for full slicer/pivot support)
3. Navigate to the **Dashboard** sheet to explore filtered insights
4. Use the **Sales Dataset** sheet to view the underlying raw data
