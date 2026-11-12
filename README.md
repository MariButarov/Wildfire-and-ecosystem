# Wildfires and Biodiversity: Analyzing Ecological Impacts Across the U.S. West Coast

> This project investigates the relationship between wildfires and bird populations in California, Oregon, and Washington. By combining historical wildfire records with bird observation data, we aim to analyze how wildfire frequency and location relate to changes in bird abundance over time. Each state is divided into four geographic regions (North, South, East, and West) to identify regional patterns. Our main goal is to compare bird observations before and after wildfire events to better understand their potential impact on biodiversity.

---

## Project Overview


This project explores how wildfires may affect bird populations across California, Oregon, and Washington by analyzing historical wildfire records and bird observations. It focuses on comparing bird observations before and after wildfires to identify changes and regional patterns in biodiversity.

- **Objective:** To evaluate the potential impact of wildfires on bird abundance in California, Oregon, and Washington.
- **Domain:** Environmental Science
- **Key Techniques:** Exploratory Data Analysis, Linear Regression
---

## Project Structure

```
├── data/  
│   ├── clean/
│   |	├── 
│   |	└──   
│   ├── raw/           								#Raw and processed data
│   	├── California_fires_with_counties.csv 					#California county coordinates 
│   	├── California_Historic_Fire_Perimeters_4388919187494360015.csv		#
│   	├── DNR_Fire_Statistics_2008_-_Present.csv				#
│   	└── ODF_Fire_Occurrence_2000-2025_20261019.csv				#
├── code/                 # Jupyter notebooks and Python scripts
├── reports/
	wildfire_visualizations.ipynp           # Generated visualizations for wildfire dataset		
├── requirements.txt     			# Dependencies
└── README.md            			# Project documentation
```


---

## Data

- **Source:**
California Wildfire Data: CAL FIRE – [California Fire Perimeters](https://data.ca.gov/@cal-fire/california-fire-perimeters-all?)

Washington Wildfire Data: [WA DNR – Fire Statistics (2008–Present)](https://geo.wa.gov/datasets/wadnr::dnr-fire-statistics-2008-present/about)

Oregon Wildfire Data: ODF – [Fire Occurrence (2000–2025)](https://data.oregon.gov/Natural-Resources/ODF-Fire-Occurrence-2000-2025/fa7z-shhx/about_data)

California County Boundaries: [California County Boundaries and Identifiers](https://publish.data.ca.gov/dataset/california-county-boundaries-and-identifiers)

Bird Observation Data: [eBird](https://ebird.org/home)


- **Description:** The project combines historical wildfire records from California, Oregon, and Washington with bird observation data from eBird. The datasets include wildfire dates, locations, causes, and bird species observations and counts. County information is used to classify observations into four geographic regions within each state.

The data is cleaned, standardized, and combined using Python and Pandas. The processed datasets are organized by date, state, and region to support comparisons of bird abundance before and after wildfire events.

- **License:** MIT License

---

## Analysis

Describe the notebooks and/or scripts used to perform the analysis. Specify the order in which the code should be run to reproduce the results.


Notes on missing values:
- The wildfire dataset from CALFire included 5 fires with locations labeled in Nevada and Arizona that presumably spread over state lines. For simplicity's sake, these were omitted. 
- The wildfire dataset from Oregon included some out-of state wildfires for California and Washington that presumably crossed state lines. Because these should also be included in the origin state's records, these were omitted. 
- If longitude/latitude were not provided for a wildfire, the record was omitted. 

---

## Results

Include a short discussion of the findings and what they imply.

---

## Authors

- Mariana Butarov - [@MariButarov](https://github.com/MariButarov)
- Sophie Akin - [@sophsophiea](https://github.com/sophsophiea)
---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

This project was created as a final project for DATA 51000 at Seattle University. In addition to course materials, the following articles were referenced. 


- Contains some modified code chunks from Geeks for Geeks Geopy Tutorial (https://www.geeksforgeeks.org/python/find-the-location-with-specified-latitude-and-longitude-using-python/)

-
