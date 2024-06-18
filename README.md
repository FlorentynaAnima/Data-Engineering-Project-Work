# PROJECT TYPE: ANALYTICS ENGINEERING PROJECT

# Global Health Analysis: Visualizing Life Expectancy and Key Health Indicators and Making Future Forecasts

## Project Overview

This project aims to analyze various health indicators across different countries using Power BI. The analysis includes comparison analysis, trend analysis, demographic analysis, and forecasting. The primary goal is to provide insights into the health status of different countries and predict future health trends.



# Scope and Objectives

- **Scope**: This project focuses on analyzing health indicators such as Life Expectancy, HIV/AIDS rates, Hepatits B prevalence, Measles, and Polio rates across multiple countries over a specified time period(2000-2015)

- **Objectives**:
  - To understand the trends in various health indicators over time.
  - To identify correlations between different health indicators.
  - To analyze the distribution of health indicators across different demographics.
  - To forecast future trends for key health indicators.

## Data Sources

The data for this project was a secondary data was sourced from :
- Kaggle

# METHODOLOGY:

## Data Preparation

### Steps:

1. **Data Collection**:
   - Data was downloaded from Kaggle website.
2. **Data Cleaning**:
   - Handled missing values by using Power Query Editor .
   - Removed Unwanted Columns.
   - Removed Duplicates.
   - Removed Errors
   - Removed Blank Rows
3. **Data Transformation**:
   - Transformed the raw data into a structured format suitable for analysis.
   - Created a a report view metrics and dimensions for analysis.

## Visualization and Analysis

### 1. Comparison Analysis
# Two Visuals were implemented

- **Visual**: Bar Chart
- **Purpose**: To compare two health indicators by country over time(HIV/AIDS,Hepatitis B) trends over time
- **Implementation**:
  - Axis: Country(Y-Axis),HIV/AIDS/Hepatitis B(X-Axis)

  **Visual**: Scatter Chart
- **Purpose**: To identify correlation between HIV/AIDS and life expectancy
- **Implementation**:
  - Axis: HIV/AIDS(Y-Axis),(X-Axis)-Life Expectency
  - Values: Country
  

### 2. Trend Analysis
# Two Visuals were implemented

- **Visual**: Line Chart
- **Purpose**: To identify trends in different countries and their corresponding life expectancy.
- **Implementation**:
  - X-Axis:country
  - Y-Axis: Life Expectancy
  - Legend: Year

  **Visual**: Line Chart
- **Purpose**: To identify trends in different countries and their sum of HIV/AIDS rate.
- **Implementation**:
  - X-Axis:Country
  - Y-Axis: Sum of Rate of HIV/AIDS
  - Legend: Year

### 3. Demographic Analysis
- **Visual**: Pie Chart/Tree Map
- **Purpose**: To show the distribution of health indicators across different demographic groups.
- **Implementation**:
  - Values: Population
  - Legend: Demographic Group (if available, otherwise regions or countries)

  #### 4. Demographic Analysis
  **Visual**: Pie Chart
- **Purpose**: To show the distribution of life expectancy accross different demographic groups.
- **Implementation**:
  - Values: Sum of Life expectancy
  - Legend: Countries

  ## INTERACTIVE ELEMENTS
  -Slicer

 # INNOVATION

 # Forecasting/Trend Line
- **Visual**: Line Chart with Forecast 
- **Purpose**: To predict future trends for key health indicators.
- **Implementation**:
  - Axis: Country
  - Values: Life Expectancy
  - Forecasting using Power BI’s built-in features
   **Visual**: Scatter Chart with Trend Line
- **Purpose**: To predict future trends for key health indicators(HIV/AIDS)
- **Implementation**:
  - Axis: Sum of HIV/AIDS (y-axis), Sum of Life Expentancy(X-axis)
  - Values: Health Indicator Values
  - 
  - Forecasting using Power BI’s built-in features

## LIMITATIONS
- Inabilty to generate map as visuals for geographic analysis

## Tools and Technologies Used

- **Power BI**: For data visualization and analysis.
- **Power BI**: For initial data cleaning and transformation.
- **GitHub**: For project version control and documentation.






