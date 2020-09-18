---
title: "Map_with_Leaflet"
author: "Apoorv"
date: "19/09/2020"
output: 
  html_document: 
    keep_md: true 
---



####Map created in R Studio using leaflet and annotations with R markdown
#####1. My city



```r
library(leaflet)
my_map <- leaflet() %>% addTiles() 
my_map <- my_map %>% addMarkers(lat=26.8467, lng= 80.9462, popup="Lucknow city, INDIA")
my_map
```

<!--html_preserve--><div id="htmlwidget-88c0d7c1bacddacb6752" style="width:672px;height:480px;" class="leaflet html-widget"></div>
<script type="application/json" data-for="htmlwidget-88c0d7c1bacddacb6752">{"x":{"options":{"crs":{"crsClass":"L.CRS.EPSG3857","code":null,"proj4def":null,"projectedBounds":null,"options":{}}},"calls":[{"method":"addTiles","args":["//{s}.tile.openstreetmap.org/{z}/{x}/{y}.png",null,null,{"minZoom":0,"maxZoom":18,"tileSize":256,"subdomains":"abc","errorTileUrl":"","tms":false,"noWrap":false,"zoomOffset":0,"zoomReverse":false,"opacity":1,"zIndex":1,"detectRetina":false,"attribution":"&copy; <a href=\"http://openstreetmap.org\">OpenStreetMap<\/a> contributors, <a href=\"http://creativecommons.org/licenses/by-sa/2.0/\">CC-BY-SA<\/a>"}]},{"method":"addMarkers","args":[26.8467,80.9462,null,null,null,{"interactive":true,"draggable":false,"keyboard":true,"title":"","alt":"","zIndexOffset":0,"opacity":1,"riseOnHover":false,"riseOffset":250},"Lucknow city, INDIA",null,null,null,null,{"interactive":false,"permanent":false,"direction":"auto","opacity":1,"offset":[0,0],"textsize":"10px","textOnly":false,"className":"","sticky":true},null]}],"limits":{"lat":[26.8467,26.8467],"lng":[80.9462,80.9462]}},"evals":[],"jsHooks":[]}</script><!--/html_preserve-->

