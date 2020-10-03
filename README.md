# manumaps
An open, web-based google maps alternative

## Goals

The goal of this project is to make a google map alternative that
  - Is web based and uses many web technologies (PWA, SW, webgl)
  - Is open source and use open source components
  - Can run on a laptop (<16go RAM, <1to ssd)
  - Is focused on time vs cost compromise

## Technologies

This project will use the following technologies :
  - [valhalla](https://github.com/valhalla/valhalla) routing engine
  - [photon](https://github.com/komoot/photon) geocoder
  - [openstreetmap](https://www.openstreetmap.org/) data
  - [openmaptiles](https://openmaptiles.org/) vector tiles
  - [mapbox-gl-js](https://github.com/mapbox/mapbox-gl-js) client map

## Features
  
  - Offline-first responsive PWA
  - Cost-based multimodal routing
  - Web-based navigation (limited for now to foreground usage)
  - Online routing, but offline navigation
  
## Demo

When ready, this project will replace the existing app on [www.manumaps.com](www.manumaps.com).
