# Achievement 6 – Happiness & Economic Factors

This project analyzes global happiness data from the 2019 World Happiness Report to examine how selected socio-economic factors relate to reported well-being across countries. In addition, a standalone time-series analysis using U.S. unemployment data is included to demonstrate analytical techniques for temporally ordered data.

The work was completed as part of Achievement 6 using Python for data analysis and Tableau for visualization.

---

## Project Objectives

- Explore global patterns in happiness scores  
- Examine relationships between happiness and key socio-economic factors:
  - GDP per capita  
  - Social support  
  - Healthy life expectancy  
- Identify socio-economic variables most strongly associated with happiness scores  
- Demonstrate differences between cross-sectional and time-series analytical methods  
- Communicate insights through clear visualizations  

---

## Data Sources

**Happiness Analysis**
- World Happiness Report (2019)  
- One row per country  
- Includes happiness scores and socio-economic indicators  

**Time-Series Demonstration**
- U.S. Unemployment Rate (FRED)  
- Monthly observations  
- Used to illustrate trend analysis, stationarity testing, and autocorrelation  

---

## Project Structure


achievement-6-happiness-analysis/
- Data/
    - 2019.csv
-  Notebooks/
    - Exploratory_Analysis.ipynb
    - Modeling_Methods_Overview.ipynb

---

## Notebooks Overview

### Exploratory_Analysis.ipynb
- Data inspection and validation  
- Selection of relevant numeric variables  
- Correlation analysis and interpretation  
- Scatter plots with regression trends  
- Exploratory insights motivating modeling choices  

### Modeling_Methods_Overview.ipynb
- Overview of modeling approaches applied after exploration  
- Linear regression (cross-sectional happiness data)  
- K-means clustering (multivariate country profiles)  
- Time-series analysis using U.S. unemployment data (trend visualization, stationarity testing, autocorrelation)  
- Consolidated discussion of insights, limitations, and next steps  

*Note: The time-series analysis is included as a methodological demonstration and is not directly integrated with the cross-sectional happiness dataset.*

---

## Tableau Visualization

Key findings from the happiness analysis are presented in an interactive Tableau story, including:

- Global distribution of happiness scores  
- Relationships between happiness, GDP per capita, and social support  
- Summary insights, limitations, and next steps  

Tableau Public link:  
https://public.tableau.com/views/Achievement6HappinessEconomicFactors/Achievement6HappinessEconomicFactors

---

## Limitations
- Happiness data represents a single year and does not capture changes over time  
- Observed associations do not imply causation  
- Linear regression does not account for interactions or non-linear relationships  
- Clustering results depend on subjective modeling choices  
- Time-series results are illustrative and not comparable to cross-sectional happiness outcomes  

---

## Next Steps
- Extend regression analysis to include multiple predictors simultaneously  
- Validate clustering results using alternative clustering methods  
- Incorporate longitudinal happiness data to enable true time-series modeling  
- Explore forecasting models (e.g., ARIMA) in greater depth for time-series datasets
