# Disease-surveillance-analysis-

#This repository contains R scripts for cleaning and preparing disease surveillance data collected from Lagos State, Nigeria. The dataset includes animal health reports from clinics and abattoirs, covering diseases such as Rabies, Anthrax, Avian Influenza, and Babesiosis.
Structure
Data/
└── raw/ # Original data (not uploaded here)
└── cleaned/ # Cleaned dataset (output)

script/
└── data_cleaning.R # Script for cleaning and preprocessing the dataset
Tools Used

-# R (data manipulation and analysis)
- #tidyverse (for data wrangling)
- #lubridate (for handling dates)
- #janitor (for cleaning column names)
- #readr, dplyr, ggplot2 (for data import and summary)

# Description
-The raw data required cleaning for:
- Consistent date formatting
- Standardising disease names and categorical variables
- Removing or imputing missing values
- Creating a clean dataset suitable for analysis and visualisation

The `data_cleaning.R` script performs the following steps:
1. Imports the raw `.csv` file using `read_csv()`
2. Cleans and formats date variables using `lubridate`
3. Standardizes disease names (e.g., "Rabies", "Anthrax", "Avian Influenza", "Babesiosis")
4. Removes rows with incomplete or irrelevant entries
5. Outputs a cleaned `.csv` file saved in `data/cleaned/`

# further Analysis
- Statistical analysis of disease trends glm()
- Geographic visualization of outbreak hotspots
- Integration with machine learning models for prediction

#Note

No personal or sensitive data is included in this repository. 

#Author
Dr. Oluwaseun Shakirat Bello  
Commonwealth Scholar | Global Health MPH | Data Enthusiast  
[LinkedIn](https://www.linkedin.com/in/oluwaseun-shakirat-b42a49104/)
