# Urban Mobility & Economic Productivity Analysis — LATAM

## Project Overview
As part of a data analysis project for the Latin American Development Bank (LADB), this notebook explores how urban mobility relates to economic productivity in major Latin American cities. The goal is to identify where investments in transportation infrastructure could generate the greatest economic and social impact.

## Objective
Analyse the relationship between traffic congestion indicators and urban economic performance to detect patterns that help prioritise interventions in cities where mobility may be limiting economic growth.

## Datasets

| Dataset | Source | Details |
|---|---|---|
| TomTom Traffic Index | [TomTom Traffic Index](https://www.tomtom.com/traffic-index/) | Not included (148MB — exceeds GitHub limit). Download from the official site and place in `/data/` as `tomtom_traffic.csv` |
| OECD Cities | OECD Regional Statistics | Included in `/data/oecd_city_economy.csv` |

## Tools & Libraries
- Python 3
- pandas — data loading, cleaning, and manipulation
- NumPy — numerical operations
- Matplotlib — data visualisation
- Seaborn — statistical visualisation

## Workflow
1. **Load & Explore** — imported datasets, reviewed structure, data types, and missing values
2. **Clean & Prepare** — standardised column names to snake_case, corrected data types (datetime, float), cleaned numeric formats
3. **Filter** — extracted 2024 data for focused analysis
4. **Aggregate** — calculated annual traffic averages per city using groupby
5. **Merge** — combined traffic and economic datasets for cross-analysis
6. **Analyse & Visualise** — identified patterns between congestion and economic indicators

## Key Skills Demonstrated
- Data cleaning and type conversion with pandas
- Handling real-world messy data (mixed formats, symbols, separators)
- Dataset merging and aggregation
- Exploratory Data Analysis (EDA)
- Data visualisation with Matplotlib and Seaborn

## Project Structure
```
urban-mobility-economy-analysis-latam/
│
├── data/
│   └── oecd_city_economy.csv
├── Urban_Mobility_LATAM_clean.ipynb
└── README.md
```

## Context
This project was completed as part of the TripleTen Data Analytics Bootcamp (2025).  
By Deborah Jara | Data Analyst | Mexico
