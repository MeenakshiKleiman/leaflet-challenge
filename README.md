## Background
The USGS provided earthquake data in a number of different formats, which were updated every 5 minutes. Participants were asked to visit the USGS GeoJSON Feed page and choose a dataset to visualize.  When they clicked a dataset (such as "All Earthquakes from the Past 7 Days"), they were given a JSON representation of that data. They then used the URL of this JSON to pull in the data for the visualization.

### Part 1: Create the Earthquake Visualization


-Using Leaflet to create a map that plotted all the earthquakes from their dataset based on their longitude and latitude.
-Ensuring that their data markers reflected the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes appeared larger, and earthquakes with greater depth appeared darker in color.
-Including popups that provided additional information about the earthquake when its associated marker was clicked.
-Creating a legend that provided context for their map data.


### Part 2: Gather and Plot More Data

-plotted a second dataset on their map to illustrate the relationship between tectonic plates and seismic activity. We needed to pull in this dataset and visualize it alongside their original data. 
-Plotted the tectonic plates dataset on the map in addition to the earthquakes.
-Added other base maps to choose from (Topographic).
-Put each dataset into separate overlays that could be turned on and off independently.
-Added layer controls to their map.

![Basic Map with Tectonic plates   earthquakes ](https://github.com/user-attachments/assets/e275969e-a381-43d9-93c1-2a043f98c51d)
![Advanced Map_Topographical ](https://github.com/user-attachments/assets/8ce137ab-275d-4038-bce8-b0d3b0ac25d8)
