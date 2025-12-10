**🚚 Fleet Management Analytics Project**

A complete end-to-end data analytics project using Python, SQL, and Power BI to analyze fleet vehicle performance, maintenance patterns, and operational efficiency.
________________________________________

## 📌 Project Overview

The goal of this project is to extract meaningful insights related to:

• Vehicle efficiency and fuel performance  
• Maintenance cost patterns  
• Vehicle age vs. performance trends  
• Driver performance impact  

The project is structured into three phases:

• Python ETL & data preparation  
• SQL-based performance and cost analytics  
• Power BI dashboard visualization  

 ________________________________________

**🛠️ Tools & Technologies**

• Python (pandas, NumPy, matplotlib, seaborn)
• SQL – MySQL Workbench
• Power BI – Interactive dashboards & KPIs
 ________________________________________
 
**🧪 Phase 1 — Python (ETL & Data Analysis)**
**1. Import and Explore Data**

   • Load vehicle dataset using pandas

   • Initial exploration and profiling

**2. Data Cleaning & Transformation**

   • Handle missing values and duplicates
   
   • Fix incorrect data types
   
   • Validate numerical ranges
   
   • Create calculated fields:
      • vehicle_age
      
      • cost_per_km
      
      • monthly_mileage
      
      • efficiency_category (High / Medium / Low)

**4. Data Analysis**

   • Performance by vehicle make and model
   
   • Relationship between age and fuel efficiency
   
   • Maintenance cost trends by vehicle type
   
   • Driver performance impact

**6. Data Export**

   • Clean dataset exported for SQL
   
   • Summary statistics saved for reporting
________________________________________
 

**🗄️ Phase 2 — SQL (Vehicle Performance Analytics)**
Database Setup

**• Create Vehicle Performance database
• Import cleaned dataset**

Analytical Queries
**Basic Queries**

   • Total mileage & average efficiency per make
   
   • Maintenance cost by vehicle type and age
   
   • Identify top-performing vehicles
   

**Advanced Queries (CTEs + Window Functions)**

   • Ranking vehicles by efficiency
   
   • Moving average of maintenance cost
   
   • Above/below average performance detection
   
   • Efficiency degradation with age
   
   • Cost-to-mileage ratio comparison

Comparative Analysis

  • New vs old vehicle performance
  
  • Vehicle type efficiency comparison
  
  • Manufacturer-based maintenance trends
________________________________________
 
**📊 Phase 3 — Power BI Dashboard**
1. Executive Summary

  • KPIs: Total Vehicles, Avg Fuel Efficiency, Total Mileage, Avg Maintenance Cost
  
  • Vehicle distribution by type & make
  
  • Age distribution chart

2. Performance Analysis

• Scatter chart: Age vs Efficiency
• Bar chart: Avg Efficiency by Make
• Line chart: Maintenance Cost vs Mileage
• Heat map: Performance Score Distribution

3. Cost Analysis

• Maintenance cost by vehicle type
• Cost-per-km insights
• Driver performance impact
• Age vs maintenance cost trend

3. Performance Analysis

      • Scatter chart: Age vs Efficiency

      • Bar chart: Avg Efficiency by Make

      • Line chart: Maintenance Cost vs Mileage

      • Heat map: Performance Score Distribution

5. Cost Analysis

    • Maintenance cost by vehicle type

    • Cost-per-km insights

    • Driver performance impact

    • Age vs maintenance cost trend


<img width="1920" height="1080" alt="Screenshot (149)" src="https://github.com/user-attachments/assets/22bad8bb-58eb-41ed-b260-95a4b9968ce6" />
<img width="1920" height="1080" alt="Screenshot (148)" src="https://github.com/user-attachments/assets/35887c85-30fc-4d2b-93e9-07bc2f5143b8" />
<img width="1920" height="1080" alt="Screenshot (147)" src="https://github.com/user-attachments/assets/e743b76c-1c9d-46fa-b66a-8d380fe53af0" />
________________________________________
**🎯 Expected Outcome**

    • A fully cleaned fleet dataset ready for analysis
 
    • Clear insights on vehicle performance, efficiency, and cost trends

    • SQL-driven analytics for ranking, comparison, and trend evaluation

    • Interactive Power BI dashboards presenting key metrics and visuals
 
    • End-to-end experience in ETL, analytics, SQL, and BI reporting



