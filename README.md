# Best Neighborhood in Pittsburgh - Final Project

## Team Information

**Team Name:** East Carnegie Enthusiasts

**Team Members:**
- Riya Shah - ras425@pitt.edu
- Akansh Karody - akk195@pitt.edu
- Connor Seto - cms510@pitt.edu

**Canvas Group Number:** Group 29

## Repository Overview

This repository contains a data-driven analysis to determine the best neighborhood in Pittsburgh based on three safety metrics: air quality, fire incidents, and crime rates. We combined rankings from each metric to identify East Carnegie as the best neighborhood overall.

## Datasets Used

### 1. Air Quality / Toxic Air Releases
- **Description**: Contains data on toxic air releases reported to the EPA from facilities in Pittsburgh, including release amounts in pounds by ZIP code and reporting year.
- **Source**: WPRDC (Western Pennsylvania Regional Data Center) - Allegheny County Toxics Release Inventory
- **Link**: https://data.wprdc.org/dataset/toxic-release-inventory
- **Key Fields**: ZIP_CODE, REPORTING_YEAR, TOTAL_RELEASE

### 2. Fire Incidents in City of Pittsburgh
- **Description**: Records of fire incidents reported in Pittsburgh neighborhoods, including incident types, locations, and timestamps.
- **Source**: WPRDC
- **Link**: https://data.wprdc.org/dataset/fire-incidents-in-city-of-pittsburgh/resource/8d76ac6b-5ae8-4428-82a4-043130d17b02
- **Key Fields**: neighborhood, incident_type

### 3. Monthly Crime Statistics
- **Description**: Monthly crime data from Pittsburgh Police, including offense types and neighborhood locations. Analysis focuses on serious crimes (assaults, robberies, burglaries, violent crimes). Follows NIBRS reporting standard.
- **Source**: WPRDC - Monthly Criminal Activity Dashboard
- **Link**: https://data.wprdc.org/dataset/monthly-criminal-activity-dashboard
- **Time Period**: January 2024 - October 2025
- **Key Fields**: Neighborhood, NIBRS_Offense_Type

## Files in Repository

- `Final_Notebook.ipynb` - Combined final report notebook with all analyses
- `ras425_toxic_air.ipynb` - Riya's individual analysis
- `Akansh_Monthly_Crime.ipynb` - Akansh's individual analysis
- `cms510-Finall-Project (1).ipynb` - Connor's individual analysis
- `toxic_air_releases.csv` - Air quality dataset
- `fpsnippets.py` - Helper functions for ZIP code to neighborhood conversion
- `ZIP_TRACT_032020.csv` - ZIP code to census tract mapping data
