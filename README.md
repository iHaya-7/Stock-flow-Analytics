# Stock Market Data Engineering Pipeline

This project implements a **data engineering pipeline** that integrates **live stock prices** from the Alpha Vantage API with **historical CSV datasets**. The pipeline is designed using both **ETL** and **ELT** approaches to ensure scalability, flexibility, and reliability for financial data analysis.

## Features
- Automated **data extraction** from Alpha Vantage API (live prices) and historical CSVs.  
- **Data validation & cleaning**: handled missing values, duplicates, and inconsistencies.  
- Support for both **ETL (Extract → Transform → Load)** and **ELT (Extract → Load → Transform)** pipelines.  
- Loading into a structured **SQL database** for storage and querying.  
- Ensured data reliability and scalability for future analytics and visualization.  

## Tech Stack
- **Python** (Pandas, Requests, SQLAlchemy)  
- **Alpha Vantage API**  
- **SQL Database** (e.g., PostgreSQL / MySQL / SQLite)  
- **ETL & ELT Data Engineering Concepts**  

## ⚙️ Setup & Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/stock-pipeline.git
   cd stock-pipeline

   2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   
