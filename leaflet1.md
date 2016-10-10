---
title: "Data Product - Peer Graded Assessment"
author: "Herminio Vazquez"
date: "10/10/2016"
output: html_document
---

This document contains the submission for the first peer graded assignment in the Coursera course of Building Data Products from John Hopkins University.


```r
library(leaflet)
```

Next we print the date as requested in the rubric of this assignment

```r
Sys.Date()
```

```
## [1] "2016-10-10"
```

Finally we print the coordinates of the location where I live


```r
# Valencia, Spain
my_map <- leaflet() %>% addTiles() %>% addMarkers(lat=39.4697500, lng=-0.3773900, popup="Herminio's City")
my_map
```

<!--html_preserve--><div id="htmlwidget-1225" style="width:504px;height:504px;" class="leaflet"></div>
<script type="application/json" data-for="htmlwidget-1225">{"x":{"calls":[{"method":"addTiles","args":["http://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png",null,null,{"minZoom":0,"maxZoom":18,"maxNativeZoom":null,"tileSize":256,"subdomains":"abc","errorTileUrl":"","tms":false,"continuousWorld":false,"noWrap":false,"zoomOffset":0,"zoomReverse":false,"opacity":1,"zIndex":null,"unloadInvisibleTiles":null,"updateWhenIdle":null,"detectRetina":false,"reuseTiles":false,"attribution":"&copy; <a href=\"http://openstreetmap.org\">OpenStreetMap</a> contributors, <a href=\"http://creativecommons.org/licenses/by-sa/2.0/\">CC-BY-SA</a>"}]},{"method":"addMarkers","args":[39.46975,-0.37739,null,null,null,{"clickable":true,"draggable":false,"keyboard":true,"title":"","alt":"","zIndexOffset":0,"opacity":1,"riseOnHover":false,"riseOffset":250},"Herminio's City",null,null]}],"limits":{"lat":[39.46975,39.46975],"lng":[-0.37739,-0.37739]}},"evals":[]}</script><!--/html_preserve-->
