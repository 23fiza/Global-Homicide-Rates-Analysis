# Global-Homicide-Rates-Analysis
Project Overview
In my latest data analysis project, I delved into global homicide rates using powerful tools such as NumPy, Pandas, and Matplotlib. This exploration aimed to uncover fascinating insights into global trends, socio-economic factors influencing homicide rates, and regional disparities.

Objectives
Global Trends: Identify and analyze global trends in homicide rates.
Socio-Economic Factors: Understand the socio-economic factors that influence homicide rates.
Regional Disparities: Identify regions with the highest and lowest homicide rates.
Data Set
The dataset includes homicide rates by country, along with additional socio-economic indicators such as GDP, unemployment rates, education levels, and more.

Tools and Libraries
NumPy for numerical computations and data manipulation.
Pandas for data cleaning, transformation, and analysis.
Matplotlib for data visualization.
Analysis Process
1. Data Cleaning and Transformation
Using Pandas, I performed essential data cleaning steps to ensure accuracy:

Checked for missing values and handled them appropriately.
Corrected data-type errors.
Removed duplicates.
Transformed and normalized the data for consistent analysis.
2. Exploratory Data Analysis (EDA)
With Pandas and NumPy, I conducted an in-depth exploratory data analysis:

Descriptive Statistics: Calculated mean, median, standard deviation, and other statistical measures for homicide rates.
Correlation Analysis: Examined the relationships between homicide rates and socio-economic factors.
Regional Analysis: Compared homicide rates across different regions and continents.

![SQL_pizza_sales (2).jpg](https://prod-files-secure.s3.us-west-2.amazonaws.com/8ab1bd97-207b-431d-852c-bb08883a8136/20ed8856-dea2-41e6-86c1-80c20448bbc7/SQL_pizza_sales_(2).jpg)

## Project Overview

In my latest data analysis project, I delved into global homicide rates using powerful tools such as NumPy, Pandas, and Matplotlib. This exploration aimed to uncover fascinating insights into global trends, socio-economic factors influencing homicide rates, and regional disparities.

## Objectives

1. **Global Trends:** Identify and analyze global trends in homicide rates.
2. **Socio-Economic Factors:** Understand the socio-economic factors that influence homicide rates.
3. **Regional Disparities:** Identify regions with the highest and lowest homicide rates.

## Data Set

The dataset includes homicide rates by country, along with additional socio-economic indicators such as GDP, unemployment rates, education levels, and more.

### About the Dataset

**Structure:**

- **Columns:** 195
- **Rows:** 6
- **Key Columns:**
    - `Location`
    - `Region`
    - `Subregion`
    - `Rate`
    - `Count`
    - `Year`

### Data Cleaning and Preparation Instructions

1. **Handling Missing Values:**
    - The dataset currently doesn't contain any values. However, if it does in the future, drop any rows with null values to ensure clean and accurate visualizations.
    - Example: If `Rate`, `Count`, or any other crucial column contains null values, those rows should be excluded from analysis to prevent errors.
2. **Data Type Conversion:**
    - Change the data type of the `Rate` column from `float` to `integer` for consistency and ease of analysis.
    - This conversion is essential for accurate statistical analysis and visualization, as integer data types often simplify interpretation and reduce the risk of floating-point errors.

### Summary of Key Performance Indicators (KPIs)

1. **Total Location Coverage:**
    - **Nigeria:** 23.18% of the total area covered.
    - **Brazil:** 25.02% of the total area covered.
    - **Remaining Countries:** The rest of the area is covered by countries such as India, Mexico, and the United States.
2. **Descriptive Statistics for Homicide Rates:**
    - **Mean Homicide Rate:** Provides the average rate of homicides across all locations.
    - **Median Homicide Rate:** Indicates the middle value of homicide rates when ordered from lowest to highest.
    - **Standard Deviation:** Measures the dispersion or variability of homicide rates from the mean.
3. **Regional Analysis:**
    - **Highest Homicide Rates:** Identified regions with the highest average homicide rates.
    - **Lowest Homicide Rates:** Identified regions with the lowest average homicide rates.
    - **Regional Trends:** Analysis of homicide rate trends across different regions.
4. **Socio-Economic Correlation:**
    - **Homicide Rate vs GDP:** Correlation between homicide rates and GDP to understand economic influences.
    - **Homicide Rate vs Unemployment:** Correlation between homicide rates and unemployment rates.
    - **Homicide Rate vs Education Levels:** Correlation between homicide rates and education levels.
5. **Peak Homicide Rates by Year:**
    - **Yearly Trends:** Analysis of how homicide rates have changed over the years.
    - **Significant Increases or Decreases:** Identification of years with significant changes in homicide rates.

## Tools and Libraries

- **NumPy** for numerical computations and data manipulation.
- **Pandas** for data cleaning, transformation, and analysis.
- **Matplotlib** for data visualization.

## Key Performance Indicators (KPIs) Summary

1. **Total Location Coverage:**
    - **Nigeria:** 23.18% of the total area covered.
    - **Brazil:** 25.02% of the total area covered.
    - **Remaining Countries:** The rest of the area is covered by countries such as India, Mexico, and the United States.
    
    ![SQL_pizza_sales (3).jpg](https://prod-files-secure.s3.us-west-2.amazonaws.com/8ab1bd97-207b-431d-852c-bb08883a8136/b2ee4b8e-e642-4cca-9b96-dd757faaf6aa/SQL_pizza_sales_(3).jpg)
    

---

1. Sum of Homicide Rate by Region
- **Africa:**
    - Total Rate: (Sum of all rates for countries within the African region)
- **Americas:**
    - Total Rate: (Sum of all rates for countries within the Americas region)
- **Asia:**
    - Total Rate: (Sum of all rates for countries within the Asian region)
- **Europe:**
    - Total Rate: (Sum of all rates for countries within the European region)
- **Oceania:**
    - Total Rate: (Sum of all rates for countries within the Oceania region)

![SQL_pizza_sales (4).jpg](https://prod-files-secure.s3.us-west-2.amazonaws.com/8ab1bd97-207b-431d-852c-bb08883a8136/fbba5879-b98e-4a91-8484-8ac146f2695a/SQL_pizza_sales_(4).jpg)
