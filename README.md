**🚚 Fleet Management Analytics Project**

A complete end-to-end data analytics project using Python, SQL, and Power BI to analyze fleet vehicle performance, maintenance patterns, and operational efficiency.
________________________________________

**📌 Project Overview**

The goal is to extract meaningful insights around vehicle efficiency, maintenance cost trends, driver performance, and overall operational health of the fleet.

This project delivers a comprehensive analysis of vehicle fleet data by progressing through three major phases:

            1.Python (ETL & Data Preparation) – cleaning, transforming, and analyzing raw fleet data
            
            2.SQL (Advanced Analytics) – running performance, cost, and maintenance analytics
            
            3.Power BI (Dashboard Reporting) – building insights and executive summaries
________________________________________

**🛠️ Tools & Technologies**

Python: pandas, NumPy, matplotlib/seaborn
SQL: MySQL workbench for analytical queries
Power BI: Interactive dashboards and KPIs
________________________________________
**🧪 Phase 1 — Python (ETL & Data Analysis)**
**1️⃣ Data Import & Exploration**
    
     Load dataset using pandas
     Generate initial profiling and descriptive statistics

**2️⃣ Data Cleaning & Transformation**

Key cleaning steps:
       Handling missing values & duplicates
       Fixing incorrect data types
       Validating ranges (fuel efficiency, mileage, etc.)
Creating calculated fields:
      Vehicle Age (years/months)
      Cost per km = annual_maintenance_cost / current_mileage_km
      Monthly mileage
Efficiency category: 
       High / Medium / Low (based on fuel efficiency)
      
**3️⃣ Data Analysis**

Insights generated:
      Performance by vehicle make and model
      Relationship between age and fuel efficiency
      Maintenance cost trends by vehicle type
      Driver performance impact on operations

**4️⃣ Data Export**

Clean dataset exported for SQL
Summary statistics saved for reporting

________________________________________
**🗄️ Phase 2 — SQL (Vehicle Performance Analytics)**
**📂 Database Setup**

Create a Vehicle Performance database
Import cleaned fleet dataset
🧩 Analytical Queries

**Basic Queries:**
     Total mileage & average efficiency per make
     Maintenance cost by vehicle type and age
     Identify highest-performing vehicles (fuel efficiency)

**Advanced Queries (CTEs + Window Functions):**
     Ranking vehicles within each make
     Moving average of maintenance cost
     Identify above/below average performers
     Analyze efficiency degradation with age
     Compare cost-to-mileage ratios
     Fleet Management Analytics Proj…

**Comparative Analysis:**
    New vs old vehicle performance
    Vehicle type efficiency comparison
    Manufacturer-based cost trends
________________________________________
**📊 Phase 3 — Power BI Dashboard**
**Dashboard Pages**

**1. Executive Summary Page**
   .KPI Cards: Total Vehicles, Average Efficiency, Total Mileage, Avg Maintenance Cost
   .Vehicle distribution by type and make
   .Age distribution chart
   <img width="1210" height="745" alt="Fleet manamgement power bi1" src="https://github.com/user-attachments/assets/62e7458c-f676-4d97-9392-05dc95532678" />

________________________________________
**2️. Performance Analysis**
    
    Scatter chart: Age vs Efficiency
    Bar chart: Avg Efficiency by Make
    Line chart: Maintenance Cost vs Mileage
    Heat map: Performance Score Distribution

    <img width="1202" height="737" alt="Fleet manamgement power bi2" src="https://github.com/user-attachments/assets/612b39e6-68d8-413e-89c2-4612a42a7cad" />

________________________________________
**3️. Cost Analysis**

    Maintenance cost by type
    Cost-per-km calculation visuals
    Driver performance impact
    Age vs maintenance cost trend

    <img width="1200" height="755" alt="Fleet manamgement power bi3" src="https://github.com/user-attachments/assets/4499807b-8a7d-45f6-857f-8798081db185" />

________________________________________
**🎯 Expected Outcome**

A fully cleaned and transformed fleet dataset ready for analysis.
Key insights into vehicle performance, fuel efficiency, maintenance costs, and driver impact.
SQL-driven analytics identifying top-performing vehicles, cost trends, and efficiency patterns.
An interactive Power BI dashboard presenting KPIs, performance visuals, and cost analysis.
End-to-end experience in ETL, data analysis, SQL querying, and BI reporting.








