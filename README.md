# Hospital Accessibility Visualization Project

## Overview
This project visualizes the accessibility of hospitals across US counties. It leverages geospatial data analysis and visualization techniques to map the maximum distance from the center of each county to the nearest hospital.
![Interactive Choropleth Map for Hospital Accessibility](https://github.com/mbabeykoon/HospitalsAccessibility/blob/main/preview%20.jpg)

## Libraries Used

- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **GeoPandas**: For handling geospatial data.
- **Plotly**: For creating interactive maps and visualizations.
- **Geopy**: For geodesic distance calculations.

## Dataset
The project uses two primary datasets:
- Hospitals Data: Contains information on hospital locations.
- US Counties Data: Contains information on US county centers.

Please download the datasets from the following links:
- Hospitals Data - https://hifld-geoplatform.opendata.arcgis.com/datasets/geoplatform::hospitals/about
- US Counties Data - https://simplemaps.com/data/us-counties

## Visualizations

- **Interactive Choropleth Map for Hospital Accessibility**: This map shows the maximum distance to the nearest hospital from the center of each county. Two layers, one for each year, allow users to switch between them to observe changes over time.
- **Hospital Locations Map**: Locations of hospitals are plotted as markers on the map to show the distribution of healthcare facilities across the country.

  





## Installation
To set up this project locally:
1. Install Dependencies:
- Install [Anaconda](https://www.anaconda.com/distribution/) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html).
- Clone the repository and navigate to the root directory.
  ```bash
  git clone https://github.com/mbabeykoon/HospitalsAccessibility.git
  cd Hospitals Accessibility #path to your folder
- Run the following command to create a conda environment from the `environment.yml` file:
  ```bash
  conda env create -f environment.yml
  conda activate env_name #change this to your environment name
 
2. Run Jupyter Notebooks:
- Navigate to the notebook directory.
- Open the notebooks in Jupyter Lab/Notebook.
