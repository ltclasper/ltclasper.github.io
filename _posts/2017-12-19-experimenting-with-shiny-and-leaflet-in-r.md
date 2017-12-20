---
layout: post
title: "Experimenting with Shiny and Leaflet in R!"
date: 2017-12-19
---

I've published my first Shiny web application based on some Twitter research. The study uses text from [Tweets to learn more about the vernacular geography of London's neighbourhoods](https://ltclasper.shinyapps.io/ldntweets/) by looking at which neighbourhood people think they are Tweeting from. It's a work in progress but it's quite easy to upload data from shapefiles, add some base mapping and start styling (although colour palette needs some work!), it's all done in R too. There are a few thousand Tweets in the point dataset so it is quite slow at the moment. 

The next step is to tidy it up a bit and then add some more functionality like graphs and overlays. Also, some user interaction would be nice, as that is probably the whole point of a Shiny web application...
