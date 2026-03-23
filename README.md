Urban Mobility & Economic Productivity Analysis — LATAM
 Project Overview
As part of a data analysis project for the Latin American Development Bank (LADB), this notebook explores how urban mobility relates to economic productivity in major Latin American cities. The goal is to identify where investments in transportation infrastructure could generate the greatest economic and social impact.

 Objective
Analyse the relationship between traffic congestion indicators and urban economic performance to detect patterns that help prioritise interventions in cities where mobility may be limiting economic growth.

 Datasets
DatasetSourceDescriptiontomtom_traffic.csvTomTom Traffic IndexTraffic congestion indicators by city (jams, delays, travel times)oecd_city_economy.csvOECD CitiesEconomic indicators by city (GDP per capita, unemployment, population)

 Tools & Libraries

Python 3
pandas — data loading, cleaning, and manipulation
NumPy — numerical operations
Matplotlib — data visualisation
Seaborn — statistical visualisation


 Workflow

Load & Explore — imported datasets, reviewed structure, data types, and missing values
Clean & Prepare — standardised column names to snake_case, corrected data types (datetime, float), cleaned numeric formats
Filter — extracted 2024 data for focused analysis
Aggregate — calculated annual traffic averages per city using groupby
Merge — combined traffic and economic datasets for cross-analysis
Analyse & Visualise — identified patterns between congestion and economic indicators


 Key Skills Demonstrated

Data cleaning and type conversion with pandas
Handling real-world messy data (mixed formats, symbols, separators)
Dataset merging and aggregation
Exploratory Data Analysis (EDA)
Data visualisation with Matplotlib and Seaborn


 Project Structure
urban-mobility-economy-analysis-latam/
│
├── urban-mobility-economy-latam.ipynb   # Main analysis notebook
└── README.md                            # Project documentation

 Context
This project was completed as part of the TripleTen Data Analytics Bootcamp (2025).

By Deborah Jara | Data Analyst | Mexico
