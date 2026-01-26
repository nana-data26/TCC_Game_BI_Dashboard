# TCC_Game_BI_Dashboard
This Project was developed as a **Capstone Project for the MBA in Business Intelligence & Analytics**.

PROJECT COMPLETED AND FINISHED


#----------------------------------------------------------------#

## PROJECT OVERVIEW

This project aims to analyze data from Twitch and IGDB to identify audience patterns and game popularity using public data collected via APIs.

#----------------------------------------------------------------#

## SOLUTION ARCHITECTURE

Twitch / IGDB APIs (Postman - Connection Tests)
              ↓
  Data Collection (Power Automate)
              ↓
    ETL in Python (Google Colab)
              ↓
      Dashboard (Power BI)

#----------------------------------------------------------------#

## TECHNOLOGIES USED

- REST APIs (Twitch / IGDB)
- Postman (APIs Requests tests)
- Power Automate (Automated data extraction)
- Python (Pandas, Numpy, Requests)
- Google Colab
- Power BI (KPIs, DAX measures)

#----------------------------------------------------------------#

## DATA COLLECTION

- APIs Used: Twitch and IGDB.
- Authentication Type Used: OAuth
- Data Collection Frequency: Once per day (around 6:00 PM - UTC−03:00) from 2025 May to August
- Types of Data Collected: Top 100 Twitch Streams (Global) and Top 100 Twitch Viewers (Brazilian)

#----------------------------------------------------------------#

## ETL IN PYTHON

Extraction:
    - Reading data from APIs

Transformations:
    - Data Cleaning
    - Normalization
    - Reconsultation via APIs (detailed information in IGDB)
    - Handling Missing Values

Load:
    - Final Data Format (.CSV)
    - Data Structure designed for BI consumption

#----------------------------------------------------------------#

## DASHBOARD

To be included

#----------------------------------------------------------------#

## KEY INSIGHTS

To be included

#----------------------------------------------------------------#

## LIMITATIONS AND NEXT STEPS

To be included

#----------------------------------------------------------------#

Developed by:
Naomi Oikawa - MBA in Business Intelligence & Analytics
Year: 2025

Social Network:
[LinkedIn](https://www.linkedin.com/in/naomi-asofu-oikawa-6899821b3/)
