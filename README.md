# San Francisco Housing Market Analysis

This project analyzes the housing market in San Francisco using housing sales data from 2010 to 2016. The analysis consists of several visualizations to understand the trends and relationships in the data.

## Data

The dataset used for this analysis is `sfo_neighborhoods_census_data.csv`, which includes information about housing units, sale price per square foot, and gross rent for various San Francisco neighborhoods. The `neighborhoods_coordinates.csv` file contains latitude and longitude coordinates for each neighborhood, which are used for geospatial visualizations.

## Analysis

The analysis is divided into several sections:

1. Calculate and plot the housing units per year
2. Calculate and plot the average sale prices per square foot
3. Compare the average sale prices by neighborhood
4. Build an interactive neighborhood map

### 1. Housing Units per Year

This section calculates the average number of housing units per year and visualizes the results using a bar chart.

### 2. Average Sale Prices per Square Foot

This section calculates the average sale price per square foot by year, filters out the housing_units column, and visualizes the results using an interactive line plot.

### 3. Average Sale Prices by Neighborhood

In this section, the data is grouped by year and neighborhood, and the mean values are calculated. An interactive line plot is created using `hvplot`, allowing users to select a neighborhood from a dropdown menu and view the average price per square foot for the selected neighborhood.

### 4. Interactive Neighborhood Map

This section combines the neighborhood location data with the average prices to create an interactive map using `hvplot` and `GeoViews`. The map displays points for each neighborhood, with the size of the points representing the sale price per square foot and the color representing the gross rent.

## Dependencies

- Python
- Pandas
- hvPlot
- GeoViews
- Jupyter Notebook

## Usage

To run the analysis, open the Jupyter Notebook `san_francisco_housing_analysis.ipynb` and execute the cells in order.
