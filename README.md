# FRE 521D – Climate Vulnerability Assessment for Global Agriculture

This repository contains the code and data used for **Assignment 1**, **Assignment 2**, and the **Final Project** for the course **FRE 521D: Data Analytics in Climate, Food and Environment (Winter 2026)**.

The final project builds directly on the database and ETL pipeline developed in Assignments 1 and 2 and uses an integrated climate–agriculture dataset to assess climate vulnerability and resilience in global agricultural systems.

---

## Repository Structure

The repository is organized by assignment and project stage:

### Assignment 1
Contains database schema design, data ingestion scripts, and SQL queries for Assignment 1.  
This section focuses on building a clean and normalized climate–agriculture database.

### Assignment 2
Contains the ETL pipeline and aggregation scripts for Assignment 2.  
This section extracts historical weather data, processes it, and integrates it with the database.

### Final Project
Contains analysis notebooks, final datasets, and figures used for the Final Project.  
All results presented in the final report and presentation are generated from this section.

### Data Sources

The analysis uses an integrated dataset that combines agricultural and climate information. Agricultural data include global crop production and yield statistics based on FAO-style datasets. Climate data include annual temperature anomaly records and historical weather variables, such as temperature and precipitation, collected using the Open-Meteo API. Country centroid coordinates are used to extract weather data consistently across countries.

All datasets are cleaned, standardized, and merged before analysis.


#### Notes and Limitations

- The analysis is conducted at the country level and does not capture sub-national variation.
- Some countries have missing data for certain years or variables.
- The analysis focuses on descriptive and comparative insights rather than causal inference.
