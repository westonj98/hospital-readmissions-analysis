# Hospital Readmission Risk Analysis

## Project Overview

This healthcare analytics project will examine hospital encounter data to identify factors associated with 30-day hospital readmissions.

The project will use SQL, Python, and Power BI to clean data, calculate healthcare performance measures, identify readmission patterns, and present findings through an interactive dashboard.

## Business Problem

Hospital readmissions can increase healthcare costs, affect patient outcomes, and place additional pressure on hospital staff and resources.

The purpose of this project is to help hospital leaders understand which patients and encounter characteristics are associated with higher readmission rates.

## Business Questions

1. What is the overall 30-day readmission rate?
2. Which diagnoses have the highest readmission rates?
3. Which age groups have the highest readmission rates?
4. Does previous hospital or emergency department use affect readmission risk?
5. Is length of stay associated with readmission?
6. Which patients may benefit from additional discharge support?

## Intended Stakeholders

- Hospital leadership
- Quality improvement teams
- Care management teams
- Nursing leadership
- Population health teams
- Healthcare operations teams

## Tools

- SQL
- Python
- Pandas
- Jupyter Notebook
- Power BI
- Excel
- GitHub

## Dataset

This project uses the public Diabetes 130-US Hospitals dataset from the UCI Machine Learning Repository.

The dataset contains deidentified hospital encounters from multiple United States hospitals and includes patient demographics, diagnoses, hospital utilization, medications, and readmission outcomes.

The primary outcome field is `readmitted`, which includes:

- `<30`: Readmitted within 30 days
- `>30`: Readmitted after 30 days
- `NO`: No recorded readmission

For this project, the main 30-day readmission measure will classify:

- `<30` as readmitted within 30 days
- `>30` and `NO` as not readmitted within 30 days

The original raw data will remain unchanged. Cleaning and analysis will be performed on separate working files.


## Project Status

## Project Status

Day 2 completed:

- Created local project folders
- Downloaded the public hospital readmission dataset
- Saved the original raw data
- Created a separate working copy
- Started the data dictionary
- Documented the dataset source
- Recorded initial data inspection notes

Next step: perform formal data quality checks.

## Planned Project Steps

1. Select a public or synthetic healthcare dataset.
2. Create a data dictionary.
3. Check the data for missing values and duplicates.
4. Clean and transform the data.
5. Analyze hospital readmission patterns.
6. Calculate key performance indicators.
7. Create an interactive Power BI dashboard.
8. Summarize findings and recommendations.
9. Document project limitations.
10. Publish the completed project.

## Important Privacy Notice

This project will only use public, synthetic, or properly deidentified data. No protected health information or confidential employer data will be included.

## Author

Janae N. Weston

M.S. Data Analytics Candidate

Healthcare Data Analytics | SQL | Python | Power BI | Tableau
