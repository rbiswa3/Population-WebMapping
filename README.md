# Population-WebMapping 
This repository contains the deliverables for Lab 4, focused on creating interactive choropleth web maps using Mapbox GL JS.

Repository Structure

The project follows the specified file structure, ensuring that all data files are organized within the assets folder and all HTML pages are at the repository root.

[your_repository_name]
    │ index.html
    │ pop_density.html
    │ wa_covid_cases.html
    │ readme.md
    ├─assets
    │      stateData.geojson
    │      wa-covid-data-102521.geojson


Map Overview

1. U.S. Population Density (pop_density.html)

Dataset: stateData.geojson

Visualization: Choropleth map showing population density (people per square mile) across U.S. states.

Interactivity: On hover, a tooltip displays the state name and its precise population density value.

2. Washington COVID-19 Data (wa_covid_cases.html)

Dataset: wa-covid-data-102521.geojson

Visualization: Choropleth map showing Cumulative Cases per 10,000 residents (casePer10k) for Washington State counties.

Interactivity: On hover, a comprehensive info box displays the county name and the three key metrics from the data:

casePer10k

deathPer10k

fullyVaxPer10k

Data Sources for WA COVID-19 Map

COVID-19 Case and Death Data: The New York Times

COVID-19 Vaccination Data: Washington State Department of Health

2021 Population Estimates: Washington State Office of Financial Management

Cartographic Boundary Data: U.S. Census Bureau
