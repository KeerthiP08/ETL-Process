**Extract, Transform, and Load (ETL) Pipeline**

This repository contains code for an ETL pipeline that extracts data from various sources, transforms it by handling missing values and calculating additional metrics, and loads it into a SQLite database for analysis.       
**Extracting Data:** The code extracts data from CSV files, JSON files, database files, and API endpoints using pandas and requests libraries.    
**Transforming Data:** The data is transformed by handling missing values and calculating additional metrics such as mean and sum.    
**Loading Data:** Transformed data is loaded into a SQLite database using the sqlite3 library.    
**Analysis:** SQL queries are used to analyze the data stored in the database, such as finding countries with low access to electricity and comparing GDP data over the years.   
