## U.S. International Air Traffic Data Analysis

## Project Overview

This repository contains an analysis of U.S. international air traffic data, focusing on passenger and freight statistics. The dataset is sourced from the U.S. Department of Transportation and includes detailed information on flights between U.S. and non-U.S. gateways. The goal of this project is to provide insights into air traffic patterns, busiest airports, and carrier performance, helping stakeholders make informed decisions.

## Objectives

1. **Identify the Top 10 Busiest Airports**: Determine the airports with the highest traffic.
2. **Monthly Total of Flights**: Analyze the total number of flights per month.
3. **Yearly Trend of Flights**: Examine the trends in air traffic over the years.
4. **Distribution of Passenger Flights**: Understand the distribution between scheduled and charter flights.
5. **Top 5 Busiest Foreign Gateway Airports**: Identify the foreign airports with the highest traffic.
6. **Top 5 Busiest Usage Airports**: Identify the U.S. airports with the highest traffic.
7. **Top 5 Busiest Carriers**: Determine the carriers with the highest number of flights.
8. **Passenger Flights between Airports**: Analyze the traffic between specific airports.

## Data Sources and Tools Used

### **Dataset:** U.S. International Air Passenger and Freight Statistics Report

### **Tools Used:**

- Microsoft Excel: Data cleaning and preprocessing
- Power BI Desktop: Data visualization and dashboard creation

## Exploratory Data Analysis (EDA)

### **Data Description**

The dataset contains key attributes that define air traffic operations. The key columns include:

- **data_dte**: The date when the data was recorded.
- **Year**: The year of the recorded data.
- **Month**: The month of the recorded data.
- **usg_apt_id**: The unique identifier for the usage airport.
- **usg_apt**: The name or code of the usage airport.
- **usg_wac**: The World Area Code (WAC) for the usage airport.
- **fg_apt_id**: The unique identifier for the foreign gateway airport.
- **fg_apt**: The name or code of the foreign gateway airport.
- **fg_wac**: The World Area Code (WAC) for the foreign gateway airport.
- **airlineid**: The unique identifier for the airline.
- **carrier**: The code or abbreviation for the airline carrier.
- **carriergroup**: The group to which the airline carrier belongs.
- **type**: The type of service (e.g., domestic, international).
- **Scheduled**: The number of scheduled flights.
- **Charter**: The number of charter flights.
- **Total**: The total number of flights (Scheduled + Charter).

## Methodology

### **Data Cleaning & Preparation**

- Handled missing values and standardized data formats.
- Created calculated fields for total flights and passenger counts.
- Grouped airports and carriers by traffic volume.

### **Data Analysis in Excel**

- Used Pivot Tables to summarize flight trends by month and year.
- Analyzed the distribution of scheduled and charter flights.
- Examined the busiest airports and carriers.

### **Visualization & Insights in Power BI**

- Built an interactive dashboard summarizing key findings.
- Created bar charts to compare the busiest airports and carriers.
- Analyzed yearly trends in air traffic.
- Evaluated the distribution of passenger flights.

## Key Insights & Interpretation

1. **Top 5 Busiest Foreign Gateway Airports**

   - YYZ: 43K flights
   - CUN: 30K flights
   - YUL: 18K flights
   - YVR: 18K flights
   - MEX: 18K flights

2. **Top 5 Busiest Usage Airports**

   - JFK: 64K flights
   - MIA: 62K flights
   - LAX: 48K flights
   - ORD: 35K flights
   - EWR: 33K flights

3. **Top 5 Busiest Carriers**

   - AA: 59K flights
   - DL: 48K flights
   - UA: 42K flights
   - CO: 26K flights
   - AC: 20K flights

4. **Distribution of Passenger Flights**

   - Scheduled: 4bn flights (97.05%)
   - Charter: 0bn flights (2.95%)

5. **Yearly Trend of Flights**

   - 1990: 8K flights
   - 2000: 16K flights
   - 2010: 21K flights
   - 2020: 24K flights

6. **Passenger Flights between Airports**

   - Usage Airport: 54 flights (20.61%)
   - Foreign Gateway Airport: 208 flights (79.39%)

## Data Visuals

The Power BI dashboard includes:

- Bar charts comparing the busiest airports and carriers.
- Line charts showing yearly trends in air traffic.
- Pie charts illustrating the distribution of passenger flights.
- Maps visualizing the geographic distribution of flights.

### **Dashboard Preview**
![image](https://github.com/user-attachments/assets/dae1d403-9570-448c-933c-5ddca533be3f)

## Data Story

This dashboard was created to analyze U.S. international air traffic data, focusing on identifying the busiest airports, carriers, and trends over time. The goal is to provide insights that assist stakeholders in making informed decisions about air traffic management and strategic planning.

### **Key Findings**

- JFK, MIA, and LAX are the top usage airports.
- YYZ, CUN, and YUL are the top foreign gateway airports.
- American Airlines (AA) and Delta Airlines (DL) are the busiest carriers.
- Scheduled flights dominate the air traffic, with charter flights being a small fraction.
- Air traffic has shown a steady increase over the years.

### **Conclusion**

To optimize air traffic management and planning:

- Focus on the busiest airports for infrastructure improvements.
- Target high-traffic carriers for partnerships and collaborations.
- Monitor trends to anticipate future demands and adjust operations accordingly.
- Continue analyzing data to inform policy and operational decisions.

## Limitations
- Data Completeness: The dataset may not include all flights, potentially leading to incomplete insights.
- Data Accuracy: There may be errors or inconsistencies in the data that could affect the accuracy of the analysis.
- Generalizability: Insights derived from this dataset may not be generalizable to other countries or regions.
- Temporal Limitations: The analysis is based on historical data and may not reflect current or future trends.
- Airport Traffic: The analysis assumes that airport traffic is a primary factor in air traffic patterns, which may not always be the case.
- Carrier Performance: The analysis assumes that carrier performance is a primary factor in air traffic, which may not always be the case.
- Geographical Distribution: The analysis assumes that geographical distribution is a primary factor in air traffic, which may not always be the case.
- Data Granularity: The dataset may lack detailed information on specific flight routes, leading to less precise insights.
