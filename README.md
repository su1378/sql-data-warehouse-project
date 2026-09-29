# sql-data-warehouse-project
An end-to-end Data Warehouse and Analytics project built with Microsoft SQL Server, covering data ingestion, transformation, data modeling, and analytical reporting.

This project was completed during my earlier practical learning in SQL, Data Warehousing, Data Engineering, and Data Analytics and is included in my portfolio as an example of hands-on work with an end-to-end data warehouse solution.

📌 Project Overview
	
Domain	Sales & Customer Analytics
Database
Microsoft SQL Server
Architecture	
Medallion Architecture
Data Sources	
ERP & CRM
Data Format	CSV
Data Model	
Star Schema
Layers	Bronze → Silver → Gold
Focus	Data Engineering & Analytics

🏗️ Architecture
Bronze → Silver → Gold

🥉 Bronze — Raw Data
Raw ERP and CRM data loaded from CSV files into SQL Server.

🥈 Silver — Clean & Transform
Data cleansing, standardization, validation, and transformation.

🥇 Gold — Business Ready
Analytical data modeled using fact and dimension tables in a star schema.

Data Flow:
ERP / CRM CSV Files → Bronze → Silver → Gold → Analytics

🔧 What I Worked On

Designed a layered data warehouse architecture
Loaded raw ERP and CRM data into SQL Server
Developed ETL processes using T-SQL
Performed data cleansing and standardization
Identified and handled data quality issues
Integrated data from multiple source systems
Designed fact and dimension tables
Built a star schema for analytical queries
Developed SQL queries for business analysis
Created documentation for data architecture and data models
Applied data validation and quality checks

📊 Analytics

The Gold layer enables analysis of:
Customer Behavior
Product Performance
Sales Trends
Revenue & Sales Metrics
Customer & Product KPIs

🛠️ Tech Stack

Database & Development
SQL · T-SQL · Microsoft SQL Server · SSMS
Data Engineering
ETL · Data Cleaning · Data Transformation · Data Quality
Data Modeling
Data Warehousing · Star Schema · Fact & Dimension Tables · Medallion Architecture

Tools

Git · GitHub · Draw.io

## 📂 Repository Structure
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # Draw.io file showing different ETL techniques and methods
│   ├── data_architecture.drawio        # Draw.io file showing the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements for the project


📚 Documentation
Data Catalog
Data Requirements
Naming Conventions
Data Architecture
Data Flow
Data Models
ETL Process

👩‍💻 About Me

Hi, I'm Suzana Radosavljević, a Traffic Engineer with several years of professional experience in logistics, transportation, and data analysis.

My background in logistics has given me a strong understanding of operational processes, business requirements, performance metrics, and working with real-world data.

I have expanded my technical skill set into Data Analytics and Data Engineering, with a particular focus on SQL, data warehousing, ETL, data modeling, and business intelligence.

I am especially interested in combining my logistics and transportation domain knowledge with data technologies to transform operational data into meaningful insights and support data-driven decision-making.

Areas of Interest
Data Analytics · SQL · Data Engineering · Data Warehousing · Business Intelligence · ETL · Data Modeling · KPI Analysis · Logistics & Supply Chain Analytics

⭐ Credits

This project was completed as part of my learning journey, using the educational materials and project guidance provided by Baraa Khatib Salkini (Data With Baraa).
The original project and learning resources are available here:
Data With Baraa – SQL Data Warehouse Project
All original educational credits are retained and acknowledged.
