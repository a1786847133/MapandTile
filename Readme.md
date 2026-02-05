# Lab 4 – Map Design & Tile Generation

## Web map
https://a1786847133.github.io/MapandTile/

## What this is
For this lab I generated four raster tilesets in QGIS (QMetaTiles) and displayed them in a single Mapbox GL JS web map.  
My theme is **public transit** in the Seattle–Eastside area, using **King County Metro bus stops**.

## Study area
Seattle + Eastside core area in King County (around Lake Washington).

## Zoom levels
All tilesets were exported around **z 10–13**.

## Tilesets
- **tileset_1:** local basemap
- **tileset_2:** metro stops (thematic overlay)
- **tileset_3:** basemap + stops (composite)
- **tileset_4:** transit-themed basemap (highlight the road in the city)

## Screenshots

![tileset_1](img/tileset_1.png)
![tileset_2](img/tileset_2.png)
![tileset_3](img/tileset_3.png)
![tileset_4](img/tileset_4.png)

## Data source
King County Metro Stops (King County Open Data):  
https://gis-kingcounty.opendata.arcgis.com/datasets/kingcounty::king-county-metro-stops/explore?location=47.535437%2C-122.122049%2C11
