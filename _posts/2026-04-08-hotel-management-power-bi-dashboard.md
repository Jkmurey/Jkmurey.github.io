---
title: "Hotel Management Power BI Dashboard"
date: 2026-04-08
category: [Power BI, Visualization]
---

## 📌 Overview
This project is a Business Intelligence dashboard built using Microsoft Power BI to analyze hotel performance, bookings, and revenue trends.
It simulates real-world hotel operations and supports data-driven decision-making.

---

## 🎯 Objectives
- Understand hotel booking patterns and occupancy trends
- Analyze revenue performance across time and room types
- Identify key business insights for decision-making
- Build an interactive dashboard using Power BI

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

