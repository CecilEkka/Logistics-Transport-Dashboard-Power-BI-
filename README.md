# 🚢 Logistics & Transport Dashboard (Power BI)

This project delivers a comprehensive business intelligence dashboard that analyzes global shipping performance through financial, operational, and logistics metrics. Built using **Power BI** and **SQL**, the dashboard enables data-driven decisions by logistics managers, shipping carriers, and analysts.

## 📋 Table of Contents

- [Project Objective](#-project-objective)  
- [Dataset Description](#-dataset-description)  
- [Methodology](#-methodology)  
- [Dashboard Snapshots](#-dashboard-snapshots)  
- [SQL Analysis](#-sql-analysis)

## 🎯 Project Objective

The goal of this project is to visualize and analyze shipping and logistics data to understand trends in **revenue, cost, profit, delivery performance, and container movement**. The dashboard empowers decision-makers in the **transport and supply chain industry** to identify inefficiencies, improve delivery performance, and enhance profit margins.

## 📦 Dataset Description

The dataset used includes **14,000+ TEUs across 6,760 containers**, with detailed shipping metrics:

- **Origin Country, Company, Carrier, Vessel Type**  
- **Shipment Dates (Day, Month, Quarter, Year)**  
- **Container Type**: 20’GP, 40’HC, 40’RF  
- **Freight Revenue, Freight Cost, Profit, Margin**  
- **Delivery Metrics**: On-time Delivery %, Average Delay (days)  
- **Transshipment Flag**  

## ⚙️ Methodology

1. **Data Cleaning and Preparation**  
   - Processed raw CSV using Power BI Power Query  
   - Validated data types, standardized entries, removed duplicates

2. **Data Modeling**  
   - Created relationships between container, shipment, and performance tables  
   - Defined measures and calculated columns using **DAX**

3. **Dashboard Design**  
   - Developed multiple pages for Executive Overview, Financial Analysis, Operational Efficiency, and Map-based Insights  
   - Used **drill-through filters**, **interactive slicers**, and **bookmark navigations** for seamless exploration

4. **KPIs and Metrics**  
   - Total Revenue: **$3.55M**  
   - Total Cost: **$2.71M**  
   - Total Profit: **$835K**  
   - Avg Profit Margin: **23.5%**  
   - On-Time Delivery: **31%**  
   - Avg Delay: **2.41 Days**  
   - TEU per Shipment: **70.49**

## 📊 Dashboard Snapshots

The Power BI dashboard consists of the following pages:

### Landing Page
![Landing Page](https://github.com/CecilEkka/Logistics-Transport-Dashboard-Power-BI-/blob/main/Dashboard_Image/1.home.png)
This is the main entry point of the dashboard. It provides a brief introduction to the project and features navigation buttons that allow users to jump to specific analysis pages:

## 📊 **1. Executive Overview**

Purpose: High-level KPIs and filters for instant visibility across the shipping ecosystem.

![Executive Overview](https://github.com/CecilEkka/Logistics-Transport-Dashboard-Power-BI-/blob/main/Dashboard_Image/2.Overview.png)

Key Features:

* **KPI Cards**: Revenue, Cost, Profit, Profit Margin, Avg Delay,
* **On-Time % Filters**: Company, Container Type, Country 
* **Essence**: Offers a quick snapshot of global shipping performance---ideal for managers tracking profit and delays at a glance.



## 💰 **2. Financial Performance**

Purpose: Revenue, cost, and profit trends by month, container type, and company.

![Financial Performance](https://github.com/CecilEkka/Logistics-Transport-Dashboard-Power-BI-/blob/main/Dashboard_Image/3.Financial.png)

Key Features:

* **Bar Charts & Line Graphs**: Revenue vs. Cost by Company and Container Type 
* **Matrix View**: Profit margins segmented by container and month
 * **Insights**: Identify which carrier or container is generating higher profits or incurring loss.



## 📦 **3. Operational Efficiency**

Purpose: Metrics on TEUs, shipments, delays, and transshipments with container-wise breakdowns.

![Operational Efficiency](https://github.com/CecilEkka/Logistics-Transport-Dashboard-Power-BI-/blob/main/Dashboard_Image/4.Operations.png)

**Key Features:**

* **KPI Cards**: TEU totals, Transshipment %, Avg Delay 
* **Visuals**: Container handling costs, Shipment breakdowns Transshipment analysis 
* **Highlights**: Pinpoint bottlenecks and delay contributors, such as container types or shipping routes.



## 🌍 **4. Map Overview**

Purpose: Country-wise container movement and profitability with dynamic filters.

![Map Overview](https://github.com/CecilEkka/Logistics-Transport-Dashboard-Power-BI-/blob/main/Dashboard_Image/5.MAP.png)

Key Features:

* **Map Visual**: Shipment origin country vs. revenue contribution
* **Slicer/Filter**: Country, Carrier, Month 
* **Usefulness**:Understand which regions contribute most to profit and where delays or costs are higher.


## 📂 **5. Shipment Detail View (Drill-Through Page)**

Purpose: Shipment-level records with all metrics – accessible via **drill-throughs** and bookmarks.
![Details View](https://github.com/CecilEkka/Logistics-Transport-Dashboard-Power-BI-/blob/main/Dashboard_Image/6.DETAILS.png)

Key Features:
* **Drill-through Functionality**: Navigate from high-level views
into detailed records 
* **Tables**: Full shipment details --- including Container ID, Type, Dates, Delay, Carrier, Cost & Revenue 
* **Bookmarks**: Used for toggling specific filters and views easily
* **Benefit**: Allows operational analysts to isolate and investigate outliers or problematic shipments.


## 🛠️ **Advanced Features Across Pages**

* **Drill-throughs**: Users can right-click and navigate from summary to detail pages (e.g., by container or company) 
* **Bookmarks**: Used to switch between different filtered views or highlight layouts without clutter 
* **Interactive Slicers**: Country, Company, Container Type Vessel, Month


## 🧮 SQL Analysis

Although the dashboard is built in Power BI, SQL logic was simulated to explore:

- Aggregations of **total revenue/cost/profit** by carrier and container type  
- **Monthly and quarterly trends** in TEU handling  
- Delivery performance analysis using transshipment flags and delay metrics  
- Profit margin classification (low, medium, high) for route optimization



## 🛠️ Tech Stack

- **Power BI Desktop**: Data modeling, visualization, DAX  
- **SQL (Simulated logic)**: Aggregations and analysis concepts  
- **Power Query**: ETL and data transformation  
- **DAX**: KPIs, calculated fields, and measures

## 🔍 Key Findings

- **40’RF** containers are the most profitable and least delayed  
- Only **31%** of shipments were delivered on time—major scope for optimization  
- Companies like **Neptune Freight** and **Atlas Maritime** had highest container volumes  
- Transshipments account for **46%** of shipments, increasing potential risk and delays

> 📁 This dashboard simulates a real-world logistics use case and provides a blueprint for data-driven performance management in the shipping and supply chain sector.
