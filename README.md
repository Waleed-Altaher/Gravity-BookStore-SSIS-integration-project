# Gravity-BookStore-SSIS-integration-project

Gravity Books Sales End-to-End Project
Logo

Table of Contents
Introduction
Project Phases
Data Source
Technologies Used
Getting Started
ETL Phase
Analysis Phase
Reporting Phase
Contributing
License
Introduction
Welcome to the Gravity Books Sales End-to-End Project repository. This project is an exemplary demonstration of a complete data warehousing solution, encompassing the Extract, Transform, Load (ETL) phase, analysis phase with SQL Server Analysis Services (SSAS), and reporting phase using Pivot Table and Power BI.

Project Phases
ETL (Extract, Transform, Load): In this phase, data is extracted from a transactional database called "Gravity Book Sales," transformed to meet data warehousing requirements, and loaded into a structured data warehouse.
Analysis: The data is modeled and structured for efficient querying and analysis using SQL Server Analysis Services (SSAS).
Reporting: Interactive reports and visualizations are created using Pivot Table in Excel and Power BI, allowing end-users to derive insights from the data.
Data Source
The source dataset for this project is the "Gravity Book Sales" database, which can be found here. This transactional database serves as the foundation for the end-to-end project.

Technologies Used
SQL Server Integration Services (SSIS)
SQL Server Analysis Services (SSAS)
Pivot Table (Excel)
Power BI
Getting Started
To explore and replicate the project, follow these steps:

Clone this repository to your local machine.
Download and install SQL Server if not already installed.
Follow the instructions in the respective folders for each project phase (ETL, Analysis, Reporting) to set up and execute the code.
ETL Phase
DDL statements of table creation and the DWH Schema

Customer Dimension

DDL Customer Dim

Book Dimension

DDL Book Dim

Shipping Dimension

DDL Shipping Dim

Date Dimension
DDL Date Dim

Detailed instructions for the ETL phase can be found in the ETL folder.

Customer Dimension
ETL Customer Dim

Book Dimension
ETL Book Dim

Shipping Dimension
ETL Shipping Dim

Fact Table Full Load
ETL Fact Table Full Load

Analysis Phase
