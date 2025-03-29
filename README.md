# **Mosquito-Borne Disease and Climate Data**  

This repository contains datasets related to **mosquito-borne diseases** (West Nile Virus, Dengue, Malaria, and Zika) and **climate data** (temperature and precipitation) for use in research on how global temperature changes impact disease spread.  

---

## **📂 Data Sources**  

### **Climate Data**  
- **Global Temperature Data** (Our World in Data)  
  - [Monthly Average Surface Temperatures by Year](https://ourworldindata.org/grapher/monthly-average-surface-temperatures-by-year?tab=table)  
- **United States Temperature & Precipitation Data** (NOAA)  
  - [Climate at a Glance - Historical Data](https://www.ncei.noaa.gov/access/monitoring/climate-at-a-glance/statewide/time-series)
  - **Updated Global Temp data to avg_temp per year instead of month for each country
  - ** Code - SELECT [Country], [Year], AVG([Temp C (average)]) as Avg_Temp
From[dbo].[Global_temp]
GROUP By [Country], [Year]
Order By [Country], [Year]
  - 

---

### **Mosquito-Borne Disease Data**  
- **Global Dengue Data** (OpenDengue)  
  - [OpenDengue Dataset](https://opendengue.org/data.html)  
- **Global Malaria Data** (WHO)  
  - [WHO Malaria Cases](https://www.who.int/data/gho/data/indicators/indicator-details/GHO/total-number-of-malaria-cases-presumed-confirmed-cases)  
- **United States West Nile Virus Case Counts** (CDC)  
  - [CDC MMWR Reports](https://www.cdc.gov/mmwr/)  
- **European West Nile Virus Case Counts** (ECDC)  
  - [ECDC West Nile Surveillance Data](https://www.ecdc.europa.eu/en/west-nile-fever/surveillance-and-disease-data/historical)  

---

## **📊 Repository Contents**  
- **CSV/XLSX Files**: Processed datasets containing mosquito-borne disease counts and climate data.  
- **SQL Database**: The data has been structured and stored in an **Azure SQL database** for analysis.  
- **Python Scripts**: Scripts for cleaning, transforming, and analyzing the data.  

---

## **💡 Usage**  
This repository is intended for research on how climate change influences the spread of mosquito-borne diseases. The data is structured to allow comparisons between **temperature/precipitation** and **disease incidence** over time.  

Feel free to use these datasets for your own research, and let us know if you have any questions or suggestions!  

---
