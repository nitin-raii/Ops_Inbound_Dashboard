# Inbound Logistics Capacity Analysis

## Objective

The goal of this project is to analyze inbound vehicle arrival patterns and evaluate dock capacity requirements across different hours of the day. The analysis focuses on identifying peak load windows, understanding volume distribution, and highlighting capacity gaps in inbound operations.

---

## Tools Used

* Excel (data preparation)
* MySQL (data querying and aggregation)
* Power BI (data visualization and dashboarding)

---

## Dataset

The dataset represents 14 days of inbound vehicle arrivals with the following fields:

* Date
* Vehicle_Number
* Previous_Node
* Origin_Type (Milkrun / Longhaul)
* Vehicle_Size
* Arrival_Time
* Volume
* Dock_Capacity
* Required_Docks
* Hour

---

## Approach

### 1. Data Preparation

* Cleaned and structured raw data in Excel
* Standardized column names and formats
* Derived hourly data for analysis

---

### 2. SQL Analysis

Key queries performed:

* Hourly dock demand calculation
* Volume aggregation by hour
* Peak hour identification
* Comparison of required vs available dock capacity

---

### 3. Dashboard Development

A Power BI dashboard was created to visualize:

* Dock Demand (Average per Day by Hour)
* Inbound Volume (Average per Day by Hour)

The dashboard highlights how inbound flow varies across the day and how it impacts dock utilization.

---

## Key Insights

* Inbound volume is highly concentrated between **14:00–16:00**, creating a sharp spike in dock demand.

* Peak dock requirement exceeds available capacity (7 docks) by a significant margin, indicating a clear operational bottleneck.

* Volume and dock demand trends are closely aligned, confirming that arrival timing directly drives capacity stress.

* Early morning and late evening hours show relatively low load, suggesting opportunities for load balancing and better scheduling.

---

## Conclusion

The analysis demonstrates a strong mismatch between inbound arrival patterns and available dock capacity. Without intervention, peak-hour congestion is likely to result in delays, inefficiencies, and operational strain.

This project highlights how data-driven insights can support better capacity planning, workforce allocation, and scheduling decisions in logistics operations.

---

## Files in Repository

* `data/vehicle_arrival_data.csv` → Raw dataset
* `sql/queries.sql` → SQL queries used for analysis
* `dashboard/inbound_capacity_dashboard.pbix` → Power BI dashboard
* `README.md` → Project documentation

---

## Dashboard Preview

![Dashboard](dashboard/inbound_view_dashboard.png)


## Future Scope

* Introduce forecasting for volume distribution
* Simulate backlog and rollover capacity
* Optimize dock allocation strategies
