---
layout: post
title: "Vernacular Placenames in OpenStreetMap"
date: 2021-07-15
---

<script src="https://unpkg.com/leaflet@1.6.0/dist/leaflet.js"
   integrity="sha512-gZwIG9x3wUXg2hdXF6+rVkLF/0Vi9U8D2Ntg4Ga5I5BZpVkVxlJWbSQtXPSiUTtC0TjtGOmxa1AJPuV0CPthew=="
   crossorigin=""></script>
<div id="map" style="width: 100%; height: 100%"></div>
<script>
var map = L.map('map',
{center: [52.340442, -2.280549],
zoom: 12
});
L.tileLayer('http://{s}.tile.osm.org/{z}/{x}/{y}.png').addTo(map);

</script>
