# Project: Business Intelligence with Tableau

## Dataset

Data for this project are contained in the data folder. The data set was derived from the Federal Aviation Administration (FAA) website (https://wildlife.faa.gov/) as a .numbers file. It deals with wildlife strikes to airplanes in the United States between 2001 and 2015.

## Workflow

### Gaining an Overview and Precleaning
The data set was precleaned using Python and pandas (faa_cleaning.ipynb file).The dataset was originally converted to csv, which did not import correctly using pandas. After conversion to xlsx and importing the data set was examined. Two columns ('Cost: Aircraft time out of service (hours)', 'Days') with large amounts of missing values were removed. The file 'strikes_clean.csv" was imported in Tableau.

### Data Processing using Tableau
In Tableau the data was further examined and visualized using concepts such as sorting, filtering, aggregations, etc., different types of visualizations were used (geographic maps, bar and line graphs, scatter plots, heatmaps, etc.). Each slide contains a description of the main findings that can be derived from the graphs as a list of bullet points. Visualizations were organized in dashboards (featuring captions and annotations) which were compiled to a story (presentation).

## Deliverable / Link to Presentation

The Tableau presentation can be found in my Tableau public profile (https://public.tableau.com/profile/svenja.h#!/vizhome/Wildlifevs_Airplanes-InsightsderivedfromtheFFAWildlifeStrikeDatabase/Presention).
