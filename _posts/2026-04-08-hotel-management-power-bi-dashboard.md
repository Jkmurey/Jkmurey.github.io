---
title: "Hotel Management Power BI Dashboard"
date: 2026-04-08
category: [Power BI, Visualization]
pin: true
---

## Project Overview
This is an end-to-end Business Intelligence project focused on analyzing hotel revenue, occupancy, pricing, and booking performance. The project involved transforming raw hotel data, developing a structured data model, creating DAX measures, and designing an interactive Power BI dashboard for business decision-making.
The project simulates real-world hotel operations and supports data-driven decision-making.

---

## Dashboard Preview
![Hotel Revenue Dashboard]({{ "/assets/img/hotel-revenue-dashboard.png" | relative_url }})
*Interactive Power BI dashboard showing hotel revenue, occupancy, RevPAR, ADR, DSRN, and Realisation performance.*

---
## Business Problem

Hotel management needs a clear and centralized view of business performance across properties, cities, room categories, and booking platforms. With key performance indicators such as revenue, occupancy, Average Daily Rate (ADR), Revenue per Available Room (RevPAR), Daily Sellable Room Nights (DSRN), and Realisation %, it can be difficult to identify performance differences and trends without an interactive analytical solution.

The challenge is to transform hotel booking and operational data into meaningful insights that enable management to monitor performance, compare properties, analyze booking channels, and identify changes in key metrics over time.

This project addresses this challenge by developing an interactive Power BI dashboard that brings together hotel performance data and presents key business metrics in a format that supports data-driven decision-making.


## Project Objectives
The main objectives of this project were to:
- Transform and prepare hotel data using Power Query to create clean, structured datasets for analysis.
- Develop a structured data model that connects hotel, room, date, and booking information for efficient analysis.
- Create DAX measures and KPIs to evaluate key metrics including Revenue, Occupancy %, ADR, RevPAR, DSRN, and Realisation %.
- Analyze hotel performance across properties, cities, room categories, and booking platforms.
- Identify performance trends by analyzing key metrics across different weeks and time periods.
- Build an interactive Power BI dashboard that allows users to filter and explore hotel performance and support data-driven decision-making.

---

## 🛠️ Tools & Technologies
- Microsoft Power BI
- Power Query (Data Cleaning & Transformation)
- DAX (Data Analysis Expressions)
- Star Schema Data Modeling

---

## 📊 Dataset
The dataset represents hotel operations data, including booking transactions, room details, and time-based information. It is designed to simulate a real-world hotel management system and support business intelligence analysis.

The data is structured into multiple tables following a dimensional model:

- Fact Table
Bookings: Contains transactional data such as booking dates, revenue, number of guests, and room allocations.
- Dimension Tables
Date (dim_date): Provides time-based attributes such as day, month, and year for trend analysis.
Rooms (dim_rooms): Includes room categories, types, and capacity details.

---

## 🔗 Data Relationships

The dataset follows a star schema, where:

- The bookings table acts as the central fact table
- Dimension tables (date, rooms) are connected via relationships

This structure enables efficient aggregation and filtering for reporting and analysis.


## 📊 Data Characteristics
The dataset contains both categorical data (room type, booking status) and numerical data (revenue, occupancy)
Time-series data allows trend and seasonality analysis
Supports calculation of key hotel KPIs such as:
- Revenue
- Occupancy Rate
- Average Daily Rate (ADR)
- RevPAR

  ---

## 🔢 Key DAX Measures
Examples of measures created:
- Total Revenue
- Occupancy Rate
- Average Daily Rate (ADR)
- Revenue per Available Room (RevPAR)

  ---

## 🎯 Business Relevance
This dataset helps answer key business questions such as:
- Which room types generate the most revenue?
- What are the peak booking periods?
- How does occupancy vary over time?
- What factors influence hotel performance?

---

## 📈 Dashboard Features
- Revenue trends over time
- Occupancy analysis by room type
- Booking patterns by date
- Key KPIs for hotel performance

 ---

 ## 📷 Dashboard Preview
#(Add screenshots in /images folder)

---

