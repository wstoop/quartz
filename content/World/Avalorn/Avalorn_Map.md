---
title: Avalorn_MAP
draft: true
tags:
  - example-tag
---
```leaflet  
id: Avalorn_1  

### Lock pins so they can't be moved  
lock: true  

### If true, view of map will recenter as you zoom out.  
recenter: true  

### If true, disables mouse scroll for zomming in and out of a map. Button controls still work.  
noScrollZoom: false  

image: Avalorn_map.jpg

### Map Pixel Height x 1 / (Pixels between Bar Scale / 100)  
### Map Pixel Width x 1 / (Pixels between Bar Scale / 100)  
### Note that this formula requires adjustments depending on your map. The idea is to determine the number of units between your bar scale. We divide by 100 here because my bar scale measures in 100 units. If your maps scale bar measures in units of 50 them you should divide by 50 instead. The idea is to calculate how many pixels are equal to 1 unit.  
### Bounds is entered as [Height, Width]  
bounds: [[0,0], [313.83, 313.83]]  
height: 900px  
width: 95%  
### This sets where the map starts by default. Set it to the middle (half) of your bounds.  
lat: 156.92  
long: 156.92  
### 0 is no zoom. Negative zoom steps away from the map. Positive zoom steps towards the map.  
minZoom: 0  
### Max zoom is 18.  
maxZoom: 18  
### Hover mouse over the Reset Zoom icon to see your current zoom level.  
defaultZoom: 1.5  
### How far it zooms in or out with each step. Can be in decimals.  
zoomDelta: 0.5  
### This is a string so can be any text. Change it to match your maps measurement scale.  
unit: Kilometers  
scale: 6.525826084  
darkMode: false

```








