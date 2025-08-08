---
title: Session 6
draft: false
tags:
  - session
  - DM
  - secret
publish: false
---
 ```encounter
name: Fight with the lowminers
players:
  - Evik
  - Jonik
  - Archaida
creatures:
  - "4": Tough
```


```leaflet  
id: MapCalcExample ### Must be unique with no spaces  
image: [[Pasted image 20250808174721.jpg]] ### Link to the map image file. Do not add a ! in front of the image  
bounds: [[0,0], [773, 1000]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
height: 800px ### Size of the leaflet embed in px on your screen  
width: 1000px ### Size of the leaflet embed in your note  
lat: 380 ### To center the map, make this half of the map height.  
long: 500 ### To center the map, make this half of the map width.  
minZoom: -1 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: 1 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -0.1 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
unit: mi ### The value displayed when measuring so you know what type of unit is being measure.  
scale: 0.002 ### Real units/px (resolution) of your map  
recenter: false  
darkmode: false ### marker
```
