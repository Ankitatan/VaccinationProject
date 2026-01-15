# VaccinationProject

Global Vaccination Analytics Project

(Streamlit + MySQL + Power BI)

Project Overview

This project analyzes global vaccination data to derive meaningful public health insights using SQL, Streamlit, and Power BI. The objective is to evaluate vaccination coverage trends, regional disparities, vaccine performance, and potential public health risks to support policy decisions, resource allocation, and disease prevention strategies.

The project is designed with:

30 analytical questions (Easy, Medium, Scenario-based)

Single-table SQL queries for robustness and exam safety

Interactive Streamlit dashboard for SQL-driven analysis

Power BI dashboard for advanced visual analytics and executive reporting

Tech Stack

Database: MySQL

Backend & Visualization: Streamlit, Pandas, Altair

BI Tool: Microsoft Power BI

Language: Python, SQL

Data Source

Database: vaccination_project
Primary table used for analysis:

coverage_data

Supporting reference tables (used in Power BI modeling):

country_master

vaccination_coverage

vaccine_schedule

vaccine_introduction

reported_cases

incidence_rate

Streamlit Dashboard

The Streamlit application (app.py) contains:

30 fully implemented analytical questions

Organized into three tabs:

Easy Questions (Descriptive analytics)

Medium Questions (Comparative & trend analysis)

Scenario-Based Insights (Policy and public health decisions)

Direct SQL execution with zero joins for safety

Charts generated question-wise (line charts, bar charts, tables)

Power BI Dashboard (Additional Analysis)

In addition to Streamlit, a Power BI dashboard has been created to provide:

High-level executive summaries

Interactive slicing by Year, Country, WHO Region, Antigen

Advanced visuals such as:

KPI cards (Average Coverage %, Total Doses, Target Population)

Coverage trends over time

Country-wise and antigen-wise comparisons

Regional heatmaps and geographic visualization

Incidence rate vs vaccination coverage comparison

The Power BI dashboard complements Streamlit by offering decision-oriented reporting suitable for senior stakeholders and policy makers.

Insights and Actionability
Public Health Policy

Identifies regions and countries with consistently low vaccination coverage, enabling targeted policy intervention.

Highlights high-performing and underperforming vaccines, supporting evidence-based immunization strategies.

Tracks long-term trends to evaluate the impact of vaccination programs over time.

Resource Allocation

Helps governments and global health organizations prioritize vaccine distribution to low-coverage regions.

Assists in forecasting vaccine demand using historical target population and dose data.

Supports equitable allocation of healthcare resources across WHO regions.

Disease Prevention Strategies

Correlates vaccination coverage with reported disease incidence (via Power BI).

Identifies high-risk regions where low coverage may lead to outbreaks.

Enables proactive planning for mass immunization campaigns.

Overall, the Power BI reports transform raw vaccination data into actionable insights, supporting data-driven decisions in global health management.

🧠 Key Analytics Covered
✅ Easy Level (Single-table)

Vaccination coverage trends by year

Average coverage by antigen

Total doses administered per year

Countries reporting vaccination data

Minimum and maximum coverage analysis

✅ Medium Level (Multi-table Joins)

Regional vaccination performance (WHO regions)

Bottom 10 countries by coverage

Vaccine geographic spread

Dose utilization vs target population

Vaccine diversity across regions

✅ Scenario-Based (Public Health Insights)

Identification of low-coverage countries (<60%)

Outbreak risk regions

Priority disease vaccine analysis (Polio, Measles, HepB)

Projected vaccine demand

Progress toward WHO’s 95% coverage goal

🗄️ Database Schema

Database Name: vaccination_project

Tables Used

country_master

coverage_data

vaccination_coverage

vaccine_introduction

vaccine_schedule

reported_cases

incidence_rate

Relational joins are performed using ISO country codes.

🛠️ Tech Stack
Layer	Technology
Frontend	Streamlit
Backend	Python
Database	MySQL
Data Processing	Pandas
Visualization	Altair | Power BI
Connectivity	mysql-connector

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone <repository-url>
cd vaccination_project

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ MySQL Configuration

Ensure MySQL is running and the database is available:

CREATE DATABASE vaccination_project;


Import the provided SQL dump or tables before running the app.

🔐 Database Connection

The application uses a cached MySQL connection via:

@st.cache_resource
def get_connection():


This ensures optimized performance and avoids repeated connections.

Credentials are currently hardcoded for local execution.

▶️ Run the Application
streamlit run app.py


The dashboard opens in your default browser.

📊 Dashboard Structure

No Sidebar (Full-Width Layout)

Three Tabs

Easy Questions

Medium Questions

Scenario-Based Insights

30 Analytical Questions

Interactive charts and tabular outputs

📈 Business & Public Health Value

Identifies vaccination gaps at country and regional levels

Supports data-driven policy formulation

Helps forecast vaccine demand

Highlights progress toward global immunization goals

📚 Learning Outcomes

Advanced SQL joins and aggregations

End-to-end analytics pipeline

Streamlit dashboard design

Public-health data interpretation

Real-world scenario-based analysis

🧾 Final Notes

This project is suitable for:

Data Analyst / Data Scientist portfolios

Public health analytics case studies

SQL + Python dashboard demonstrations

Academic and internship evaluations

Author: Ankita Taneja
Tools: Streamlit | MySQL | Python | Altair | Power BI
Domain: Public Health & Vaccination Analytics
