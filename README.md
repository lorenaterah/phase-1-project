# Aviation Safety Analysis Project

## Overview

This project analyzes historical aviation accident data to uncover patterns, highlight the safest aircraft types and regions, and provide data-driven recommendations for business decision-making. 
The ultimate goal is to reduce risk, strengthen passenger confidence, and guide operators in choosing safer fleet and operational strategies.


## Data Overview

* **Dataset:** Cleaned aviation accident dataset (`cleaned_aviation_data.csv`).
* **Features Included:**

  * `Year` – Year of the accident/incident.
  * `Aircraft Type` – Model/type of aircraft involved.
  * `Operator` – Airline or operator of the aircraft.
  * `Region/Location` – Geographical location of the event.
  * `Accident Category` – Type of incident (e.g., mechanical, weather-related, human error).
  * `Fatalities (Total, Aboard, Ground)` – Number of people killed.
* Size:*11 columns and 22581 rows*
* Scope: Covers multiple decades of aviation data, with focus on the last 20 years for modern aircraft relevance.


## Data Understanding

* Relevance:
  Each variable was chosen to support the project’s central question: *Which aircraft types and regions pose the least risk for aviation business operations?*

  * Time (Year): Enables trend analysis.
  * Aircraft Type & Operator: Critical for comparing safety records.
  * Region: Captures geographical variations in accident rates.
  * Fatalities: Quantifies severity of accidents.

* Strengths:

  * Large dataset with historical depth.
  * Rich detail across multiple safety dimensions (aircraft, operator, region).

* Limitations:

  * Missing or incomplete records for some years/operators.
  * Historical data may not fully reflect the performance of new aircraft models or regulatory improvements.
  * Does not include contextual data such as weather, maintenance logs, or pilot experience.


## Analysis Approach

* Descriptive Statistics: Accident frequencies, fatality rates.
* Comparative Analysis: Safety outcomes across aircraft, operators, and regions.
* Trend Analysis: Long-term shifts in accident severity and frequency.


## Visualizations in Tableau

A Tableau dashboard will be added to this project to make findings more interactive and accessible.
[https://public.tableau.com/app/profile/lorena.terah/viz/AviationAccidentanalysis/Dashboard1]

## Project Status

This repository contains the cleaned dataset, analysis notebooks, and supporting documentation.
