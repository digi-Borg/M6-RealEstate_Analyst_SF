# FinTech Real Estate Analysis Using Data Visualization to locate Investment Properties

*'Welcome to my FinTech project as a 'Real Estate Analyst to find Investment Properties in San Francisco'*

---

## Background
This project is for a Real Estate analyst at a property technology company developing software as a novel approach offering real estate investors an online service to assist them in locating property purchasing opportunities for their investment portfolio. A trial run is focused on the San Francisco real estate market to evaluate and prove it successful.  

The real estate technology created utilizes a program to gather, evaluate, analyze data in order to locate viable investment property opportunities in the San Franciso area. Its program application tools includes numerical and visual aggregation, interactive visualizations, and geospatial software to analyze and visualize real estate data. Utilizing this program can efficiently expedite decisions for investment opportunities.    

In order to the meet needs in achieving the goals of the user, different programming analysis tools were designed in progressive steps for this project: First is to aquire raw data from the San Francisco census to get information on *neighborhoods, sales price-per-square foot, housing units, gross rent*, which is then grouped and calculated to find *housing units-per-year*. Second, is to calculate the *average sale prices-per-square foot* and *gross rent* to analyze different value trends in Sanfrancisco. Third is to focus the value trends for investment opportunities by comparing *sales prices-per-square foot* and *gross rent* by neighborhood. Fourth, is to build a map to visually locate neighborhoods and compare property data for *average price-per-square foot* values and *average gross rent* returns.  

Numerical and visual aggregation is utilized from the imported San Francisco census data in the first step to calculate the number of *housing units-per-year*, and then visualize the results from 2010 to 2016 in a bar chart to analyze growth trends. The second step of the program uses numerical aggregation and calculates the *average prices-per-square foot* and *gross rent*, and visualizes the aggregated results in a line chart of San Francisco property value trends over the years. The third part uses interactive visualizations in a line chart with a hvplot widget to explore the *average sale price-per-square foot* and *gross rent* by neighborhood. The fourth program uses interactive visualizations with hvPlot and GeoViews to explore the geospatial relationships in the data through an Interactive Neighborhood map to visually locate neighborhoods from a overhead vantage point and compare property location for potential investment decisions.


This program gives users a step by step process to aggregate numerical data into visual plot charts for finding real estate investment opportunities and make property purchases. Utilizing this real estate property technology, real estate investment managers can efficiently connect data relationships to trending property values and use interactive visualizations for investment decisions.  


---

## Technologies

The software operates on python 3.9 with the installation package imports embedded with Anaconda3 installation. It includes 'PyViz' as a single platform for accessing multiple visualization libraries from the Python visualization package. Two PyViz libraries, hvPlot and GeoViews are utilized for this program.

* [anaconda3](https://docs.anaconda.com/anaconda/install/windows/e) .

* [pyviz hvplot geoviews](https://hvplot.holoviz.org/index.html#) .

---

## Installation Guide

Before running the applications first activate the Conda development environment and launch JupyterLab to import the following required libraries apps. If hvplot and geo views is not installed with anaconda, the recommended way to install hvPlot is using the conda terminal command below provided by Anaconda. 

```python libraries
import pandas as pd
import hvplot.pandas
from bokeh.models import HoverTool
from pathlib import Path 

[conda install -c pyviz hvplot geoviews] or [pip install geoviews] 
```

---
# Usage

This application is launched from web-based JupyterLab utilizing Pandas which is designed for data analysis to write and read code in an IDE and review results through the Python libraries. The Anaconda3 software application includes the Pandas libraries; **'PyViz' as a single platform for accessing two PyViz libraries, hvPlot and GeoViews.** They are utilized for high-level plot charts in this program from the Python visualization package. **HoverTool**is imported from the Bokeh library for **hvplot and GeoViews**. It utilize data frames and plot charts in an integrated Conda development environment. 

The program is developed in Jupyter notebooks on a **.ipny** file. Imports of PyViz libraries **hvplots and geoviews**; and with  **HoverTool** are used for more advanced interactive chart environments. These apps makes it much easier to explore data in interactive plot properties, without having to write additional code to select ranges, columns, or data values manually. These interactive visualization libraries also improve browser plot presentations. Together they advance functions to create informative visualizations from the Pandas DataFrames and data metrics. 

The **san_francisco_housing.ipynb** program utilizing the above libraries has several steps to retrieve, aggregate, create, evaluate, and analyze data to make forcasts for real estate investing. Through these steps real estate portfolio managers can visualize property opportunities to efficiently aid purchase decisions in meeting investment goals.   

```python
financial_planning_tools.ipynb
```
 

---

## Contributors

*Provided to you by digi-Borg FinTek*, 
Dana Hayes: nydane1@gmail.com

---

## License

Columbia U. Engineering