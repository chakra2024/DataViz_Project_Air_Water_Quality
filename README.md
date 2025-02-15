# Data Visualization Project - City Pollution Analytics: Air Quality & Water Pollution in France 

## **Project Overview**
This project analyzes air quality and water pollution trends across world cities, focusing on **France**. Using data from Kaggle (originally from Numbeo), this study examines regional and city-level pollution trends and explores potential correlations between air and water pollution.

## **Note** - The actual notebook file contains the in-depth analysis of the project as well as the visualizations

## **Dataset**
- **Source**: [Kaggle - World Cities Air Quality and Water Pollution](https://www.kaggle.com/datasets/cityapiio/world-cities-air-quality-and-water-polution/data)
- **Original Data Source**: Numbeo (https://www.numbeo.com)
- **Collected On**: October 18, 2021
- **Size**: 3963 records, 5 columns
- **Columns**:
  - `City`: City name
  - `Region`: Region/state name
  - `Country`: Country name
  - `AirQuality`: Index (0 = bad, 100 = best)
  - `WaterPollution`: Index (0 = no pollution, 100 = extreme pollution)

## **Prerequisites**
- **Python 3.10 and above** 
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

## **Research Question**
- **How do air quality and water pollution vary across regions and cities in France?**

### **Sub-Questions**
1. **Regional Trends:** What are the air and water pollution trends in different regions of France?
2. **City-wise Analysis:** Which cities have the best and worst pollution levels?
3. **Correlation Analysis:** Is there a relationship between air quality and water pollution?

## **Preprocessing and Data Cleaning**
- Cleaned column names by removing spaces and quotes.
- Standardized text fields (Region, Country).
- Converted air quality and water pollution values to numerical format.
- Replaced missing region values with **"Other Regions"**.

## **Methodology & Visualization**
1. **Regional Analysis** (Bar Chart) – Compares air and water pollution indices across **"Ile-de-France," "Other Regions," and "Reunion"**.
2. **City-wise Trends** (Bar Charts) – Highlights best and worst cities for air and water quality.
3. **Correlation Analysis** (Scatter Plot) – Investigates the relationship between air and water pollution.

## **Key Findings**
- **"Ile-de-France"** has lower air quality but better water quality compared to other regions.
- **"Limoges" and "Saint-Etienne"** exhibit excellent air and water quality, while **"Paris" and "Marseille"** suffer from high pollution levels.
- A **weak negative correlation (-0.33)** between air and water pollution suggests that the two factors are influenced by separate environmental variables.

## **Limitations & Future Work**
- Dataset is **static (2021)** and lacks time-series trends.
- No additional socio-economic or industrial activity data was included.
- Future research can **integrate GIS heatmaps** or **time-based pollution trends** for deeper analysis.

## **Technologies Used**
- **Python** (Pandas, Matplotlib, Seaborn)
- **Data Cleaning & Processing**
- **Exploratory Data Analysis**
- **Data Visualization**
- **Correlation Analysis**

