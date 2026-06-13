# Logistics Fleet Analytics Dashboard

## Overview

This project is an enterprise-style Power BI analytics solution designed to provide end-to-end visibility into transportation operations, customer profitability, fleet utilization, driver productivity, and safety performance.

The dashboard enables stakeholders to monitor operational KPIs, identify performance trends, investigate cost drivers, and perform detailed drill-through analysis at customer, truck, and driver levels.

---

## Business Objectives

* Monitor revenue and profitability trends
* Analyze customer value and revenue concentration
* Optimize fleet utilization and maintenance performance
* Evaluate driver productivity and efficiency
* Track safety incidents and risk exposure

---

## Dashboard Pages

### 1. Landing Page

Central navigation hub for the reporting solution.

### 2. Executive Overview

Enterprise KPI monitoring including Revenue, Profit, Loads, Miles, and On-Time Performance.

### 3. Financial & Customer Analytics

Customer value analysis, Pareto analysis, route profitability, and freight performance analysis.

### 4. Fleet & Asset Performance Analytics

Truck utilization monitoring, fuel cost analysis, maintenance cost tracking, and maintenance event analysis.

### 5. Driver Performance Analytics

Driver productivity analysis, performance scorecards, and workforce distribution.

### 6. Safety Performance Analytics

Incident monitoring, hotspot analysis, claims cost tracking, and risk assessment.

---

## Technical Highlights

* Power BI Desktop
* Star Schema Data Modeling
* Power Query Data Transformation
* 50+ DAX Measures
* Conditional Formatting
* Drill-Through Navigation
* Dynamic Titles
* KPI Scorecards
* Geospatial Analytics
* Interactive Filtering

---

## Project Scale

* Revenue Analyzed: $299M
* Loads: 85K+
* Fleet Assets: 120 Trucks
* Drivers: 124
* Safety Incidents: 170

---

## Advanced Features

* Customer Drill-Through Page
* Truck Drill-Through Page
* Driver Drill-Through Page
* About Dashboard Page
* Landing Page Navigation

---

## Data Model

The solution uses a star schema architecture consisting of:

### Dimension Tables

* DimDate
* DimCustomer
* DimDriver
* DimTruck
* DimRoute
* DimTrailer

### Fact Tables

* FactLoads
* FactTrips
* FactFuelPurchases
* FactMaintenance
* FactSafetyIncidents

### Aggregate Tables

* driver_monthly_metrics
* truck_utilization_metrics

---

## Author

Rohith T
