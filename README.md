# Unemployment Analysis

## Overview
This project focuses on analyzing the unemployment rate in a given dataset, with particular emphasis on the sharp increase during the COVID-19 pandemic. The analysis includes data preprocessing, visualization, and the extraction of meaningful insights about unemployment trends across regions and over time.
![Screenshot 2025-01-12 111517](https://github.com/user-attachments/assets/a315c3dd-eed1-46a0-8817-f443019abb36)
![Screenshot 2025-01-12 111549](https://github.com/user-attachments/assets/dbf87872-ced1-4080-b114-b9810fb83de9)
![Screenshot 2025-01-12 111626](https://github.com/user-attachments/assets/92ff796e-9fb5-42f5-8bc6-f19f16a799e2)


## Objective
The main objectives of this project are:
- To examine unemployment trends over time.
- To analyze regional variations in unemployment rates.
- To investigate the relationship between unemployment rates and labor participation rates.
- To provide actionable insights based on the analysis.

## Dataset Used
The dataset used for this project contains information about unemployment rates and related metrics. Key columns include:
- **Date:** The date of data collection.
- **Region:** The region where the data was collected.
- **Estimated Unemployment Rate (%):** The unemployment rate in percentage.
- **Estimated Labour Participation Rate (%):** The labor participation rate in percentage.

The dataset includes data points for various regions and dates, enabling a comprehensive analysis of unemployment trends.

## Analysis Steps
1. **Data Loading:** The dataset was loaded into a pandas DataFrame.
2. **Data Preprocessing:**
   - Column names were stripped of extra spaces.
   - The `Date` column was converted to datetime format for time-based analysis.
   - Missing values were handled by forward-filling or dropping, as appropriate.
3. **Data Visualization:**
   - **Bar Plot:** Displayed unemployment rates by region.
   - **Line Plot:** Showed unemployment rates over time for different regions.
   - **Scatter Plot:** Analyzed the relationship between labor participation and unemployment rates.

## Results
1. **Unemployment Trends by Region:**
   - Regions showed varying levels of unemployment, with some regions consistently exhibiting higher rates than others.
2. **Unemployment Over Time:**
   - A sharp increase in unemployment rates was observed during the COVID-19 pandemic.
   - Post-pandemic recovery trends varied by region.
3. **Relationship Between Labor Participation and Unemployment:**
   - A negative correlation was observed between labor participation rates and unemployment rates in several regions.

## Conclusion
This analysis highlights the significant impact of the COVID-19 pandemic on unemployment rates and the regional disparities in unemployment trends. Key takeaways include:
- The importance of region-specific policies to address unemployment.
- The potential role of increasing labor participation in mitigating unemployment.

By visualizing the data and extracting actionable insights, this project provides a foundation for further exploration of economic recovery strategies and labor market policies.

