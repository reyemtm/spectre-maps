---
layout: map
title: Mapbox GL Map
category: maps
date: 2019-02-15 16:04:41
---
<script>
/*Blank Mapbox GL Map*/

var map = new mapboxgl.Map({
  container: 'map',
  hash: true,
  style: {
    "version": 8,
    "name": "blank",
    "sources": {
      "blank": {
        "type": "vector",
        "url": ""
      }
    },
    "layers": [{
      "id": "background",
      "type": "background",
      "paint": {
        "background-color": "#1d1f20"
      }
    }]
  },
  center: [-95.52, 39.94],
  zoom: 4,
  debug: 1
});
map.addControl(new mapboxgl.NavigationControl());
map.addControl(new mapboxgl.FullscreenControl());

/*End Blank Map*/
</script>
