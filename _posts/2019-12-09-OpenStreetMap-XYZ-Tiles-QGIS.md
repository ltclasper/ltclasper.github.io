---
layout: post
title: "Using OpenStreetMap XYZ Tiles in QGIS"
date: 2019-12-09
---

Adding a basemap into QGIS is essential to give you some context when doing spatial analysis or for using as a backdrop in map production. [OpenStreetMap](https://www.openstreetmap.org/#map=6/54.910/-3.432) is an excellent choice for base mapping It is built and maintained by a community of mappers, is open and has worldwide coverage. One of the things I like about OpenStreetMap is the fact that is driven by local community knowledge, so you find colloquial names for geographic features that might not exist on mapping from national mapping agencies or commercial mapping services. It is not-for-profit so has no commercial interests, is produced by enthusiasm mappers (like me!), anyone can take part and it is also vital for humanitarian aid, often in places with little other available mapping.

It is very straightforward to add an OpenStreetMap XYZ tile layer into QGIS, plus there is a massive choice of map styles to go for, depending on map usage and what features within the OpenStreetMap you wanted to highlight. Firstly, go to the [OpenStreetMap Wiki tile page](https://wiki.openstreetmap.org/wiki/Tiles) and pick the required basemap from the list. You will need to copy the tiles URL, then go to QGIS Browser. From the QGIs Browser, right click on the XYZ Tiles option and click New Connection. Now paste your URL into the box and give the connect a name (e.g. OpenCycleMap etc.), you'll just need to delete all of the "$" symbols from the URL and that is it! You can now double click on the connection, which will be listed under XYZ Tiles in the QGIS Browser and it will add the OpenStreetMap basemap to your Layers.
