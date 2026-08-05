# Climate and Environmental Intelligence Dashboard

## DSA3050A Group 7 Project

---

## Group Members

| Member Name | Student ID |
|--------------|------------|
| Member 1 | XXXXXXXX |
| Member 2 | XXXXXXXX |
| Member 3 | XXXXXXXX |
| Member 4 | XXXXXXXX |

---

## Dataset URL:
https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository

---
## Dataset Description:
No. of rows:154,556 Rows

No. of columns: 41 columns

No. of tables: 2 tables

This dataset provides daily weather information for capital cities around the world. Unlike forecast data, this dataset offers a comprehensive set of features that reflect the current weather conditions around the world.
Starting from August 29, 2023.
It provides over 40+ features , including temperature, wind, pressure, precipitation, humidity, visibility, air quality measurements and more. The dataset is valuable for analyzing Global weather patterns, exploring climate trends, and understanding the relationships between different weather parameters.

 ---
 ## Business Problem:
 Global atmospheric volatility and worsening air pollution pose severe risks to municipal public health, city infrastructure, and ecological balance. Environmental protection agencies, public health departments, and urban policy directors often lack a unified, real-time Business Intelligence (BI) platform to continuously monitor spatial-temporal weather trends alongside hazardous air pollutants. Without centralized analytics, identifying vulnerable geographic clusters, tracking dangerous particulate matter accumulation (PM2.5 and PM10 ), and detecting sudden extreme heat or ultraviolet (UV) radiation spikes remains reactive rather than proactive. 

 ---
 ## Power query transformations:
 - Renamed unclear columns
- Corrected data types
- Removed duplicates
- Removed blank rows
- Trimmed and cleaned text columns
- Replaced inconsistent values
- Handled missing values
- Removed unnecessary columns
- Split and merged columns
- Created custom columns
- Created conditional columns
- Date_table added
- Summary_Regional_Averages table created
---
## Data model explanation
A *star schema* data model was implemented to improve dashboard performance and simplify analysis.

### Fact Table

* Weather observations containing environmental measurements.

### Dimension Tables

* Date
* Country
* Location
* Weather
* PM2.5 Risk
* Moon Phase
* Regional Summary

Relationships were created between the fact table and each dimension table to enable filtering, drill-down analysis and time intelligence calculations while minimizing data redundancy.


---
## DAX measures created
The project includes several custom DAX measures, including:

* Average Temperature
* Average Humidity
* Average UV Index
* Total Rainfall
* Rainfall per Location
* Temperature Ranking
* Rainfall Ranking
* PM2.5 Ranking
* PM2.5 Ratio
* Visibility Ratio
* Air Quality Status
* Rainfall Status
* Heat Alert Indicator
* Selected Weather
* Dynamic Dashboard Title

These measures provide KPI calculations, rankings, ratios, dynamic reporting and business insights.


---
## Dashboard pages explained
## 1. Executive Dashboard

Provides an overview of key environmental indicators including:

* Average Temperature
* Rainfall
* Humidity
* Air Quality
* UV Index
* Heat Alerts

---

## 2. Air Quality Analysis

Displays pollution trends using:

* PM2.5
* PM10
* Carbon Monoxide
* Air Quality Risk Categories
* Pollution Rankings

---

## 3. Climate Trends

Shows environmental trends over time including:

* Temperature
* Rainfall
* Atmospheric Pressure
* Humidity
* Visibility

---

## 4. Regional Analysis

Compares environmental indicators between countries and cities using interactive maps and charts.

---
## Key insights
- There is Moderate Air Quality Risk because the Average PM2.5 rests at 19.50, with "Moderate" conditions consistently present in observations, this posing ongoing health concerns for sensitive populations.
- The "Carbon Monoxide Levels by Region" chart indicates that cities such as Abu Dhabi, Abuja, Accra, Addis Ababa, and Aguaray record similar high carbon monoxide values.
- -The dashboard shows an average temperature of 20.21°C, while the yearly temperature trend remains almost flat from 2024 to 2026. This shows that average temperature has not changed widely during the period, showing that shortterm climate conditions have remained relatively consistent.
- The "Air Quality Risk by Moon Phase" chart shows differences in the number of observations across the moon phases; the Waxing Gibbous phase being the largest proportion (approximately 23%).
- The yearly pressure chart shows that total atmospheric pressure remains relatively constant throughout the reporting period. If combined with stable temperatures, this suggests that fluctuations in air quality are more likely driven by pollutant emissions than by large-scale atmospheric pressure changes.

---
## Recommendations
-Implementation of stricter policies for emission control in the regions with high carbon monoxide levels through vehicle emission inspections and cleaner public transport would improve the air quality significantly. 

-With moderate air quality being dominant, the assigned agencies should strengthen public awareness that would encourage the vulnerable groups to limit their exposure during the period when the air quality is poor. 

-Expansion of the air quality monitoring stations in densely populated cities to identify hotspots in time, thus supporting better policy decisions. 

-Conducting research into the relationship between the environmental conditions and the air quality observed during the different moon phases. With understanding of the patterns, pollution forecasting may improve. 

-Monitoring of temperature and atmospheric pressure by the policy makers although they are stable should be conducted. This is to detect early signs of climate change and implement strategies to adapt. 

---

## Contribution summary for each member:

---

 
 

