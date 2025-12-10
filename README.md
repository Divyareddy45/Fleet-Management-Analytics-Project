**🚚 Fleet Management Analytics Project**

A complete end-to-end data analytics project using Python, SQL, and Power BI to analyze fleet vehicle performance, maintenance patterns, and operational efficiency.
________________________________________


**📌 Project Overview**

The objective of this project is to extract meaningful insights about:

Vehicle efficiency

Maintenance cost trends

Driver performance

Overall fleet operational health

The project is divided into three major phases:

Python (ETL & Data Preparation) – cleaning, transforming, and analyzing raw fleet data

SQL (Advanced Analytics) – performing performance, cost, and maintenance analytics

Power BI (Dashboard Reporting) – building interactive dashboards and executive summaries

________________________________________


🛠️ Tools & Technologies

Python: pandas, NumPy, matplotlib, seaborn

SQL: MySQL Workbench for analytical queries

Power BI: Interactive dashboards and KPI visuals

________________________________________


**🧪 Phase 1 — Python (ETL & Data Analysis)**
1. Import and Explore Data

Load vehicle dataset using pandas

Perform initial exploration and profiling

2. Data Cleaning & Transformation

Handle missing values and duplicates

Correct data types and validate value ranges

Create calculated columns:

vehicle_age (from purchase year/date)

cost_per_km = annual_maintenance_cost / current_mileage_km

monthly_mileage = current_mileage_km / vehicle_age_months

efficiency_category (High / Medium / Low based on fuel efficiency)

3. Data Analysis

Performance comparison by vehicle make and model

Age vs fuel efficiency relationship

Maintenance cost trends by vehicle type

Impact of driver performance on cost and efficiency

4. Data Export

Clean dataset exported for SQL processing

Summary statistics generated for reporting

________________________________________


**🗄️ Phase 2 — SQL (Vehicle Performance Analytics)**
📂 Database Setup

Create a Vehicle Performance database

Import the cleaned dataset into SQL tables

 Analytical Queries

Basic Queries

Total mileage & average efficiency by make

Maintenance cost by vehicle type and age

Identify top-performing vehicles (fuel efficiency)

Advanced Queries (CTEs + Window Functions)

Ranking vehicles within each make

Moving averages for maintenance cost

Identify above/below average performers

Analyze efficiency degradation with age

Compare cost-to-mileage ratios

Comparative Analysis

New vs old vehicle performance

Vehicle type efficiency analysis

Manufacturer-based maintenance cost patterns

________________________________________


**📊 Phase 3 — Power BI Dashboard**
1. Executive Summary Page

KPIs:

Total Vehicles

Average Fuel Efficiency

Total Mileage

Average Maintenance CosT

Visuals:

Vehicle distribution by type & make

Age distribution chart

<img width="1210" height="745" alt="Fleet manamgement power bi1" src="https://github.com/user-attachments/assets/ae18938e-ad47-463b-ae3b-eda27f339131" />


2. Performance Analysis Page

Scatter chart: Age vs Efficiency

Bar chart: Avg Efficiency by Make

Line chart: Maintenance Cost vs Mileage

Heat map: Performance Score Distribution

<img width="1202" height="737" alt="Fleet manamgement power bi2" src="https://github.com/user-attachments/assets/d200c035-b18d-450c-a4e2-5ec257391823" />


3. Cost Analysis Page

Maintenance cost by type

Cost-per-km analysis

Driver performance impact

Age vs maintenance cost trend

<img width="1200" height="755" alt="Fleet manamgement power bi3" src="https://github.com/user-attachments/assets/32c1bcbb-5128-4a55-bfc8-acc231461b99" />

________________________________________


**🎯 Expected Outcome**

A fully cleaned and transformed fleet dataset ready for analysis

Key insights into vehicle performance, fuel efficiency, maintenance costs, and driver impact

SQL-driven analytics identifying top-performing vehicles and efficiency patterns

An interactive Power BI dashboard presenting KPIs, visuals, and cost insights

Complete end-to-end experience in ETL, data analysis, SQL querying, and BI reporting

A fully cleaned and transformed fleet dataset ready for analysis

Key insights into vehicle performance, fuel efficiency, maintenance costs, and driver impact

SQL-driven analytics identifying top-performing vehicles and efficiency patterns

An interactive Power BI dashboard presenting KPIs, visuals, and cost insights

Complete end-to-end experience in ETL, data analysis, SQL querying, and BI reporting








