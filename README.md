# Mapping_Earthquakes

# Objectives
The goals of this challenge :

* Use d3.json() to get tectonic plate data and add the data   using the L.geoJSON() layer.
* Style the tectonic plate LineString data to stand out on the map.
* Add the tectonic plate data as an overlay with the earthquake data.
* Add a third map style to allow the user to select from three different maps.
# Resources

* Software: Visual Studio Code 1.43.0, HTML, CSS, JavaScript (ES6), Mapbox
* Libraries: D3.js, Leaflet.js
* Data Source: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson , https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json

# Summary
![](image/screenshot.PNG)

This map has 3 differnt layers for viewers to swithing their prefered map style. When pointing the bubble circle, it indicates the level of earthquake magnitude by color and the detail metric is displayed on the right bottom conor. Redlines are the tectionic plates layer. Base on the buble locations, the high magnitude earthquake mostly is taken place on the tectionic plates. 
