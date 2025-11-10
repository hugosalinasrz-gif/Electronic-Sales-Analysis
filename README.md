# Electronic Sales Analysis Report

## 📋 Overview
This project focuses on analyzing a Kaggle dataset of electronic sales (20,000 rows, 2023–2024) to build a structured report and deliver actionable business insights.  
The main goal was to demonstrate how common sales questions can be answered through **data preparation and visualization** using **Excel** with **Power Query**, **Pivot Tables**, and **interactive dashboards**.

---

## 🧹 Data Preparation
Data cleaning and transformation were performed in Power Query to prepare the dataset for analysis:
- Removed blank rows and adjusted data types  
- Added a custom column for total sales (`total_calculated`)  
- Created a separate month column with a new date format  
- Reordered columns for clarity  
- Added a conditional column (`group_age`) to classify customers by age group  

**Manual adjustments:**
- `quantity_adjusted`: manually corrected column to fix minor data inconsistencies in quantities before analysis. Adjustments not performed in Power Query.

---

## 📊 Visualization Process
The analysis explored key sales-related questions and visualizations:

- **How have sales evolved monthly?**  
- **Which product category sells the most units?**  
- **What is the sales distribution per age group?**

Additional dashboard visuals include:
- Product preferences by gender  
- Most used payment method  
- Average product rating  

---

## 📈 Key Insights
The final Excel dashboard consolidates all main sales questions into a single interactive view.  
It integrates pivot charts and slicers, enabling dynamic exploration by product, payment method, age group, and month.

**Highlights:**
- **Age group impact:** Customers over 50 generate nearly half of total sales (~$33M), while the under-25 segment contributes only ~$7.4M.  
- **Seasonality:** Sales peak mid-year, especially in **August ($7.3M)**, but drop by over **70% in December**.  
- **Product performance:** Smartphones dominate the market with **37K units sold**, far surpassing other categories.  

These findings suggest that focusing on older customer segments, reinforcing year-end sales strategies, and prioritizing smartphone marketing could help maximize future sales performance.

---

## 🧰 Tools Used
- Microsoft Excel  
  - Power Query  
  - Pivot Tables  
  - Pivot Charts  
  - Interactive Dashboard  

---
```
## 🗂️ Project Structure

sales-analysis-project/
├── README.md                   ← Project explanation
├── Sales_Analysis_Report.pdf   ← PDF documentation
├── Sales_Dashboard.xlsx        ← Interactive dashboard
└── data_preparation/
    ├── raw_data.csv            ← Original dataset
    └── transformed_data.csv    ← Cleaned dataset ready for analysis
├──Visuals
   ├──Dashboard_overview.png
```