# USED_VEHICLE_MARKET_-_PERFORMANCE_INSIGHTS_DASHBOARD
End-to-end Excel data analysis project leveraging Power Query, Power Pivot (DAX), and dynamic PivotTables to evaluate over 550,000 transaction records.

**Project Overview**
This project delivers a comprehensive end-to-end data analysis and interactive dashboard examine used vehicle sales performance, pricing trends, and valuation drivers. Utilising a dataset of over 550,000 transaction records, the analysis identifies core revenue drivers, brand-level price variations, and the impact of vehicle mileage on market depreciation.
The primary objective is to provide actionable business intelligence for automotive retailers, fleet managers, and pricing analysts to optimise acquisition strategies and pricing models.

**Key Performance Indicators and Insights**
1. Total Sales Revenue: $4.37Billion generated across all analysed transactions.
2. Sales Volume: 558,799 units sold, demonstrating robust market liquidity.
3. Average Selling Price: $13,768, serving as a baseline benchmark across brrands and vehicle conditions.
4. Volume vs. Price Disparity: High-volume brands example Ford, drive overrall market revenue, whereas luxury brands (like BMW, Mercedes-Benz) maintain signicantly higher average selling prices despite lower unit volume.
5. Mileage Depreciation Thresholds: Vehicles categorised under Low Mileage (0-50K miles) retain substantially higher  resale values, with a steep drop-off observed as vehicles cross into the Medium and High Mileage brackets.

**Data Architecture**
1. Data Cleaning and Transforming (Power Query):
   - Filtered null and missing transaction records.
   - Standardized text formats and updated vehicle attributes.
   - Created custom conditional attributes (the odometer readings categorised into actionable Mileage Brackets: Low, Medium, High).
2. Data Modeling and Calculations (Power Pivot)
   - Built relational data models to handle large-scale datasets efficiently.
   - Defined custom measures and aggregation logic for Total Revenue, Unit Counts, and Average Selling Price.
3. Pivot Table Analysis:
   - Segmented market volume by calendar year and sales state.
   - Calculated brand-level performance metrics and condition/tramission breakdowns.
4. Interactive Dashboard Design:
   - Designed a clean, high-contrast UI with gridline-free aesthetics.
   - Integrated KPI summary cards for rapid high-level executive review.
   - Implemented interactive multi-chart Slicers (Year, State) connected through global report connections for dynamic cross-filtering.
  
**Tools used**
- Microsoft Excel: Power Query, Power Pivot(DAX), Pivot Tables, Dynamic Charts, Slicers and User Interface Design.

**Dashboard**
<img width="1350" height="713" alt="Used Vehicle Market   Performace Insights Dashboard" src="https://github.com/user-attachments/assets/b75d0bdf-3cad-4ae3-b536-93531a82417d" />

**Dataset**
- Raw Dataset: Due to file size limitations (>25mb), the raw dataset can be downloaded from here https://www.kaggle.com/datasets/syedanwarafridi/vehicle-sales-data

  
  
