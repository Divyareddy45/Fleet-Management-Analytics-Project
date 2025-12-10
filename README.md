# 🚚 Fleet Management Analytics Project

A complete end-to-end data analytics project using **Python**, **SQL**, and **Power BI** to analyze fleet vehicle performance, maintenance patterns, and operational efficiency.

---

## 📌 Project Overview

The goal of this project is to extract meaningful insights related to:

&nbsp;&nbsp;&nbsp;&nbsp;• Vehicle efficiency and fuel performance  
&nbsp;&nbsp;&nbsp;&nbsp;• Maintenance cost patterns  
&nbsp;&nbsp;&nbsp;&nbsp;• Vehicle age vs. performance trends  
&nbsp;&nbsp;&nbsp;&nbsp;• Driver performance impact  

The project is structured into three phases:

&nbsp;&nbsp;&nbsp;&nbsp;• Python ETL & data preparation  
&nbsp;&nbsp;&nbsp;&nbsp;• SQL-based performance and cost analytics  
&nbsp;&nbsp;&nbsp;&nbsp;• Power BI dashboard visualization  

---

🛠️ Tools & Technologies

&nbsp;&nbsp;&nbsp;&nbsp;• Python (pandas, NumPy, matplotlib, seaborn)  
&nbsp;&nbsp;&nbsp;&nbsp;• SQL – MySQL Workbench  
&nbsp;&nbsp;&nbsp;&nbsp;• Power BI – Interactive dashboards & KPIs  

---

# 🧪 Phase 1 — Python (ETL & Data Analysis)

**1. Import and Explore Data**

&nbsp;&nbsp;&nbsp;&nbsp;• Load vehicle dataset using pandas  
&nbsp;&nbsp;&nbsp;&nbsp;• Initial exploration and profiling  



**2. Data Cleaning & Transformation**

&nbsp;&nbsp;&nbsp;&nbsp;• Handle missing values and duplicates  
&nbsp;&nbsp;&nbsp;&nbsp;• Fix incorrect data types  
&nbsp;&nbsp;&nbsp;&nbsp;• Validate numerical ranges  
&nbsp;&nbsp;&nbsp;&nbsp;• Calculated Field

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○ vehicle_age  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○ cost_per_km  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○ monthly_mileage  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○ efficiency_category (High / Medium / Low)  



**3. Data Analysis**

&nbsp;&nbsp;&nbsp;&nbsp;• Performance by vehicle make and model  
&nbsp;&nbsp;&nbsp;&nbsp;• Relationship between age and fuel efficiency  
&nbsp;&nbsp;&nbsp;&nbsp;• Maintenance cost trends by vehicle type  
&nbsp;&nbsp;&nbsp;&nbsp;• Driver performance impact  



**4. Data Export**

&nbsp;&nbsp;&nbsp;&nbsp;• Clean dataset exported for SQL  
&nbsp;&nbsp;&nbsp;&nbsp;• Summary statistics saved for reporting  

---

# 🗄️ Phase 2 — SQL (Vehicle Performance Analytics)

**Database Setup**

&nbsp;&nbsp;&nbsp;&nbsp;• Create Vehicle Performance database  
&nbsp;&nbsp;&nbsp;&nbsp;• Import cleaned dataset  



**Analytical Queries**

**Basic Queries**

&nbsp;&nbsp;&nbsp;&nbsp;• Total mileage & average efficiency per make  
&nbsp;&nbsp;&nbsp;&nbsp;• Maintenance cost by vehicle type and age  
&nbsp;&nbsp;&nbsp;&nbsp;• Identify top-performing vehicles  



**Advanced Queries (CTEs + Window Functions)**

&nbsp;&nbsp;&nbsp;&nbsp;• Ranking vehicles by efficiency  
&nbsp;&nbsp;&nbsp;&nbsp;• Moving average of maintenance cost  
&nbsp;&nbsp;&nbsp;&nbsp;• Above/below average performance detection  
&nbsp;&nbsp;&nbsp;&nbsp;• Efficiency degradation with age  
&nbsp;&nbsp;&nbsp;&nbsp;• Cost-to-mileage ratio comparison  



**Comparative Analysis**

&nbsp;&nbsp;&nbsp;&nbsp;• New vs old vehicle performance  
&nbsp;&nbsp;&nbsp;&nbsp;• Vehicle type efficiency comparison  
&nbsp;&nbsp;&nbsp;&nbsp;• Manufacturer-based maintenance trends  

---

# 📊 Phase 3 — Power BI Dashboard

**1. Executive Summary**

&nbsp;&nbsp;&nbsp;&nbsp;• KPIs: Total Vehicles, Avg Fuel Efficiency, Total Mileage, Avg Maintenance Cost  
&nbsp;&nbsp;&nbsp;&nbsp;• Vehicle distribution by type & make  
&nbsp;&nbsp;&nbsp;&nbsp;• Age distribution chart  



**2. Performance Analysis**

&nbsp;&nbsp;&nbsp;&nbsp;• Scatter chart: Age vs Efficiency  
&nbsp;&nbsp;&nbsp;&nbsp;• Bar chart: Avg Efficiency by Make  
&nbsp;&nbsp;&nbsp;&nbsp;• Line chart: Maintenance Cost vs Mileage  
&nbsp;&nbsp;&nbsp;&nbsp;• Heat map: Performance Score Distribution  



**3. Cost Analysis**

&nbsp;&nbsp;&nbsp;&nbsp;• Maintenance cost by vehicle type  
&nbsp;&nbsp;&nbsp;&nbsp;• Cost-per-km insights  
&nbsp;&nbsp;&nbsp;&nbsp;• Driver performance impact  
&nbsp;&nbsp;&nbsp;&nbsp;• Age vs maintenance cost trend  






<img width="1920" height="1080" alt="Screenshot (149)" src="https://github.com/user-attachments/assets/22bad8bb-58eb-41ed-b260-95a4b9968ce6" />
<img width="1920" height="1080" alt="Screenshot (148)" src="https://github.com/user-attachments/assets/35887c85-30fc-4d2b-93e9-07bc2f5143b8" />
<img width="1920" height="1080" alt="Screenshot (147)" src="https://github.com/user-attachments/assets/e743b76c-1c9d-46fa-b66a-8d380fe53af0" />
________________________________________
🎯 Expected Outcome

&nbsp;&nbsp;&nbsp;&nbsp;• A fully cleaned fleet dataset ready for analysis  

&nbsp;&nbsp;&nbsp;&nbsp;• Clear insights on vehicle performance, efficiency, and cost trends  

&nbsp;&nbsp;&nbsp;&nbsp;• SQL-driven analytics for ranking, comparison, and trend evaluation  

&nbsp;&nbsp;&nbsp;&nbsp;• Interactive Power BI dashboards presenting key metrics and visuals  

&nbsp;&nbsp;&nbsp;&nbsp;• End-to-end experience in ETL, analytics, SQL, and BI reporting  



