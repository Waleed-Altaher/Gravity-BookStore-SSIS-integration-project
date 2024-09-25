# Gravity Books Sales SSIS Integration Project
![Logo](https://github.com/Waleed-Altaher/Gravity-BookStore-SSIS-integration-project/blob/main/gravity%20logo.png)
## Table of Contents
- [Introduction](#introduction)
- [Data Source](#data-source)
- [Technologies Used](#technologies-used)
- [Execution](#Execution)

## Introduction
Welcome to the Gravity Books Sales End-to-End Project repository. This project is an exemplary demonstration of a complete data warehousing solution, encompassing the Extract, Transform, Load (ETL) phase.

## Data Source
The source dataset for this project is the "Gravity Book Sales" database, which can be found [here](https://github.com/bbrumm/databasestar/tree/main/sample_databases/sample_db_gravity/gravity_sqlserver). This transactional database serves as the foundation for the project.

## Technologies Used
- Microsoft SQL Server.
- SQL Server Integration Services (SSIS)


## Execution

* DDL statements of table creation and the DWH Schema
  
  * Customer Dimension
    
    ![DDL Customer Dim](https://github.com/3amory99/Gravity-Books-Sales-End-to-End-Project/blob/master/Project%20Screenshots/Customer%20Dim.PNG)
    
  * Book Dimension
    
    ![DDL Book Dim](https://github.com/3amory99/Gravity-Books-Sales-End-to-End-Project/blob/master/Project%20Screenshots/Book%20Dim.PNG)
    
   * Shipping Dimension
     
    ![DDL Shipping Dim](https://github.com/3amory99/Gravity-Books-Sales-End-to-End-Project/blob/master/Project%20Screenshots/Shipping%20Dim.PNG)
  
   * Date Dimension
     
    ![DDL Date Dim](https://github.com/3amory99/Gravity-Books-Sales-End-to-End-Project/blob/master/Project%20Screenshots/Date%20Dim.PNG)





* Detailed instructions for the ETL phase can be found in the [ETL folder](/ETL).

   * Customer Dimension
   
    ![ETL Customer Dim](https://github.com/3amory99/Gravity-Books-Sales-End-to-End-Project/blob/master/Project%20Screenshots/ETL%20Customer%20Dim.PNG)

   * Book Dimension
   
    ![ETL Book Dim](https://github.com/3amory99/Gravity-Books-Sales-End-to-End-Project/blob/master/Project%20Screenshots/ETL%20Book%20Dim.PNG)

   * Shipping Dimension
   
    ![ETL Shipping Dim](https://github.com/3amory99/Gravity-Books-Sales-End-to-End-Project/blob/master/Project%20Screenshots/ETL%20Shipping%20Dim.PNG)

   * Fact Table Full Load
   
    ![ETL Fact Table Full Load](https://github.com/3amory99/Gravity-Books-Sales-End-to-End-Project/blob/master/Project%20Screenshots/ETL%20Fact%20Table%20Full%20Load.PNG)


  For Data Warehouse .Bak [Here]([url](https://drive.google.com/file/d/1UWBgLrByWln3ZXcX046adzUX2cxJRZCZ/view?usp=sharing))
