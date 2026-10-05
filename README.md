# Project Title: A Comparison of Rainfall Between Seattle, WA and Grand Rapids, MI

> This project will use publicly available data to compare the amount of rainfall between Seattle and Grand Rapids.

---

## Project Overview

This project uses publicly available data to determine if Seattle, WA or Grand Rapids, MI gets more precipitation. The data is from the NAOO weather stations. It was determined that Seattle receives more precipitation.

- **Objective:** determine which city rains more: Seattle or Grand Rapids
- **Domain:** Weather
- **Key Techniques:** Visualizations

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

- **Source:** [Seattle Rain](data/seattle_rain.csv) [Grand Rapids Rain](data/grandrapids_rain.csv)
- **Description:** Data containing precipitation values in Seattle and Grand Rapids
- **License:** (if applicable)

---

## Analysis

Data from each city was first checked to ensure that the same date ranges were being compared between cities. Then, missing values were imputed by finding the average rainfall on each day for each city, then filling the missing data with the corresponding average rainfall. Finally, boxplots were created to visually compare rainfall between the two cities. The notebook that does the analysis is titled Weather_data.ipynb. The clean data file is called "clean_seattle_grandrapids.csv"

---

## Results

Seattle has more rain than grand rapids
---

## Authors

- Kyle DeRosia

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Tools/libraries used
- Tutorials or papers referenced
- Inspiration or collaborators
