# Project: Business Intelligence with Tableau

## Dataset

Data for this project are contained in the data folder. The data set was derived from the Federal Aviation Administration (FAA) website (https://wildlife.faa.gov/) as a .numbers file. It describes incidences of wildlife strikes to airplanes in the United States between January 2001 and May 2015.

## Workflow

### Gaining an Overview and Precleaning

The dataset was converted to csv, which did not import correctly using pandas. After conversion to xlsx and importing the data set was examined. The data set was precleaned using Python and pandas (faa_cleaning.ipynb file). Two columns ('Cost: Aircraft time out of service (hours)', 'Days') were removed due to large amounts of missing values ('strikes_clean.csv'). The file 'strikes_clean.csv' was imported in Tableau.

### Data Processing using Tableau

In Tableau the data was further examined and visualized using concepts such as sorting, filtering, aggregations. Different types of plots were used for visualization(geographic maps, bar and line graphs, scatter plots, heatmaps, etc.). Main findings derived from the graphs were summarized as a list of bullet points. Visualizations and findings/text were organized in dashboards (featuring captions and annotations) which were compiled to a story (presentation).

## Deliverable / Link to Presentation

The Tableau presentation can be found in my Tableau public profile (https://public.tableau.com/profile/svenja.h#!/vizhome/Wildlifevs_Airplanes-InsightsderivedfromtheFFAWildlifeStrikeDatabase/Presention).

## Sources Images

Images used in the presentation were downloaded from the following sources:

### Image 1
Airplane and birds: https://images.tribuneindia.com/cms/gall_content/2018/12/2018_12$largeimg23_Sunday_2018_012600245.jpg

### Image 2
FAA Wildlife Strike Database banner: https://wildlife.faa.gov/images/logo_wildlife.jpg

### Image 3
Dog on runway: https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ_iZ2LT4yT9otwAAhkxm546kb_04mW3PPQtFeb2T7_dMOFU29Z

### Image 4
Damaged airplane front: https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR2OdpHZu0BNx8y-PIk8kHEKiyz3gARtBlX0QOF2O3jg9zHzPkx0A

### Image 5
Damaged turbine: https://www.avionews.it/resources/800x800/cb31c4c11c5e8f3f71d7afb3da61726f.jpg.jpg

### Image 6
Dog with goggles: https://s3.amazonaws.com/images.gearjunkie.com/uploads/2015/04/Piper-12.jpg