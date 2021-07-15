---
layout: post
title: "Vernacular Placenames in OpenStreetMap"
date: 2021-07-15
---

   
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<link rel="stylesheet" href="https://unpkg.com/leaflet@1.6.0/dist/leaflet.css"
   integrity="sha512-xwE/Az9zrjBIphAcBb3F6JVqxf46+CDLwfLMHloNu6KEQCAWi6HcDUbeOfBIptF7tcCzusKFjFw2yuvEpDL9wQ=="
   crossorigin=""/>
   <style>
body{
padding: 0;
margin: 0;
}
html, body, #map {
height: 100%;
}
</style>
</head>
<body>
 
   
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

</body>
</html>

	
	
