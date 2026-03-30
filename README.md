# housing_affordability_in_barcelona
Final project for the allWomen Data Analysis Bootcamp, mentored by Asia Noble. 

# Housing Affordability in Barcelona: A District-Level Analysis

## Project Overview
This project analyzes the evolution of housing affordability across districts in Barcelona using publicly available data.  
The objective is to measure how rental prices and household income have evolved over time, and to identify districts experiencing higher affordability pressure.

The analysis is descriptive and exploratory in nature. It does not attempt to establish causal relationships, but rather to provide data-driven evidence of observed patterns.

---

## Research Question
**How has housing affordability evolved across districts in Barcelona over the last decade, and which districts show the highest affordability pressure when rental prices are compared to household income?**

---

## Data Sources
All datasets used in this project are publicly available:

- Barcelona Open Data Portal  
  - Average rental prices by district and year  
  - Household income statistics by district  
  - Population data (used for normalization where relevant)
  - Internal migrations

- Statistical Institute of Catalonia (Idescat, Catalonia, Spain)  
  - Migrations within Catalonia regions

---

## Methodology
The analysis follows these main steps:

1. Data collection and cleaning  
2. Alignment of rental price and income data by district and year  
3. Feature engineering:
   - Rent-to-income ratio as a proxy for affordability pressure
4. Aggregation and comparison across districts
5. Visualization of trends and cross-sectional differences

---

## Key Metrics
- Average rental price (€)
- Average household income (€)
- Rent-to-income ratio
- Year-over-year changes by district

---

## Tools & Technologies
- Python
- pandas
- matplotlib / seaborn
- Jupyter Notebook

---

## Key Findings (Summary)
- Housing affordability has evolved unevenly across districts.
- Some districts consistently show higher rent-to-income ratios than others.
- In several cases, rental price growth outpaces income growth.

Detailed findings and visualizations are available in the analysis notebook.

---

## Limitations
- The analysis relies on aggregated district-level data.
- Household income figures are averages and may mask internal variability.
- Results describe correlations and trends; no causal claims are made.

---

## Next Steps
Possible extensions of this project include:
- Exploring the relationship between tourism pressure and housing availability
- Analyzing demographic changes associated with affordability pressure
- Incorporating additional socioeconomic indicators

---

## Author
This project was developed as part of a data analytics portfolio to demonstrate applied data analysis skills using real-world public datasets.
