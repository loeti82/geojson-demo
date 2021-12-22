# geojson-demo
Demo for geojson files

## How to use Overpass API
- goto https://overpass-turbo.eu/
- run 
 [out:json];
 area[name="Pfäffikon"]->.perimeter; 
 nwr(area.perimeter)[name="Hanggelerstrasse"];

 out geom;
 
- export as geojason
