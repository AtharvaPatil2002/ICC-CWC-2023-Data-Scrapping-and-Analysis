
# ODI CWC 2023 Data Analysis

This project involves data scraping, cleaning, and analysis of the ODI Cricket World Cup 2023 data. The data was extracted from ESPN Cricinfo, cleaned in python, and then visualized using Power BI to provide detailed insights and reports.


# Table of contents

- [Introduction](#Introduction)
- [Data Scraping](#Data-Scraping)
- [Data Cleaning](#Data-Cleaning)
- [Data Transformation and Analysis](#Data-Transformation-and-Analysis)
- [Power BI Dashboard](#Power-BI-Dashboard)
- [Repository Structure](#Repository-Structure)
- [Dependencies](#Dependencies)
- [Usage](#Usage)
- [Contributors](#Contributors)
- [Acknowledgements](#Acknowledgements)

## Introduction

This repository contains the code and resources for analyzing the ODI Cricket World Cup 2023 data. The project covers the entire workflow from data scraping to creating an interactive Power BI dashboard.
## Data Scraping

Data scraping was performed using JavaScript to extract data from ESPN Cricinfo using BrightData's self made web scrappers. The data was extracted from the XML source and converted into JSON format. The following datasets were created:

- Players Data: Information about the players.
- Matches Data: Details of the matches played.
- Batting Summary: Summary of batting performances.
- Bowling Summary: Summary of bowling performances.
## Data Cleaning

The JSON files were uploaded into Jupyter notebook turned in pandas Dataframe. Data cleaning was carried out using a Python notebook. The datasets were then converted into csv files. The cleaning process involved:

- Removing special characters.
- Eliminating duplicate entries.
- Column renaming
- Word embedding
## Data Cleaning

The JSON files were uploaded into Jupyter notebook turned in pandas Dataframe. Data cleaning was carried out using a Python notebook. The datasets were then converted into csv files. The cleaning process involved:

- Removing special characters.
- Eliminating duplicate entries.
- Column renaming
- Word embedding
## Data Cleaning

The JSON files were uploaded into Jupyter notebook turned in pandas Dataframe. Data cleaning was carried out using a Python notebook. The datasets were then converted into csv files. The cleaning process involved:

- Removing special characters.
- Eliminating duplicate entries.
- Column renaming
- Word embedding
## Data Transformation and Analysisx

The cleaned datasets were then imported into Power BI for further transformation and analysis. This involved:

- Changing data types.
- Creating new columns.
- Establishing relationships between tables using the match_id column.
- New measures were created for further visualizations, including:

    - Total Runs
    - Total Wickets
    - Economy
    - Batting Average
    - Strike Rate
    - Number of innings batted
    - Number of innings bowled
    - Bowling strike Rate
    - Bowling Average
    - Average balls face
    - Boundary percentage
## Power BI Dashboard

The Power BI dashboard includes various reports based on different player types:

- Opener
- Anchor
- Finisher
- All-rounder
- Bowler
- Overall team selection (based on personal selection)
- Tooltips were added to display the best stats for each player.

<img width="671" alt="All Rounder" src="https://github.com/AtharvaPatil2002/ICC-CWC-2023-Data-Scrapping-and-Analysis/assets/97679489/56a7fa67-d4f6-4f9f-b535-b442df2ef610">
<img width="383" alt="Final 11" src="https://github.com/AtharvaPatil2002/ICC-CWC-2023-Data-Scrapping-and-Analysis/assets/97679489/8fd82230-a340-4853-873d-e4891907c55a">
<img width="577" alt="Bowler tooltip in use" src="https://github.com/AtharvaPatil2002/ICC-CWC-2023-Data-Scrapping-and-Analysis/assets/97679489/057716ca-e7fb-4261-9309-1c596f7baff3">

## Repository Structure

ODI-CWC-2023-Analysis

- Brightdata web scrapper codes
    - batting_summary.js
    - bowling_summary.js
    - cwc_results.js
    - players.js
- CSV_files
    - bating_summary.csv
    - bowling_summary.csv
    - cwc_results.csv
    - players.csv
- JSON_files
    - batting_summary.json
    - bowling_summary.json
    - cwc_results.json
    - players.json
- Power BI Dashboard
    - ICC CWC 2023 Analysis.pbix
    - Dashboard screenshots(Folder)
- Preprocessing in python
    - CWC analysis preprocessing.ipynb
## Dependencies

- Python 3.x
- Jupyter Notebook
- Pandas
- Power BI Desktop
- BrightData(Self made web scrapers)
## Usage
Begin by ensuring all dependencies are installed. Execute data cleaning and preprocessing steps as outlined in CWC analysis preprocessing.ipynb. Perform data transformation in power query of Power BI also create measures according to your preference to use in the dashboard. Prepare individual reports based upon player role and make a seperate team of the tournament report, also prepare tootltip on hover for every instance where a players name is mentioned in all 6 reports. Lastly, explore the insights and visualizations provided in the Power BI dashboard (ICC CWC 2023 Analysis.pbix).

## Contributors

Atharva Patil
## Acknowledgements

[BrightData](https://brightdata.com/) for providing web scrapping platform.
