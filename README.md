# Chicago Traffic Crashes – Exploratory Data Analysis (EDA)

This project explores the **Traffic Crashes – Crashes** dataset from the city of Chicago. Using Python and data visualization libraries, we extract insights on when, where, and under what conditions road crashes are most likely to occur.

## Project Files
- `EDA_Traffic_Crashes.ipynb` – Jupyter Notebook with complete EDA code, plots & observations
- `Traffic_Crashes_EDA_Report.pdf` – PDF report summarizing findings and visualizations

## Objective
To perform statistical and visual analysis of traffic crash data in Chicago to uncover patterns, trends, and anomalies that may help improve road safety and urban planning.

## Tools & Libraries
- Python  
- Pandas  
- Matplotlib  
- Seaborn  

## Key Insights from EDA
### Crash Timing & Frequency
- Most crashes occur during **rush hours (7–9 AM & 5–7 PM)**
- **Weekdays** see more crashes, especially during commute times

### Speed & Injury Severity
- **Higher speed limits** are generally associated with **more severe injuries**

### Weather & Environmental Conditions
- Crashes under **rain or snow** have higher injury averages
- **Lighting and road surface** significantly influence crash outcomes

### Monthly Trends
- **Seasonal peaks** observed in **winter and summer months**
- **October** saw an especially high number of incidents

### Injury Analysis
- Majority of crashes resulted in **non-incapacitating injuries**
- Fatal injuries were **rare but non-negligible**

### Crash Locations
- **Geographic clustering** of crashes visualized via latitude & longitude
- Helps identify **accident hotspots** in the city

### Multivariate Insights
- Positive correlations found among various injury types
- Crash hour patterns differ significantly between **weekdays vs. weekends**

## Data Preprocessing
- Renamed and cleaned column names for clarity
- Removed duplicates and handled missing/null values
- Dropped irrelevant columns (e.g., DOORING_I, PHOTOS_TAKEN_I)
- Applied `.mode()`, `.fillna()`, and categorical encodings where needed

## Outcome
The analysis highlights the influence of **time, speed, weather, and environment** on traffic crashes. These insights can be used by city officials and urban planners to:
- Improve **traffic safety policies**
- Deploy **targeted safety interventions**
- Identify **high-risk zones** for monitoring and infrastructure upgrades



