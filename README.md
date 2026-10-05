# Project Title: A Comparison of Rainfall Between Seattle, WA and Grand Rapids, MI

> This project will use publicly available data to compare the amount of rainfall between Seattle and Grand Rapids.

---

## Project Overview

Provide a short and concise overview of the project. Mention the problem it solves, the data used, and the key outcomes or findings.

- **Objective:** Clearly state the main goal of the project.
- **Domain:** (e.g., Healthcare, Finance, E-commerce, etc.)
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

- Your Name - [@yourhandle](https://github.com/yourhandle)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Tools/libraries used
- Tutorials or papers referenced
- Inspiration or collaborators
