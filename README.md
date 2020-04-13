# Mapping_Earthquake
  
## Objective
  
Use d3.json() to get tectonic plate data and add the data using the L.geoJSON() layer.
  
Style the tectonic plate LineString data to stand out on the map.
  
Add the tectonic plate data as an overlay with the earthquake data.
  
Add a third map style to allow the user to select from three different maps.

  
## Resources Used
  
logic.js file from Earthquakes_past7days branch
  
GeoJSON/PB2002_boundaries.json from the available GIT repository
  
## Steps
  
Created a new branch Earthquake_Challenge and copied the same folder structure that we 've been using int he module. 
  
Updated the logic.js to make a d3json() call to the tectonic data and add the data layer ont he map using the L.geoJSON(). The color of the tectonic lines have been made brighter bby using styling options.
  
Tectonic layer has been added to the overlays and by default it is displayed on opening the index.html file in the browser.
  
Light map style has been added as a third map layer and base layer has been updated with the same. Streets has been made to be the default map.
  
## Screenshot

![alt text](https://github.com/29bharat/Mapping_Earthquakes/blob/master/Earthquake%20Challenge.PNG)


