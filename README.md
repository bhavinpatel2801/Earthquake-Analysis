# Earthquake Data Analysis Project

## Overview
This project analyzes Earthquake data from 2023-2024(till august) to identify trends, distribution of Earthquake accross globe.

## Data
This dataset provides detailed information on 1,137 earthquakes from around the world. It includes a wide range of attributes such as magnitude, location details, time, and various seismological measurements. The data was collected using the EveryEarthquake API from RapidAPI, offering researchers, seismologists, and data enthusiasts a rich resource for analysis, machine learning projects, and geological studies.

## Methods
1. Data cleaning and preprocessing
2. Exploratory Data Analysis (EDA)
3. Statistical analysis
4. Time series analysis for seasonal patterns

## Results
Key findings:
1. There is no linear relationship between magnitude and depth of earthquakes, however we can conclude that all earthquakes with depth more than 300km has magnitude of more than 5.0.
2. Majority of eathquakes have shallow depth(20km).
3. At global level, pacific ocean coastal areas are facing frequent earthquakes.
4. There is yet 4 month to complete 2024, still year 2024 has experienced more than twice the eathquakes compared to 2023 indicating substanstial increased in siesmic activity in 2024.
5. Month of July, August and September is where majority of eathquakes has occured indicating some kind of seasonality with Earthquakes.
6. Proportion of earthquakes that are tsunami related: 5.98%. 67 out 68 Tsunami accopanied eathquakes have more than 4.0 magintude.

![image](https://github.com/user-attachments/assets/a54144ad-fab5-46d5-945d-d09c7b8977d9)


## Repository Structure
- `data/raw/`: Original, immutable data
- `data/processed/`: Cleaned, transformed data
- `notebooks/`: collab notebooks for analysis
- `results/`: Figures, tables, and summary reports
