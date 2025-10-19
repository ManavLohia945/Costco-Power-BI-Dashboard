# 🧾 Costco Power BI Dashboard Project
<img width="1008" height="360" alt="Costco Logo" src="https://github.com/user-attachments/assets/4e8c92af-6caa-41ce-a65c-5a4f1f4d4fe0" />

## 📊 Advanced End-to-End Power BI Project | Real-World Business Analytics Case Study

This project demonstrates advanced Power BI capabilities applied to real-world retail data from Costco, focusing on interactive dashboard design, KPI development, and DAX-based business insights. The goal was to analyze sales performance, profit trends, and regional growth through a highly dynamic and visually compelling dashboard.

# 🚀 Project Overview

## Objective:
To design a professional, data-driven Power BI dashboard that delivers key business insights — total revenue, profit, and growth trends — enabling executives to evaluate performance across regions and segments efficiently.

## Key Outcomes:

- Built an interactive Power BI dashboard analyzing $2.8M+ in revenue and 49K+ orders.

- Implemented custom DAX measures to calculate YoY growth, profit margins, and KPI comparisons versus targets. 

- Enhanced query performance and usability with custom bookmarks, slicers, and dynamic visual storytelling.

- Created a real-world, interview-ready portfolio project showcasing advanced analytical and visualization skills.

## 🧩 Problem Statement

Costco’s management required a unified view of key business metrics — sales, profit, and growth — across multiple regions and time periods.
The goal was to:

- Track KPIs against targets.

- Compare performance by region, segment, and product.

## 🛠️ Steps & Methodology
### 1. Identifying Key Performance Indicators (KPIs)

Total Revenue, Total Profit, Total Quantity Sold, Regional Sales Growth, Profit Margins, Order Achievement vs. Target

### 2. Data Cleaning & Transformation (Power Query)

- All preprocessing performed within Power BI — not Excel.
- Removed duplicates and nulls, validated data types.
- Split columns (e.g., Country-City) using delimiters.
- Merged Global Sales with Products tables via Product_ID for price and cost data.
- Created custom columns for Net Sales and Profit using Power Query formulas.
- Eliminated redundant columns (start/end dates) to streamline model performance.

### 3. Data Modeling

- Established relational model connecting Global_Sales, Products, and newly created Date table (M:1 cardinality).
- Built a dynamic Date Table using DAX with derived fields for Year, Quarter, and Month Start Date.
- Marked Date table as primary for time-intelligence calculations.

### 4. DAX Measures & Calculations

- Centralized all calculations in a dedicated Measures Table:
- Total Revenue, Total Profit, Total Orders
- YoY and Target Calculations (Target = 1.5x Previous Year)
- Created advanced KPI measures for % Growth vs. Target and prior-year comparison using CALCULATE, FILTER, and DATEADD functions.

### 5. Dashboard Design & Visualization

Implemented dark-themed executive dashboard with Costco branding.
Designed custom bookmarks and slicer panels for intuitive interactivity.
Visual elements include:
- **Line chart for Revenue vs. Target**
- **Donut chart for Revenue by Segment**
- **Bar chart for Regional Profit Distribution**
- **Gauge for Order Achievement vs. Target**
- **Geographic Map for Statewise Revenue**
- **Added Year slicers and region filters with toggle animations for a seamless user experience.**

### 📈 Key Insights Generated

- **Total Revenue: $2.8M+, Total Profit: $1.6M+, Total Orders: 49K+**
- **South and West regions contributed the highest profit margins.**
- **Corporate segment generated 27.5% of total revenue, while Home Delivery dominated consumer share.**
- **Visualized YoY growth trends and pinpointed underperforming product categories.**

### 🏆 Learning & Outcomes
 
- Mastered end-to-end BI workflow: Data Cleaning → Modeling → Visualization → Storytelling
- Gained advanced proficiency in DAX, Power Query, and interactive dashboard design.
- Built a portfolio-ready dashboard demonstrating business acumen and analytical storytelling — key skills for Data & Business Analyst roles at firms like Amazon, Amex, and Swiggy.

### 📸 Dashboard Preview
<img width="1745" height="971" alt="Screenshot 2024-12-24 at 10 43 47 PM" src="https://github.com/user-attachments/assets/3b8f7b56-57ba-4f11-bc30-28cc3b5471f8" />

### 🧾 Conclusion

This Costco Power BI project exemplifies how analytical rigor and visualization design come together to create actionable business intelligence. From data cleaning and modeling to KPI creation and storytelling, this dashboard reflects the skills and thinking of a business-first data analyst capable of delivering measurable value.
