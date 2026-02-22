# NGO-Data-Architecture-Looker-Studio-Dashboard-SQL-Google-Sheets
End-to-end data solution for an NGO: SQL database design, ETL from Google Sheets, and interactive Looker Studio dashboards for financial tracking.

🕊️ Potenciar Solidario: NGO Data Architecture & Analytics

Project Overview
This project involved designing and implementing a professional data infrastructure for Potenciar Solidario, a Non-Profit Organization. The goal was to transition from fragmented spreadsheets to a centralized relational database system, enabling real-time tracking of donations, expenses, and social impact from 2018 to 2024.

🚀 Tech Stack
Database Design: SQL (MySQL) for schema architecture and relational integrity.

Data Engineering: Google Sheets & Excel for ETL (Extract, Transform, Load) and data cleaning.

Business Intelligence: Looker Studio for interactive financial and operational dashboards.

Documentation: Entity-Relationship Diagrams (ERD) and detailed Data Dictionaries.

🛠️ Key Features & Deliverables
1. Relational Database Design (SQL)
I designed a scalable SQL schema to ensure a "Single Source of Truth."

Optimized Tables: Created structured entities for Donors, Suppliers, Employees, and Expenses.

Data Integrity: Implemented ENUM types for strict data validation and FOREIGN KEY constraints to link donations with specific projects.

Scalability: The architecture supports historical tracking of $167M+ in total revenue and $57M+ in expenses.

2. Interactive Business Intelligence (Looker Studio)
I developed a multi-page dashboard to provide actionable insights for NGO leadership:

Revenue Analysis: Tracked income with geographic heatmaps and donor frequency segmentation (Annual, Monthly, etc.).

Expense Management: Detailed breakdown of expenditures categorized by sectors like Construction, Technology, and Education.

Supplier Performance: Identification of Top 5 suppliers and spending trends by year.

📈 Business Impact
Transparency: Enabled 100% visibility into fund allocation across different business sectors.

Strategic Growth: Identified the most profitable donor regions to optimize fundraising campaigns.

Efficiency: Automated the data consolidation process, reducing manual reporting time.

📁 Project Structure
/sql_schema: SQL DDL scripts and database definitions.

/documentation: Entity-Relationship Diagram (ERD) and Data Dictionary.

/dashboards: PDF exports of the interactive Looker Studio reports.

/data_raw: Sample datasets used for the analysis.
