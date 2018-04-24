---
layout: post
title: "Shiny and Leaflet in R"
date: 2017-12-19
---

I've published my first Shiny web application based on some reaesrch with Twitter data. The study uses text from Tweets to learn more about the vernacular geography of London's neighbourhoods, it's [available to view here](https://ltclasper.shinyapps.io/ldntweets/) by looking at which neighbourhood people think they are Tweeting from. It's a work in progress but it's quite easy to upload data from shapefiles, add some base mapping and start styling (although the colour palette needs some work as it's difficult to find 28 discrete colours), it's all done in R too. There are a few thousand Tweets in the point dataset so it is quite slow to render at the moment. The point clustering helps but does take away from the visual impact of seeing all of the Tweets on the screen at once. 

The next step is to tidy it up a bit and then add some more functionality like graphs and overlays. Also, some user interaction would be nice, as that is probably the whole point of a Shiny web application...
