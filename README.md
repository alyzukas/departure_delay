# Departure Delay Flight Analysis
- **Author:** Group Project 
- **Date:** November 2, 2025

-------

## Project Overview

**Introduction:** This repository contains an R analysis of NYC flight departure delays for United Airlines,
executed in Google Colab using the `nycflights13` dataset.

**Problem Statement:** Which variable impacts departure delays the most? 

### Files
- `departure_delays_analysis.ipynb` – main Colab notebook


### How to open
1. Click the **Open in Colab** badge below, or  
2. Download the `.ipynb` and open in Colab manually.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1UX6xXixKirhUbRy2xcQqpOwBOpC45K64#scrollTo=uleS3xuDbX9h)

---

## Project Structure

```
├── code/                 # Google Colab Notebook and R script
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data (ADD)

- **Sources:** 

    - EdGap Information (EdGap_data.xlsx)[https://github.com/alyzukas/education/blob/main/data/EdGap_data.xlsx]
    - School Information (ccd_sch_029_1617_w_1a_11212017.csv [https://github.com/alyzukas/education/blob/main/data/ccd_sch_029_1617_w_1a_11212017.csv]
    - Geographical Assignment (EDGE_GEOCODE_PUBLICSCH_1617.xlsx)[https://github.com/alyzukas/education/blob/main/data/EDGE_GEOCODE_PUBLICSCH_1617.xlsx]

---


- **License:** N/A

---

## Analysis

Google Colab Notebook

---

## Results (ADD)
Based off of the differing average exam scores for each geoassignment category, it is safe to assume that a schools geographical assignment **does** have an affect on school performance. But based off how little these averages differ, we cannot confidently support that geoassignment necessarily has a **strong** affect on school performance.

When analyzing the relationship of school performace and all socioeconmic variables, it appears that there are **other school variables that have stronger effects on school performace** than geographical assignment. Specifically - percentage of college education, percentage of students from married-couple families, and median income.


---

## Authors (ADD)

- Your Name - [@alyzukas](https://github.com/alyzukas)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements (ADD)

- Tools/libraries used:
    -  pandas
    -  NumPy
    - matplotlib.pyplot
    - seaborns grid modeling
    - statsmodels.formula.api
    - statsmodels.api
- Tutorials or papers referenced: DATA 5100 Class modules
- Inspiration or collaborators: Dr Fischer
