# Snowflake_swiggy_end_to_end_DE_project
This repository showcases a full-stack data engineering project simulating a Swiggy-like food delivery platform. The pipeline leverages Snowflake for scalable data warehousing and Streamlit for interactive analytics dashboards.

<img width="1920" height="1080" alt="Architecture" src="https://github.com/user-attachments/assets/9c399f39-4496-45c0-9d0b-691f33ca2a41" />


***🚀 Project Overview***
**Goal: Build a production-grade ETL pipeline from raw stage data (CSV) to high-quality analytics and real-time KPI dashboards.**

***Tech Stack:***

+Snowflake — Data warehouse, ETL, masking policies, slow-changing dimensions

+SQL — DDL, DML, SCD2, KPI views

+Streamlit — Modern Python dashboard UI

+Python — For data visualization/analytics (Streamlit app)

***Key Features:***

+Raw → Clean → Consumption layer design

+Full star schema and dimensional modeling

+Automated change data capture using Streams

+SCD2 logic for historical tracking

+Policy tags and masking for data privacy (PII)

+Modular, production-ready scripts

+Interactive dashboards for KPI analysis


**🛠️ Modules & Components**
<img width="921" height="417" alt="image" src="https://github.com/user-attachments/assets/ba59b65e-c464-41fe-a058-748c4b6c564f" />

🚦 How to Run
1. Snowflake Setup

+Create a warehouse and schemas with Create-DB-Schema.sql

+Ingest sample CSV data into stage (simulate copy into ...)

+Run the respective entity SQL scripts sequentially to build tables and load data

+Use the KPI view scripts for reporting

2. Streamlit Dashboard
+Install Python requirements (streamlit, snowflake-snowpark-python, altair, etc.)

+Configure Snowflake connection for the Streamlit app

+Launch dashboard:

streamlit run streamlit/streamlit_app.py

📋 Documentation

See docs/ for system architecture diagrams, data lineage, ERD, and business logic design.

👨💻 Author & Contact
 Created by: Nayan Jain

www.linkedin.com/in/nayan-jain007, nayanjain24003@gmail.com

