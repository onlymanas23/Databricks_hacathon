# Databricks_hacathon
# RailSmart AI — Delay-Aware Route Optimization

##  What It Does  
RailSmart AI predicts station-level train delays and recommends the most reliable routes by minimizing total journey time, waiting time, and delay risk.

##  Architecture Diagram  
            +----------------------+
            |  Railway Datasets    |
            | (Schedules, Delays)  |
            +----------+-----------+
                       |
                       v
            +----------------------+
            |   Data Ingestion     |
            |   (Databricks)       |
            +----------+-----------+
                       |
                       v
            +----------------------+
            | Data Processing      |
            | (PySpark + SQL)      |
            +----------+-----------+
                       |
                       v
            +----------------------+
            | Delay Prediction     |
            | (ML Models)          |
            +----------+-----------+
                       |
                       v
            +----------------------+
            | Route Optimization   |
            | (Risk + Time Model)  |
            +----------+-----------+
                       |
                       v
            +----------------------+
            |       Frontend       |
            | User Input/Output    |
            +----------------------+
Demo Steps
Open the website in your browser
Enter Source Station
Enter Destination Station
Click "Find Best Route"
---

