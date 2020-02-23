# Mapping_Earthquakes

## Project Overview 
Goal is to use JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. I used the Leaflet library to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data.

This module has taught me the following:

1. Create a branch from the master branch on GitHub.
2. Add, commit, and push data to a GitHub branch.
3. Merge a branch with the master branch on GitHub.
4. Retrieve data from a GeoJSON file.
5. Make API requests to a server to host geographical maps.
6. Populate geographical maps with GeoJSON data using JavaScript and the Data-Driven Documents (D3) library.
7. Add multiple map layers to geographical maps using Leaflet control plugins to add user interface controls.
8. Use JavaScript ES6 functions to add GeoJSON data, features, and interactivity to maps.
9. Render maps on a local server.

        
## Branches/docs

1. Simple_Leaflet_Map (also committed to the Master Branch)
2. Mapping_Single_Points
3. Mapping_Multiple_Points
4. Mapping_Lines
5. Mapping_GeoJSON_Polygons
6. Mapping_GeoJSON_Points
7. Mapping_GeoJSON_Linestrings
8. Earthquakes_past7days

9. Earthquake_Challenge (committed in the Master Branch)
10. gitignore : hide AI KEY (master)
11. majorAirport.json (master)
12. torontoNeighborhoods.json (master)
13. torontoRoutes.json (master)

## Summary

The code logic. js pulls the data from the JSON or another file, and organizes and utilizes the maps depending on module chapter or assignement. The style.css and index.html deplays the information shows the viewer a nice visualization of the data. The index. html code calls the style. css, d3, logics. js, in order to show the information. 

# Module 13 Challenge 

## Challenge overview

1. Create a new folder on your Mapping_Earthquakes repository and name it “Earthquake_Challenge.”
2. Copy the folders and files from your Earthquakes_past7days branch and add them to the Earthquake_Challenge folder. 
3. Use the GeoJSON/PB2002_boundaries.json data from the GitHub repository (Links to an external site.) for the tectonic plate data. You’ll need to log into GitHub to access the GeoJSON data.
4. Place the d3.json() call with the L.geoJSON() layer for the tectonic plate data at the end of your code from your Earthquakes_past7days branch.
5. Style the lines with a strong, bright color so the lines show up on the satellite map and are not too light to be seen on the lighter maps.
6. Create the tectonic plate layer for the map.
7. Add the tectonic plate layer to the overlays so that they show up in the tile layer, as shown in the image below.
8. Add the tectonic plate and earthquake data to the map for any map style choice.
9. Edit the base layer so that it holds all three maps.
10. Make the streets map the default map.s.


## Summary 
***Please note the code/information can be found in logics.js and the html formatting can be found in index.html

I made an API call to the tectonic plate data using d3.json(), and then added the data as an overlay to the map using the L.geoJSON() layer. In addition to the streets and satelliteStreets maps, I added a third map: Light. All map styles were added to the base layer so that they show up on the map to allow the user to change which layers are visible.
