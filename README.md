# Mapping Earthqaukes

## Overview of Project
### Purpose of Project
In this project, I demonstrated my proficiency with various JavaScript, Leaflet.js, and geoJSON features including: adding multiple maps and a base layer, mapping GeoJSON LineStrings and Points, adding data to a Leaflet map, styling data on a Leaflet map, adding data as overlay, adding data to a LayerGroup class. 

### Background of Project
Disater Reporting network, a fictional nonprofit company, provides data driven storytelling on disasters around the world. As the Data Visualization Specialist, I built an insightful, interactive website about earthquakes. My role was to support website and mobile application development by using the latest GeoJSON data from the U.S. Geological Survey website, traverse and retrieve earthquake data using JavaScript and the D3 and leaflet libraries, and plot the data on a Mapbox map through an API request. 


---
## The Map 
The map includes the magnitude and location of the earthquake shown dynamically through a popup marker. The diameter of the marker for each earthquake reflects the magnitude of the earthquake in size and color. Earthquakes with higher magnitudes are larger and darker with a legend providing context for the map. Additionally, to illustrate the relationship between the location and frequency of seismic activity and tectonic plates, fault lines have been added to the map. 


### Map Styles 
The user can dynamically select from three different map styles: Streets [default], Satellite, or Dark. 

**Mapbox Maps IDs**

USED ON THIS MAP 
* Mapbox Streets: mapbox/streets-v11
* Mapbox Satellite: mapbox/satellite-v9
* Mapbox Dark: mapbox/dark-v10

COULD BE ADDED 
* Mapbox Light: mapbox/light-v10
* Mapbox Navigation Day: mapbox/navigation-day-v1
* Navigation Night: mapbox/navigation-night-v1
* Mapbox Outdoors: mapbox/outdoors-v11
 
 
 ### geoJSON() Layers
The user can dynamically add and remove earthquake data layers. 
LAYERS 
* Earthquakes: markers for each earthquake reflecting the magnitude of the earthquake in size and color with a popup marker describing the magnitude and location 
* Tectonic Plates: lines representing tectonic plates
* Major Earthquakes: markers for earthquake with **magnitudes of 5 and greater** with a popup marker describing the magnitude and location



