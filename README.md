# Boatiful Berlin Demo

An Android App thought for those who like paddle on the water. The Boatiful Demo Berlin App is a PoC and provides a Berlin offline Map
and offline Routing on the River and Canal Network of the City. Beyond the fastest route, time and distance, speed and accuracy bearing via gps will be displayed.




# Quick Start
Simply download and install the "Boatiful Demo Berlin.apk" on your android device.

<p align="center">
  <img src="http://davmol.de/git_hub_data/Screenshot_20190120-130104.jpg" width="350">
  <img src="http://davmol.de/git_hub_data/Screenshot_20190120-130232.jpg" width="350">
</p>

 
# Background Story

# Map
The Basemap uses the .map format used with the Mapsforge VTM Render Engine.
The Basemap is created with Osmosis & Mapsforge-Writer Plugin. For the visualization is a custom VTM Theme is applied with costum POIs for waterways. 

# Routing
Custom routing profile on water via the open source graphhopper core api which can be found here:

https://github.com/graphhopper/graphhopper

Graphhopper is a routing enginge that works on OpenStreetMap data. The custom routing profile uses following waytags:
<waterway="river"/>
<waterway="canal"/>
<boat="yes"/>


