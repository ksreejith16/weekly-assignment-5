#  Strategic Sales & Profitability Analytics Suite

![Power BI](https://img.shields.io/badge/Power_BI-Desktop-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![Data Source](https://img.shields.io/badge/Data-Modified_Retail_Dataset-blue?style=for-the-badge)

##  Executive Overview

This project is a robust **Business Intelligence (BI) solution** designed to analyze retail sales performance across global markets. Leveraging **Power BI**, this dashboard transforms raw transactional data into actionable insights, enabling stakeholders to identify high-value regions, optimize product portfolios, and track year-over-year (YoY) growth trends.

Unlike standard reporting tools, this solution utilizes a **custom-designed "Deep Ocean" UI theme** for enhanced readability and professional presentation, focusing on user-centric data storytelling.

---

##  Dashboard Previews

### 1. Executive Sales Dashboard
*A high-level view of critical KPIs including Total Sales, Net Profit, and YoY Growth percentages, featuring a custom sidebar navigation.*
![Executive Dashboard](./image_7a0fca.png) 
*(Replace this path with your actual image file)*

### 2. Product Performance Matrix
*Granular analysis of product categories using conditional formatting and data bars to highlight top performers instantly.*
![Product Matrix](./image_7a0ce0.png)

---

##  Key Features

* ** Dynamic KPI Tracking:** Real-time calculation of Total Sales, Profit Margins, and YoY Growth using advanced DAX measures.
* ** Geospatial Intelligence:** Interactive map visualizations to pinpoint sales hotspots and regional performance gaps.
* ** Time-Series Analysis:** Drill-down capabilities allowing users to analyze trends by Year, Quarter, and Month to detect seasonality.
* ** Custom UI/UX Design:** Implemented a non-standard "Navy & Teal" professional color palette with rounded borders and shadow effects for a modern application feel.
* ** Product Matrix:** Advanced matrix visualizations replacing standard tables, featuring embedded data bars for quick comparative analysis.

---

##  Technical Architecture

This project follows a structured **ETL (Extract, Transform, Load)** methodology:

1.  **Data Extraction:** Imported raw sales data (`Modified_Sales_Data.csv`) containing 1,000+ transaction records.
2.  **Data Transformation (Power Query):**
    * Cleaned inconsistent data types.
    * Created a standard **Star Schema** data model.
    * Established a dedicated **Date Table (DimDate)** for accurate time-intelligence calculations.
3.  **Data Modeling:** Built relationships between Fact tables (`FactSales`) and Dimension tables (`DimRegion`, `DimDate`).
4.  **Visualization:** Applied a custom JSON theme file to enforce brand consistency across all report pages.

---

##  Business Questions Answered

This dashboard is designed to answer critical business questions:
* *Which regions are driving the highest profit margins vs. simple revenue volume?*
* *How is the current year's performance comparing to the previous year (YoY)?*
* *Which product sub-categories are underperforming and dragging down net profit?*
* *Is there a seasonal trend in sales spikes (e.g., Q4 holiday surges)?*

---

##  Installation & Usage

To view and interact with this report locally:

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    ```
2.  **Prerequisites:** Ensure you have [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) installed.
3.  **Open the File:** Double-click `Chubb_Assignment_5.pbix` to launch the report.
4.  **Refresh Data:** If you modify the source CSV, click the "Refresh" button in the Home ribbon to update the visuals.

---

##  License

This project is open-source and available under the [MIT License](LICENSE).

---

### 👤 Author
**[sreejith reddy]**
