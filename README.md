# Monitoring the Water Quality in Bhopal Region using Satellite Imagery and GIS Techniques

This is a collaborative and open sourece project promoted by Omdena VIT Bhopal Chapter.

Bhopal is known as "the city of lakes" in India. The Bhopal region has been facing environmental challenges regarding water quality for the past few decades (since the gas tragedy of 1989). Due to a lack of regular monitoring, the Government is unable to identify and address issues regarding water pollution, its supply, and any ongoing contamination issues in Bhopal Lakes. Many residents of Bhopal still lack access to clean drinking water that comes under the jurisdiction of the Bhopal Municipal Corporation (BMC).

To precisely determine the water quality in the Bhopal region, the project intends to construct a system for processing satellite photos and GIS data to monitor water quality parameters (pH, temperature, salinity, dissolved oxygen, turbidity, suspended matter, etc).

Project detailed description: https://omdena.com/projects/monitoring-the-water-quality-in-bhopal-region/

## Objectives

* Collect water quality parameters (pH, temperature, salinity, dissolved oxygen, turbidity, suspended matter, etc), measured by
satellite remote sensing for different lakes and dams in Bhopal area.

* Perform EDA (exploratory data analysis) and visualizations on the data collected to get insights and comparisons with water quality
standard thresholds.

* In this project I was responsible of collecting data and performing EDA for Kerwa Dam.


## Data Collection - Google Earth Engine APIs

The satellite data for different water quality related indexes (pH, temperature, turbidity, salinity, etc) was collected by using Google Earth Engine Python APIs.

Link to sample code in Colab: https://colab.research.google.com/drive/1WhR9HkJawPfC9JefXdMCLAxBZ5Cg5tFG?usp=sharing

![Data Collection](./images/gee_kerwa_dam.png)


## EDA - Exploratory Data Analysis

After data collection, different statistical and EDA analysis were performed in order to understand the patterns in the data and to get first insights on the behavior of different water quality indices over the years from 2018 to 2022.

![EDA Sweetviz](./images/sweetviz.jpg)

![EDA Pandas Profiling](./images/pandas_profiling.png)

![EDA Corr Matrix](./images/corr_matrix.png)


## Streamlit Web App Deployed

At the end of the project the team developed a Web App by using Streamlit Python framework to showcase project details and results.

Link to the Web App:  https://vaasu2002-omdena-bhopal-water-quality-dashboard-main-pzjmtf.streamlit.app/

![Streamlit App](./images/StreamlitApp.png)


## Project GitHub Repo

https://github.com/OmdenaAI/omdena-bhopal-water-quality-monitoring



