# Departure Delay Flight Analysis
- **Author:** Group Project 
- **Date:** November 2, 2025

-------

## Project Overview

**Introduction:** This repository contains an R analysis of NYC flight departure delays for United Airlines,
executed in Google Colab using the `nycflights13` dataset.

**Problem Statement:** Which variable impacts departure delays the most? 

### Main Source of Analysis
- `departure_delays_analysis.ipynb` – main Colab notebook


### How to open
1. Click the **Open in Colab** badge below, or  
2. Download the `.ipynb` and open in Colab manually.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1UX6xXixKirhUbRy2xcQqpOwBOpC45K64#scrollTo=uleS3xuDbX9h)

Please view the fficial **Google Powerpoint** presentation [here](https://docs.google.com/presentation/d/1llBNPO991JsdHFwYwofdL1u-ZTQaiRJ5O6EKXS1JWoQ/edit?slide=id.gc6f9e470d_0_0#slide=id.gc6f9e470d_0_0). 

Please view the official link to the **Analysis Report** [here](https://redhawks-my.sharepoint.com/:w:/r/personal/azukas_seattleu_edu/_layouts/15/Doc.aspx?sourcedoc=%7Bec7a6e9d-e7cd-418b-8c36-ea39606ec47c%7D&action=edit&wdPreviousSession=a3e074e4-a199-051d-9450-868f4a0f6938&web=1).

---

## Project Structure

```
├── 'departure_delay_analysis'                # Google Colab Notebook and R script
├── 'departure_delay_analysis_report          # Generated reports and visualizations
├── 'departure_delay_analysis_presentation    # Presentation slides for communicating results
├── requirements.txt                          # Dependencies
└── README.md                                 # Project documentation
```

---

## Data 

## Sources:

This project utilizes four main data sets from the **‘nycflights13’ R Package**:

- **Weather**: Contains values from the variables we are going to analyze further. Like the departure airport, time of day, time of year, visibility, precipitation level, and wind speed. 
- **Airlines**: Provides details about each airline, including the carrier airline code and airline name. 
- **Airports**: Contains details about each airport, like the faa code, name, altitude, latitude/longitude, altitude(ft), timezone, and daylight-saving indicators . 
- **Flights**: Contains details about the United Airlines flights in and out of NYC for the year of 2013, such as the airline and carrier names, airport information, plane identification codes, and weather origin. 


Together, these datasets allow for the analysis of relationships between departure delays and the 6 variables we aim to analyze.  

---

## Analysis

Google Colab Notebook

---

## Results 
For 2013 United Airlines NYC flights, we found that the strongest predictors of departure delays were time_of_day and time_of_year, but when tested for randomness – we found that time_of_day was the only variable that displayed any level of statistical significance. 

So, to answer our original question - what variable has the greatest effect on departure delays? - our suggested solution would be **time of day** (morning, afternoon, evening, night). 

To further expand on this conclusion, it is important to emphasis that this is just based on the analysis of a very specific subset of data – United Airlines NYC for the year of 2013. If we wanted to gain a better understanding of variable effects on United Airlines' departure delays, we would want to analyze data across multiple origins and years.  

For example, we could analyze the relationship of departure delays for NYC Unites Airlines flights across the time span of 2000 to 2020, instead of just in 2013. This would allow us to see a bigger picture in variables like time_of_year (winter, spring summer, fall).  

Just like our permutation test suggested, the differences we observed in the departure delays for each season is mostly likely due to random chance. Logically, we can consider the fact that this is not fully true. Time of year must affect departure delays, right? 

Expanding this analysis further by analyzing this across multiple years allows us to pick up any potential trends. 


---

## Authors 

- Alyssa Zukas - [@alyzukas](https://github.com/alyzukas)
- Prince Newman
- Badamgarav Battushig
- Edwin Okwor

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements 

- Tools/libraries used:
    -  Ggplot2: Imported for data visualization 
    - Dplyr: Used for data manipulation in R. Such as the filter, select, muttate, arrange, and summarize functions 
    - Tidyr: Used for tidying and reshaping data 
    - Tibble: Installed modern data frames for R 
    - Forcats: Imported for categorical/factor data manipulation 
    - Lubridate: Used to work with date and time 
- Tutorials or papers referenced: DATA 5300 Class modules
- Inspiration or collaborators: Dr Slaughter
