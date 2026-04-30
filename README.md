## Project Overview:
This project analyzes EV adoption using 150,000+ records. A Tableau dashboard highlights key metrics like vehicle count, range, technology split, and trends. Results show rapid growth after 2020, with BEVs dominating over 80% of the market, indicating a shift to full electrification.
The dashboard helps stakeholders understand market dynamics and identify patterns supporting the transition to sustainable mobility.
## Business Problem:
The rapid shift toward sustainable transportation has accelerated EV adoption, but stakeholders lack clear insights into how it varies across manufacturers, regions, and technologies.
This project analyzes adoption patterns, including BEV vs. PHEV distribution, leading manufacturers, time trends, geography, and CAFV eligibility to support better decision-making.

## Datasource & Overview:
**Records:** 150,482 | **Fields:** 15

**Key Variables:** Model Year, Make, Model, Electric Vehicle Type, Electric Range, CAFV Eligibility, County/City/State
## Methodology:
The dataset (150K+ EV records) was cleaned and standardized, with calculated fields created for KPIs and EV type grouping; trends were analyzed across time, manufacturer, model, location, and CAFV eligibility, and results were presented in an interactive Tableau dashboard with dynamic filters.
## Key Calculations & Metrics:
1. Total Vehicles: COUNTD([DOL Vehicle ID])
2. Average Electric Range: AVG([Electric Range])

3. EV Type Grouping:

IF [EV Type] = "Battery Electric Vehicle (BEV)" THEN "BEV"
ELSEIF [EV Type] = "Plug-in Hybrid Electric Vehicle (PHEV)" THEN "PHEV"
END
## Dashboard:
![EV Dashboard](images/EV_dashboard.png)
## Skills:
* Data Cleaning & Transformation & Modelling
* KPI Development & Calculated Fields
* Exploratory Data Analysis (EDA)
* Interactive Dashboard Design (Filters, User Interaction)
* Market & Business Insights
## Results & Recommendations:
- **BEVs** dominate the market **(80.15%)** vs **PHEVs (19.8%)**
- Consistent growth in EV adoption from 2011–2024
- Tesla vehicles leads in total EV adoption
