# Forest Fire Hotspot Analysis in India 

## 🛰️ Project Overview

This project focuses on identifying and analyzing forest fire hotspots across India using geospatial data and satellite remote sensing techniques. This project was conducted as a term project for the EES 654 (Geoinformatics) course under the guidance of Dr. Somil Swarnkar at the Indian Institute of Science Education and Research, Bhopal. The study aims to provide insights into the spatial and temporal patterns of forest fires, enabling effective management and conservation strategies. The analysis covers the period from January 2001 to July 2024 and utilizes data from NASA's Fire Information for Resource Management System (FIRMS) and MODIS sensor data for forest cover fraction.

## 🎯 Objectives

*   **Identify** forest fire hotspots in India using geospatial analysis.
*   **Analyze** temporal trends and seasonal variations in forest fire occurrences.
*   **Correlate** forest fire hotspots with forest types and climatic conditions.
*   **Provide** recommendations for forest fire management and conservation.

## 📊 Data Sources

*   NASA's Fire Information for Resource Management System (FIRMS)
*   MODIS Forest Cover Fraction (FCF) dataset from EOS-TERRA

## ⚙️ Methodology

*   **Data Acquisition:** Obtained forest fire data from NASA's FIRMS and forest cover fraction data from MODIS aboard EOS-TERRA.
*   **Grid-Based Segmentation:** Divided fire data into 0.5 x 0.5-degree spatial grids for systematic analysis.
*   **Monthly Summation:** Calculated monthly fire counts for each grid to assess temporal variations.
*   **Filtering High Forest Cover Areas:** Retained grids with a forest cover fraction exceeding 10%.
*   **Hotspot Analysis:**
    *   Selected the top 30% of grids with the highest fire counts as major fire-prone areas.
    *   Analyzed peak fire occurrences across multiple years to detect recurring patterns.
    *   Examined seasonal variations (pre-monsoon: Feb-May, post-monsoon: Oct-Jan) to determine fire trends.

## 🔑 Key Findings

*   **Temporal Trends:** No evident increasing trend in forest fire occurrences was observed, contrary to some literature. Forest cover fraction shows an increasing trend, while fire counts decreased until 2020, followed by a changing trend.
*   **Hotspot Locations:** Major hotspots identified in Odisha, Maharashtra, Madhya Pradesh, Andhra Pradesh, and Northeast India (Assam, Nagaland, Manipur, Arunachal Pradesh).
*   **Forest Types:** Tropical dry deciduous forests are the most fire-prone, accounting for the majority of hotspots.
*   **Seasonal Patterns:** March is a critical month for forest fires, with significant activity in the pre-monsoon period.

## 🔭 Future Work

*   Conduct further research to understand the impact of climate and human activities on forest fires.
*   Utilize advanced technologies, such as satellite remote sensing and GIS, for improved fire monitoring and management.
