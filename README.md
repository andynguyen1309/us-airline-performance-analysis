# US Airline Performance Analysis (2019–2023)

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Business Analytics](https://img.shields.io/badge/Business-Analytics-blue?style=for-the-badge)
![Data Visualization](https://img.shields.io/badge/Data-Visualization-green?style=for-the-badge)
![Dashboard](https://img.shields.io/badge/Interactive-Dashboard-orange?style=for-the-badge)
![3M Flights](https://img.shields.io/badge/Dataset-3M_Flights-red?style=for-the-badge)

## ✈️ Overview

This project analyses over 3 million domestic US airline flights between January 2019 and December 2023 using Tableau.

The objective is to identify operational performance trends across airlines, airports and flight routes while investigating the major causes of delays and cancellations.

The project was developed as part of my Business Analytics portfolio to demonstrate dashboard design, KPI development and interactive data visualisation using Tableau.

## 🔗 Interactive Dashboard

View the full interactive Tableau dashboard here:

[![View on Tableau Public](https://img.shields.io/badge/View_on_Tableau_Public-E97627?style=for-the-badge&logo=tableau&logoColor=white)](https://public.tableau.com/app/profile/andy.nguyen4651/viz/USAirlinePerformanceAnalysis20192023/Home)

<img width="1998" height="1598" alt="Dashboard0-Home" src="https://github.com/user-attachments/assets/6d650670-a118-4a8f-8e2d-217721179dde" />

## ❓ Business Questions

This dashboard answers questions such as:

### Overall Performance
- How many flights operated between 2019 and 2023?
- How did COVID-19 affect flight volume?
- What percentage of flights arrived on time?
- What are the primary causes of delays?

### Airline Performance
- Which airlines have the highest average delays?
- Which airlines experience the highest cancellation rates?
- Which airlines consistently outperform competitors?

### Airport Performance
- Which airports experience the longest delays?
- Which airports record the highest cancellation rates?
- Are delay problems concentrated at major hubs?

### Delay Cause Analysis
- Which delay category contributes the most delay minutes?
- How have delay causes changed over time?
- Which airlines and airports are most affected by each delay type?

### Route Performance
- Which routes carry the highest passenger traffic?
- Which busy routes experience the worst delays?
- Which delay causes dominate high-volume routes?

## 💾 Dataset

- Source: https://www.kaggle.com/datasets/patrickzel/flight-delay-and-cancellation-dataset-2019-2023 
- Time Period: January 2019 – August 2023

### Size: 3+ million domestic flights

- 5 dashboards
- 20+ interactive visualisations
- Multiple calculated fields, KPIs and parameters

The raw dataset exceeds GitHub's file size limit and is therefore not included in this repository. The original data can be downloaded directly from the Bureau of Transportation Statistics.

## ⚙️ Tools
- Tableau Desktop (Data Visualisation)
- Python (Data Preparation and Validation)

## 🎯 Dashboard Overview

### Dashboard 1 — Overall Airline Performance

Provides an executive overview of the US aviation industry: Flight volume trend, Delay category distribution, Delay cause breakdown, Operational KPIs

<img width="1998" height="1598" alt="Dashboard1-Overview" src="https://github.com/user-attachments/assets/2ea110fa-9f8d-46a1-bd2e-047dcb993011" />

### Dashboard 2 — Airline Performance

Compares airline operational performance using: Delay ranking, Cancellation ranking, Delay vs cancellation matrix, Best and worst airline KPIs

<img width="1998" height="1598" alt="Dashboard2-Airline" src="https://github.com/user-attachments/assets/e7ea69bb-343e-4648-8dfa-1fb449e3c6d3" />

### Dashboard 3 — Airport Performance

Analyses airport operational efficiency through: Airport performance map, Delay ranking, Cancellation ranking, Airport KPIs

<img width="1998" height="1598" alt="Dashboard3-Airport" src="https://github.com/user-attachments/assets/c46f7fa5-6cf3-4c88-9880-addc21e4d7a1" />

### Dashboard 4 — Delay Cause Analysis

Explores operational delay sources using: Delay cause trend, Delay cause composition, Airport heatmap, Delay breakdow

<img width="1998" height="1598" alt="Dashboard4-Delay-Cause" src="https://github.com/user-attachments/assets/396fbf2b-9d41-4a3e-8157-b94750f942d4" />

### Dashboard 5 — Route Performance

Examines performance across major US routes: Route performance scatterplot, Highest traffic routes, Worst-performing busy routes, Delay cause composition by route

<img width="1998" height="1598" alt="Dashboard5-Route" src="https://github.com/user-attachments/assets/beb7dd75-5534-4460-9463-a270707acc9b" />

## 🔎 Key Findings

- Approximately 64.5% of flights arrived on time or early.
- Flight activity declined sharply during COVID-19 before recovering to near pre-pandemic levels.
- Late Aircraft and Carrier Delay accounted for most delay minutes.
- Allegiant Air recorded the highest average arrival delay among major airlines.
- Smaller regional airports experienced the greatest delays and cancellation rates.
- Major routes such as ORD → LGA combined high traffic volume with above-average delays, making them priority candidates for operational improvement.

## 🔮 Future Improvements

- Delay prediction using Machine Learning
- Airport network analysis
- Seasonal forecasting
- Interactive route map
- Airline benchmarking over longer time periods
