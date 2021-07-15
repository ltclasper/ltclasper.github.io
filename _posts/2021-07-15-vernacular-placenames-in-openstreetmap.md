---
layout: post
title: "Vernacular Placenames in OpenStreetMap"
date: 2021-07-15
---

<html>

<body>

 <div id="my-custom-map" style="width: 600px; height: 400px"></div>


  <script>


  var map = L.map('map').setView([42.35, -71.08], 13);


  L.tileLayer('http://tiles.mapc.org/basemap/{z}/{x}/{y}.png',
    {
      attribution: 'Tiles by <a href="http://mapc.org">MAPC</a>, Data by <a href="http://mass.gov/mgis">MassGIS</a>',
      maxZoom: 17,
      minZoom: 9
    }).addTo(map);

  </script>
</body>
</html>
	
