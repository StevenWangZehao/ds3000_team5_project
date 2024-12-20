# DS3000 Final Project 
Group members: Talal Fakhoury, Zehao Wang, Nanak Sabharwal

## Overview
This repository contains code and data for a study investigating the predictability of short-term weather patterns and temperatures near Northeastern University. The project focuses on leveraging historical weather data to develop predictive models for temperature trends.

### Key Features
- **Jupyter Notebook**: Contains all the code used to collect, process, and analyze weather data. It includes data visualization, regression modeling, and residual analysis.
- **CSV File**: A csv file generated by the code, included as a fallback option for use due to API extraction limits.

---

## Files in This Repository
1. **`Team5FinalProject.ipynb`**  
   - The main Jupyter Notebook file with code for:
     - Data collection using the VisualCrossing Weather Query Builder.
     - Data preprocess.
     - Visualization of seasonal weather trends.
     - Implementation of two regression models (simple and multiple linear regression) to predict temperature trends.
     - Residual analysis to evaluate model performance.

2. **`weather_data.csv`**  
   - A csv file generated by the code, containing weather data from October 23, 2023, to October 23, 2024, for Northeastern University (360 Huntington Ave, Boston, MA). This file ensures accessibility for users without API access or facing API limitations.
