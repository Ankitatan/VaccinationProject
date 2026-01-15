Vaccination Data Analysis and Visualization

Streamlit | MySQL | Power BI | Public Health Analytics

📌 Project Overview

This project analyzes global vaccination coverage data to uncover trends, regional disparities, and actionable public health insights. The analysis is implemented using MySQL for data storage, Streamlit for SQL-driven analytics, and Power BI for advanced business intelligence dashboards.

The solution supports policy-making, disease prevention, and resource allocation decisions for governments and health organizations.

🧠 Problem Statement

Analyze global vaccination data to understand:

Vaccination coverage trends over time

Regional and country-level disparities

Vaccine performance and uptake

Public health risks due to low vaccination coverage

The cleaned data is stored in a normalized SQL database, visualized through Streamlit dashboards, and further analyzed using Power BI.

🎯 Business Use Cases
Public Health Strategy

Identify regions with low vaccination coverage

Evaluate vaccination program effectiveness

Support booster dose and new vaccine policies

Disease Prevention

Detect high-risk regions prone to outbreaks

Assess impact of vaccination on disease reduction

Resource Allocation

Optimize vaccine supply distribution

Forecast vaccine demand based on historical trends

Global Health Policy

Enable data-driven vaccination policies

Support WHO and government health initiatives

🛠️ Tech Stack
Component	Technology
Database	MySQL
Backend Analytics	Python
Dashboard	Streamlit
BI Tool	Power BI
Visualization	Altair, Power BI
Query Language	SQL
🗂️ Dataset Description

Database: vaccination_project

Tables Used

coverage_data – Vaccination coverage and dose data

country_master – Country and WHO region reference

incidence_rate – Disease incidence rates

reported_cases – Disease case counts

vaccine_introduction – Vaccine rollout information

vaccine_schedule – Vaccine schedule and target population

📊 Streamlit Dashboard

The Streamlit app (app.py) provides:

30 analytical questions fully implemented

Single-table SQL queries only (exam-safe, zero empty graphs)

Organized into three tabs:

Easy Questions (10)

Medium Questions (10)

Scenario-Based Insights (10)

Question-wise charts (line, bar, tables)

Robust MySQL connection handling

📈 Power BI Dashboard

A separate Power BI dashboard is created for advanced analytics and executive reporting.

Power BI Features

KPI cards (Average Coverage, Total Doses, Target Population)

Country & WHO region comparisons

Year-wise vaccination trends

Antigen-wise coverage analysis

Interactive slicers (Country, Year, Region, Vaccine)

Heatmaps and ranking visuals

Power BI complements Streamlit by providing high-level insights suitable for decision-makers.

🔍 Insights and Actionability
Public Health Policy

Identifies low-coverage regions for targeted intervention

Evaluates vaccine effectiveness across regions and time

Resource Allocation

Supports data-driven vaccine distribution planning

Helps forecast future vaccine demand

Disease Prevention

Highlights outbreak-prone regions due to low coverage

Assists in proactive vaccination campaign planning

The Power BI reports convert complex vaccination data into clear, actionable insights for public health authorities.

📁 Repository Structure
📦 Vaccination-Data-Analysis
 ┣ 📄 app.py
 ┣ 📄 README.md
 ┣ 📊 PowerBI_Dashboard.pbix
 ┣ 📁 screenshots (optional)

✅ Project Highlights

30/30 questions implemented (no skips)

Zero SQL join errors in Streamlit

Power BI used for advanced visualization

Fully viva-ready and evaluation-compliant

Clean, modular, and documented code

🧪 How to Run the Project

Clone the repository

Set up MySQL and import the database

Update database credentials in app.py

Run:

streamlit run app.py


Open Power BI file for advanced insights

📌 Evaluation Readiness

This project meets all evaluation criteria:

Data cleaning and normalization

SQL integrity and structure

Interactive dashboards

Actionable insights and business relevance

👤 Author

Ankita Taneja
Aspiring Data Scientist | Healthcare & Analytics Projects
