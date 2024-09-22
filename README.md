# Geospatial interactive Visualization + data analysis for senior clubs in Poland

The project demonstrates an interactive chorolpeth map and a heatmap created with Python and Jupyter Notebook. The map visualizes available number of places in clubs for seniors in each commune in Poland per 1000 inhabitants.


# Features of geospatial viz

- Interactive Map and a heatmap: both Visualize the number of places in senior clubs per 1,000 inhabitants for each commune.
- Custom Styling: Unique styling for both communes and voivodeships, with tooltips and a dynamic color scale based on senior club availability.
- Data Preparation: Data cleaning and merging of multiple datasets, including population data and geospatial boundaries.
- Libraries Used: Folium, Pandas, GeoPandas, and Branca.

# Features of data analysis
- Data Preparation: Data cleaning and merging 
- Performing EDA by grouping smaller administrative units (communes) into bigger ones (voivodships)
- Performing EDA by grouping communes by the type (urban, rural or mixed) and exploring the differences between the groups by performing Kruskal-Wallis test.
- Correlation between population size and offered number of places in the communes.
Libraries Used: Pandas, Matplotlib, Seaborn, SciPy.

# Files in repository

- Jupyter Notebook for geospatial vizualisations (.ipynb)
- Jupyter Notebook for data analysis (.ipynb)
- interactive map (HTML)
- heatmap (HTML)
- CSV files (dataset + 2 files with variable labels)
- GeoJSON File

# Summary

The notebooks contains a detailed description of the data preparation steps, merging the datasets and the visualization and analysis process. 