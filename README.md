# Patient Wait List Dashboard

## Overview:

## Table of Contents:

- [Project Presentation](#project-presentation)
- [Live Dashboard](#live-dashboard)
- [Tools & Technique used](#tools--technique)
- [Problem Statement](#problem-statement)
- [Goal & Purpose](#goal--purpose)
- [Business Model](#business-model)
- [Feature Requests](#feature-requests)
- [Data Source](#data-source)
- [Data Modeling](#data-modeling)
- [Key Metrics](#key-metrics)
- [Dashboard Overview](#dashboard-overview)
- [Insights & Recommendations](#insights-and-recommendations)
- 
## Project Presentation
This project presents an interactive dashboard for tracking and analyzing patient wait lists across various medical specialties. It provides real-time insights into trends, case distributions, and overall demand for healthcare services.

## Live Dashboard:

Checkout the live dashboard here 👉🏻 [Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiOTQyODU5OGMtMGQ1My00OTkyLTk0ZTItN2I2MDZiMDY1Yjg3IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)
  
## Tools & Technique:
### Data Analysis:
Microsoft Excel (2021)
Power BI Desktop (July 2024)
Power BI Service, Power Query
Data Modeling, DAX, ETL, DAX Studio

#### Database:
SQL, MySQL, MySQL Workbench

#### Project Documentation:
Git & GitHub, VS Code Editor

## Problem Statement:
AtliQ Hardware, a fast-growing electronics company, currently relies on Excel files for its data analysis, which hampers the ability to generate actionable insights. This lack of effective analytics has caused substantial losses in the Latin American market. The senior executives have decided to invest in a comprehensive data analytics project to improve decision-making and drive business growth.

## Goal & Purpose:

 - Provide an intuitive dashboard for tracking patient wait lists.
- Help administrators identify bottlenecks and trends.
- Assist in predicting future demand for healthcare services.

## Business Model:

This project could be leveraged as a subscription-based service for healthcare facilities seeking actionable insights into patient flow and wait list management.

<p align="center">
<img src="https://github.com/Deepthi3245/Business--Insight--360/blob/d10c0f170d5b5428d4ff418140eded3602cf4a27/Projects%20Views/ATLIQ.png" >
</p>

#### Retail: Third-party stores (e.g., Croma, Amazon).
#### Direct: AtliQ-owned stores (e.g., AtliQ e-store).
#### Distributor: Agencies handling international distribution (e.g., Neptune in countries with import restrictions).

AtliQ manufactures computer hardware and distributes its products through various channels:
<p align="center">
<img src="https://github.com/Deepthi3245/Business--Insight--360/blob/d10c0f170d5b5428d4ff418140eded3602cf4a27/Projects%20Views/ATLIQ%202.png" >
</p>

## Feature Requests
Future improvements may include:
- Predictive analytics for wait time forecasting.
- Automated alerts for critical wait list thresholds.
- Integration with electronic health record (EHR) systems.


## Data Source
Data is aggregated from hospital records, patient management systems, and external healthcare databases.

Internal AtliQ Database: Contains both fact and dimension tables for sales, inventory, and financial data.
<p align="center">
<img src="https://github.com/Deepthi3245/Business--Insight--360/blob/3f25349aa2c18342a8473e8fbfa24c95a4029c69/Database-Structure/database%201.png" >
</p>

<p align="center">
<img src="https://github.com/Deepthi3245/Business--Insight--360/blob/3f25349aa2c18342a8473e8fbfa24c95a4029c69/Database-Structure/database%202.png" >
</p>
External Data: Additional .xlsx/.csv files for benchmark and market share data. The fiscal year for AtliQ starts in September, with data spanning from FY 2018 to FY 2022. Sales data is available through December 2021.

## Data Modeling
Structured datasets are modeled using SQL and cleaned using Python (pandas). The data is then processed to generate insights used in dashboard visualizations.
<p align="center">
<img src="https://github.com/Deepthi3245/Business--Insight--360/blob/d10c0f170d5b5428d4ff418140eded3602cf4a27/Data%20Modeling/Data%20modeling%20gif.mp4" >
</p>


# Key Metrics
- **Total patients in the wait list**
- **Average wait time per specialty**
- **Monthly trend analysis**
- **Demand per medical specialty**
- **Critical capacity alerts**


## Dashboard Overview:
<p align="center"> Home Page </p>
<p align="center">
  <img src="https://github.com/Deepthi3245/Business--Insight--360/blob/d10c0f170d5b5428d4ff418140eded3602cf4a27/Projects%20Views/Home.png">
</p>

<p align="center"> <strong>Finance Page </strong></p>
<p align="center"> Get P & L statement for any customer / product / country or aggregation of the above over any time period and More. </p>

<p align="center">
  <img src="https://github.com/Deepthi3245/Business--Insight--360/blob/d10c0f170d5b5428d4ff418140eded3602cf4a27/Projects%20Views/Finance.png">
</p>

## Dashboard Overview
The dashboard provides multiple views, including:
- **Overall patient wait lists**
- **Breakdown by specialty**
- **Historical trends**
- **Forecasted demand projections**

## Insights & Recommendations
- **High-demand specialties** require resource allocation adjustments.
- **Seasonal fluctuations** indicate the need for flexible staffing.
- **Reducing wait times** through better scheduling and prioritization can improve patient satisfaction.




