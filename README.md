# Hospital Accessibility Visualization Project

## Overview
This project visualizes the accessibility of hospitals across US counties. It leverages geospatial data analysis and visualization techniques to map the maximum distance from the center of each county to the nearest hospital.

## Libraries Used

- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **GeoPandas**: For handling geospatial data.
- **Plotly**: For creating interactive maps and visualizations.
- **Geopy**: For geodesic distance calculations.

## Dataset
The project utilizes census geospatial data, encompassing county-level population data in 2000 and 2020 and Education data from 2020 at the county level.
https://data.census.gov/

## Visualizations

### Folium Maps
- **Interactive Choropleth Map for 2000 and 2020**: This map displays the population distribution across US counties for the years 2000 and 2020. Two layers, one for each year, allow users to switch between them to observe changes over time.



- **Interactive Map Showing Percentage Difference**: This map visualizes the percentage difference in population changes at the county level. The symmetric color map ranges from red (population decrease) to blue (population increase), with white indicating minimal or no change.




### Plotly Choropleth Map
- **Interactive Plotly Map with Population Data**: This Plotly map provides an interactive choropleth representation of population data for US counties in 2000 and 2020. The map includes a slider to switch between the years, displaying changes in population over two decades.




- **High School Graduate Percentage among Ages 18-24 in 2020**: This interactive map shows the percentage of high school graduates among the 18-24 age group across US counties in 2020. The map utilizes a color scale to represent varying percentages, with detailed statistics available in the hover tooltip for each county. The data includes the total population in this age group, the number of high school graduates, bachelor’s degree holders, and those with less education.





## Installation
To set up this project locally:
1. Install Dependencies:
- Install [Anaconda](https://www.anaconda.com/distribution/) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html).
- Clone the repository and navigate to the root directory.
  ```bash
  git clone https://github.com/mbabeykoon/GeoSpatial.git
  cd GeoSpatial
- Run the following command to create a conda environment from the `environment.yml` file:
  ```bash
  conda env create -f environment.yml
  conda activate env_name #change this to your environment name
 
2. Run Jupyter Notebooks:
- Navigate to the notebook directory.
- Open the notebooks in Jupyter Lab/Notebook.
