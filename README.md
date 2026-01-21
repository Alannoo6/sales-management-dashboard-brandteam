# Sales Management Dashboard (Power BI) – Commercial Performance Analysis

## Overview
This project presents an interactive Power BI dashboard for comprehensive commercial performance analysis of Brandteam’s Sports Brands business unit, based on real sales data from 2021 to 2025.

The dashboard enables analysis of sales performance by client, salesperson, product, brand and region, supporting data-driven decision making for commercial and management teams.

It includes client and salesperson rankings, brand and product family analysis, geographic distribution and dynamic filters to identify growth drivers and optimization opportunities.

> **Disclaimer:** All datasets, table names, business identifiers and sensitive information have been fully anonymized to preserve confidentiality and comply with corporate data protection policies. This repository is for demonstration purposes only.

---

## Business Problem
Commercial teams require consolidated and reliable visibility into sales performance across multiple dimensions in order to:

- Identify top and underperforming clients and sales representatives  
- Analyze product, brand and category performance  
- Detect geographic trends and regional opportunities  
- Support strategic planning and operational decision making  

This dashboard centralizes transactional sales data into a single analytical model to provide a unified and interactive reporting solution.

---

## Project Objective
Develop a management dashboard to monitor commercial performance, enabling the analysis of sales by client, salesperson, product, division and region.

The objective is to provide a flexible analytical tool that allows business users to explore performance indicators, detect trends and support data-driven decisions.

---

## Architecture & Data Flow

The analytical workflow follows a standard BI pipeline:

- Extract transactional sales data from SQL Server  
- Transform and model data into an analytical dataset  
- Build a semantic model with calculated measures using DAX  
- Visualize KPIs and performance indicators in Power BI  

This approach ensures data consistency between transactional systems and analytical reporting while maintaining scalable and reusable data models.

---

## Key Features
- Interactive dashboards with dynamic filters and slicers  
- Client and salesperson ranking analysis  
- Brand, product family and category performance views  
- Geographic sales distribution and regional performance analysis  
- Time-based analysis across multiple years (2021–2025)  
- KPI monitoring for commercial performance  

---

## Business Impact
This dashboard helps:

- Improve visibility into commercial performance across multiple business dimensions  
- Identify growth opportunities and underperforming segments  
- Support sales strategy and territory planning  
- Reduce manual reporting effort by centralizing analytics in a single platform  
- Improve data quality and consistency for management reporting  

---

## Technologies Used
- **SQL Server** — data extraction and dataset construction  
- **Power BI** — data visualization and interactive dashboards  
- **DAX** — measures and business logic for advanced analytics  
- **GitHub** — version control and project documentation  

---

## Dataset Preparation
As a first step, data was extracted from a transactional database hosted on SQL Server.

SQL scripts were developed to build the base dataset used as the data source for analysis and visualization in Power BI.

The scripts used in this stage can be found in the following folder:

