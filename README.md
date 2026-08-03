 💉 Vaccination Data Analysis and Visualization

Streamlit • MySQL • Power BI • SQL • Python • Public Health Analytics

An end-to-end data analytics project that explores global vaccination coverage using SQL, Streamlit, and Power BI. The project transforms raw vaccination data into interactive dashboards and actionable insights to support public health planning, disease prevention, and evidence-based decision-making.

📌 Project Overview

Vaccination programs play a critical role in preventing infectious diseases and improving population health. This project analyzes vaccination coverage across countries and regions to identify trends, measure program performance, and highlight areas requiring policy intervention.

The solution integrates MySQL for structured data management, Streamlit for interactive SQL-based analytics, and Power BI for executive dashboards and business intelligence reporting.

🎯 Objectives
Analyze vaccination coverage trends over time.
Compare vaccination performance across countries and WHO regions.
Identify areas with low vaccination uptake.
Support public health planning with data-driven insights.
Build interactive dashboards for technical and non-technical users.
🛠️ Technology Stack
Category	Tools
Programming	Python
Database	MySQL
Query Language	SQL
Dashboard	Streamlit
Business Intelligence	Power BI
Visualization	Altair, Power BI
Data Analysis	Pandas, NumPy


🗄️ Database Structure

Database: vaccination_project

Tables Used
coverage_data – Vaccination coverage and administered doses
country_master – Country and WHO region reference data
incidence_rate – Disease incidence statistics
reported_cases – Reported disease case counts
vaccine_introduction – Vaccine rollout information
vaccine_schedule – Immunization schedules and target populations


📊 Streamlit Dashboard

The Streamlit application provides interactive SQL-based analytics with 30 analytical questions, organized into three sections:

Easy Analysis
Vaccination coverage overview
Country comparisons
Coverage by vaccine
Intermediate Analysis
Trend analysis
Regional comparisons
Coverage distribution
Scenario-Based Analysis
Public health insights
Policy recommendations
Resource allocation scenarios
Features
Interactive SQL-powered dashboard
Dynamic charts and tables
Robust MySQL connectivity
Modular code structure
User-friendly interface


📈 Power BI Dashboard

The Power BI dashboard provides executive-level business intelligence with:

KPI cards
Country-wise vaccination comparison
WHO regional analysis
Vaccination trends over time
Vaccine-wise coverage analysis
Interactive slicers
Ranking visualizations
Heatmaps and comparative charts
💼 Business Use Cases
🏥 Public Health Planning
Monitor vaccination program performance
Identify low-coverage populations
Support immunization campaigns
🌍 Disease Prevention
Detect regions vulnerable to outbreaks
Evaluate vaccination effectiveness
Monitor disease control initiatives
📦 Resource Allocation
Optimize vaccine distribution
Forecast vaccine demand
Improve inventory planning
📊 Policy Support
Assist governments and health agencies
Enable evidence-based policy decisions
Support strategic vaccination planning
📈 Key Insights
Vaccination coverage varies significantly across countries and regions.
Certain vaccines achieve consistently higher uptake than others.
Trend analysis highlights improvements as well as regions requiring additional attention.
Interactive dashboards simplify monitoring and decision-making for healthcare stakeholders.
📂 Repository Structure
Vaccination-Data-Analysis/
│
├── app.py
├── README.md
├── requirements.txt
├── PowerBI_Dashboard.pbix
├── screenshots/
├── sql/
└── data/
🚀 Getting Started

Clone the Repository

git clone https://github.com/Ankitatan/VaccinationProject

cd Vaccination-Data-Analysis

Install Dependencies

pip install -r requirements.txt

Configure MySQL

Create the vaccination_project database.

Import the required tables.

Update the database credentials in app.py.

Run the Application

streamlit run app.py


Open the Power BI dashboard (PowerBI_Dashboard.pbix) for advanced analytics and executive reporting.

📸 Dashboard Preview

Add screenshots of your Streamlit and Power BI dashboards here.

Example:

<img width="2780" height="1373" alt="Screenshot 2026-08-03 232924" src="https://github.com/user-attachments/assets/2e23d9c8-2b4f-4ba7-906b-112bf18119df" />


<img width="2848" height="1419" alt="Screenshot 2026-08-03 232855" src="https://github.com/user-attachments/assets/626d547a-f7ec-48bd-a054-36ef7816c767" />


<img width="2831" height="1450" alt="Screenshot 2026-08-03 232638" src="https://github.com/user-attachments/assets/b6b277dc-3544-4d36-8b9d-cba07f635b34" />


✨ Skills Demonstrated
SQL Query Development
Database Design
Data Cleaning
Exploratory Data Analysis (EDA)
Data Visualization
Dashboard Development
Business Intelligence
Public Health Analytics
Streamlit Application Development
Power BI Reporting
Data Storytelling
🔮 Future Enhancements
Integrate live vaccination datasets through APIs.
Add machine learning models for vaccination trend forecasting.
Build interactive geographic heat maps.
Deploy the application on Streamlit Community Cloud.
Automate data refresh for real-time reporting.
👩‍💻 Author

Ankita Taneja

Aspiring Data Analyst | Data Scientist | Business Intelligence Enthusiast

🔗 GitHub: https://github.com/Ankitatan
💼 LinkedIn: https://www.linkedin.com/in/ankita-taneja-390613396/
⭐ Support

If you found this project helpful or interesting, consider giving the repository a ⭐ Star. It helps others discover the project and supports future development.
