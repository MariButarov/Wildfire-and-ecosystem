# Wildfires and Biodiversity: Analyzing Ecological Impacts Across the U.S. West Coast

> This project investigates the relationship between wildfires and bird populations in California, Oregon, and Washington. By combining historical wildfire records with bird observation data, we aim to analyze how wildfire frequency and location relate to changes in bird abundance over time. Each state is divided into four geographic regions (North, South, East, and West) to identify regional patterns. Our main goal is to compare bird observations before and after wildfire events to better understand their potential impact on biodiversity.

---

## Project Overview

Provide a short and concise overview of the project. Mention the problem it solves, the data used, and the key outcomes or findings.

This project explores how wildfires may affect bird populations across California, Oregon, and Washington by analyzing historical wildfire records and bird observations. It focuses on comparing bird abundance before and after wildfires to identify changes and regional patterns in biodiversity.

- **Objective:** To evaluate the potential impact of wildfires on bird abundance in California, Oregon, and Washington by comparing bird observations before and after wildfire events and identifying regional and temporal patterns.
- **Domain:** Environmental
- **Key Techniques:** (e.g., Regression, Classification, Clustering, NLP, Time Series)

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
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

- **License:** (if applicable)

---

## Analysis

Describe the notebooks and/or scripts used to perform the analysis. Specify the order in which the code should be run to reproduce the results.

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

- Tools/libraries used
- Tutorials or papers referenced
- Inspiration or collaborators
