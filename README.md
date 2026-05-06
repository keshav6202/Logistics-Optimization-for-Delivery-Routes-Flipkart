# 🚚 Flipkart Logistics Optimization & Delivery Analytics

## 📌 Project Overview
Flipkart, through its logistics arm Ekart Logistics, manages millions of deliveries daily across India. During festive seasons and peak demand periods, the logistics network faces operational challenges such as route inefficiencies, warehouse bottlenecks, and traffic-related delivery delays.

This project focuses on building a **SQL-driven analytics system** to analyze shipment operations, identify delivery bottlenecks, optimize routes, and evaluate delivery agent performance using simulated logistics data.

---

## 🎯 Project Objectives

- Identify root causes of delayed deliveries
- Analyze traffic and warehouse processing inefficiencies
- Optimize delivery routes using performance metrics
- Evaluate delivery agent productivity and efficiency
- Generate actionable insights for logistics improvement

---

## 📊 Dataset Schema

The project uses five relational datasets:

### 1. Orders
Contains delivery details, timestamps, customer region, and order status.

### 2. Routes
Includes source/destination locations, route distance, and historical traffic delay information.

### 3. Warehouses
Stores warehouse capacity, processing times, and operational efficiency metrics.

### 4. Delivery Agents
Contains delivery speed, experience level, efficiency ratings, and performance scores.

### 5. Shipment Tracking
Tracks shipment movement through checkpoints and real-time logistics updates.

---

## 🛠️ Tasks Performed

### 🔹 Data Cleaning & Preparation
- Removed duplicate records
- Handled missing traffic delay values using route-level averages
- Standardized date formats to `YYYY-MM-DD`
- Validated inconsistent records such as:
  - Delivery dates before order dates
  - Negative processing durations

### 🔹 Delivery Delay Analysis
- Calculated delivery delays for each order
- Identified Top 10 delayed routes
- Ranked delayed shipments warehouse-wise using SQL Window Functions

### 🔹 Route Optimization
- Calculated Distance-to-Time efficiency ratios
- Identified inefficient routes with high traffic delays
- Detected routes where more than 20% of deliveries were delayed

### 🔹 Warehouse & Agent Performance
- Identified bottleneck warehouses using Common Table Expressions (CTEs)
- Ranked delivery agents using On-Time Delivery Percentage (OTD%)
- Compared top-performing and low-performing agents using subqueries

### 🔹 KPI Reporting
Generated business KPIs including:
- Average Delivery Delay per Region
- On-Time Delivery Percentage (OTD%)
- Average Traffic Delay per Route
- Warehouse Processing Efficiency
- Agent Productivity Metrics

---

## 📈 Key Formula Used

### On-Time Delivery Percentage (OTD%)

\[
OTD\% = \left( \frac{\text{Total On-Time Deliveries}}{\text{Total Deliveries}} \right) \times 100
\]

Where:

- **Total On-Time Deliveries** = Deliveries completed within expected delivery time
- **Total Deliveries** = Overall completed deliveries

---

## 💡 SQL Concepts Used

- Joins
- Subqueries
- Common Table Expressions (CTEs)
- Window Functions
- Aggregate Functions
- CASE Statements
- Ranking Functions
- Group By & Having Clauses

---

## 📂 Deliverables

### 📄 SQL Script
Contains:
- Data cleaning queries
- Analytical SQL queries
- KPI generation scripts

### 📊 PowerPoint Presentation
Includes:
- Visual charts
- Route performance analysis
- Warehouse bottleneck insights
- Agent performance dashboards

### 🎥 Project Walkthrough Video
Explains:
- Dataset structure
- SQL logic
- Key findings
- Business recommendations

---

## 🚀 How to Run the Project

1. Import the datasets into your SQL environment:
   - MySQL
   - PostgreSQL
   - SQL Server

2. Execute the `Logistics_Optimization.sql` script.

3. Review the generated result tables and KPI outputs.

---

## 📌 Key Insights

- Traffic congestion significantly impacts delivery timelines on high-volume routes.
- Certain warehouses operate consistently above average processing time, creating bottlenecks.
- Experienced delivery agents maintain higher OTD percentages compared to low-experience agents.
- Route optimization can reduce overall delivery delays and operational costs.

---

## 🧰 Technologies Used

- SQL
- MySQL / PostgreSQL / SQL Server
- Data Analytics
- Business Intelligence Concepts

---

## 📖 Note

This project was developed as part of a logistics optimization case study.  
All analysis is performed on simulated datasets representing Flipkart's supply chain and logistics operations.

---

## 👨‍💻 Author

**Keshav Kumar**  
B.Tech CSE | Data Analytics & SQL Enthusiast
