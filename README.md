# StomatalConductanceAnalysis
Stomatal Conductance Analysis Pipeline with Photosynthesis Meter CIRAS3 Data

## Overview

This Python pipeline is designed for the analysis and visualization of stomatal conductance data collected using CIRAS3. 

## Features

- **Data Loading and Preprocessing:**
  - Load CIRAS3 data in **xml** files and convert into the dataframes use the defined function *xml_to_dataframe* from the folder file
  - One reference file which provide the plant information (genotype, plant_num, leaf_num) for each file
  - visulzie the raw data and preprocess data to handle missing values, outliers, or other data quality issues.
  - Calculation the Relative gs, elative gs was computed for each individual measured plant by normalizing gs to the initial steady-state gs value observed

