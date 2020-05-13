# online.nasa.satellite.tracker.3d 
Online 3d web to track nasa satellites and astros. Alternative for J-Track 3D from NASA

## Web: https://sbesada.github.io/online.nasa.satellite.tracker.3d/

## Reference
- Data for the satellite tracker: https://sscweb.sci.gsfc.nasa.gov/
- This page is a 3D alternative for https://science.nasa.gov/realtime/jtrack/3d/JTrack3D.html
- 3D library - https://cesium.com/

## Satellites & Astros Data
This web is populated on various schedules depending on mission, ranging from weekly to yearly and include predictive and definitive orbits

## Accuracy
 - Locations are stored in 32bit floats with a precision of a few meters near the Earth and a few hundred km at Pluto
 - The longitude, latitude and altitude hava small precision error due to the coordinate conversion between NASA coordinate system (GEO) and map coordinate system WGS84 (https://es.wikipedia.org/wiki/WGS84). I am using an Octave function in order to transform de coordinate system from GEO to WSG84 (https://www.gnu.org/software/octave/) and this project (https://sourceforge.net/projects/irbem/ - Los Alamos National Laboratory)
 - Ground Stations have a few hundred meters error
 
## ISS Tracker
 - ISS: https://en.wikipedia.org/wiki/International_Space_Station
 - You can compare the accuracy with https://www.esa.int/Science_Exploration/Human_and_Robotic_Exploration/International_Space_Station/Where_is_the_International_Space_Station

## 3D Earth 
 - It is possible to see the Earth near real time. (https://wiki.earthdata.nasa.gov/display/GIBS/)
 - It is possible to see the Earth at night.
 
## 3D Moon
  - The Moon is rendered in 3d with images from NASA (https://svs.gsfc.nasa.gov/4720)

## Real time data
 - It is possible to track satellites and astros in real time. The position is updated each minute. 
 
 ## Mobile
 This web is mobile friendly
 
 ## How to use the web
 Choose a satellite or astro and do click on the satellite or double click on the Moon to see the details
 
 ## Download
 You can download info about satellites in xlsx format
 
 ## Donation
 If you think that my work deserves a donation, you can do it: https://sbesada.github.io/
 
