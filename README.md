# Analyzing Arrest Patterns in Chicago
_Chicago Police Department (CPD) arrest data on offenses, locations, and demographics_

Data sourced from **City of Chicago**: https://catalog.data.gov/dataset/arrests

This GitHub repository contains the code used for the data cleaning, exploratory analysis, and visualization process, as well as the original and cleaned datasets sourced from the Chicago Police Department (CPD) Automated Arrest application (CLEAR system), which can be accessed via the link above.

The dataset is limited to adult arrests (individuals 18+) and captures key information about offenses, arrest locations, charges, and demographic details. Each arrest record may contain up to four charges, ranked by severity according to Illinois court system standards. The dataset also excludes any arrest records expunged under the Illinois Criminal Identification Act.

## This repository contains two folders:

### Data Cleaning, Exploration, and Visualization:
- **Arrests Chicago Data Cleaning.ipynb** = Code used during the data cleaning process
- **Arrests Chicago EDA and Visualization.ipynb** = Code used during the exploratory data analysis (EDA) and visualization process to address critical questions and visualize findings from the dataset.

### Dataset Files:
- **Arrests.csv** = The original raw dataset. Due to GitHub’s 25MB file size limit, this file could not be uploaded directly. It can be accessed and downloaded from the official source at https://catalog.data.gov/dataset/arrests
- **Arrests Cleaned.csv** = The cleaned and processed dataset generated using the code from Arrests Chicago Data Cleaning.ipynb. Note that this file is compressed in .csv.gz format to reduce file size for GitHub's upload limit.
