# Whale Migration & Ocean Temperature Analysis (Part 2)

This is the second part of my marine data analysis project. 

After identifying the main "hotspots" of whale observations, I wanted to find out **why** they were there. 

## Goal
To test the hypothesis: *Does sea surface temperature influence whale movement in the Southern Ocean?*

## Data
- **Whales:** Movebank (Antarctic blue whales, 2013)
- **Water Temperature:** NOAA OISST v2.1 (Sea Surface Temperature for 2013)
- **Tools:** Python, pandas, xarray, matplotlib, seaborn

## Key Findings
1. **No direct correlation:** The scatter plot showed that whale observations are spread across different temperatures. Surface water temperature alone does not dictate their movement.
2. **Migration Route:** The heatmap clearly shows a diagonal aggregation pattern, suggesting whales follow a specific migratory route near Antarctica rather than moving randomly.

## Conclusion
The data (808 records for one year, surface temperature only) is insufficient to make a strong conclusion. 

Other factors like water depth, food availability (chlorophyll), and predators likely play a much larger role.

## Visualizations

<img width="844" height="547" alt="scatter plot" src="https://github.com/user-attachments/assets/23dca526-f99c-4405-891c-cef18cf4b152" />

*Scatter plot: Number of whale sightings vs Sea Surface Temperature.*


<img width="1000" height="573" alt="heatmap" src="https://github.com/user-attachments/assets/34528109-0d2e-4cfe-883d-a942860cd30b" />

*Heatmap: Whale observation hotspots by latitude and longitude.*

[View the full analysis](https://github.com/vicTORIa-biotech/whale-migration-analysis_marine-data/blob/main/Antarctic%20blue%20whales%2C%20east%20Antarctic%20sector%20of%20the%20Southern%20Ocean.csv)

**Author:** Victoria
