# Mapathon HOT OSM - What We Mapped ! #
----------


Example 
---------------
Idjwi, Democratic Republic of the Congo.

![alt tag](https://github.com/tgrippa/Mapathon_HOT_OSM_WhatWeMapped/blob/master/Example/Mapathon2016accomplishment.gif?raw=true)

On Saturday, the 16th of April 2016, the first national-level mapathon took place in Belgium. Nearly 200 peoples, in 7 universities, mapped 50.000 buildings in a day.


Abstract
--------
This repository provide a "Jupyter Notebook" which facilitate the creation of animated GIF or video, illustrating what it have been mapped during a mapathon event.


Procedure
--------
The user should create a shapefile (polygon) corresponding to the area of interest which has been mapped during the mapathon. Then, the OpenStreetMap data will be downloaded automatically and imported in Postgresql. Shapefiles are produced for both highways, and residential area/buildings features. The user should then use the TimeManager plugin of Qgis to create frames highlighting the modifications which have been made. The .gif and .mp4 animated illustrations are then created in the notebook. Some basic statistics are computed in the notebook (number of mappers, number of new features, etc..).


Material - Dependencies
--------
To be used as it is, some programs/softwares need to be installed. 

- [Qgis](https://www.qgis.org/fr/site/forusers/download.html).
- [Postgresql](https://www.postgresql.org/).
- [Qgis TimeManager Plugin](https://plugins.qgis.org/plugins/timemanager/). More ressources [here](http://planet.qgis.org/planet/tag/time%20manager/), [here](https://anitagraser.com/projects/time-manager/), [here](https://www.youtube.com/watch?v=GkfoFFy-bao), [or here](https://github.com/anitagraser/TimeManager).
- [osm2pgsql](http://wiki.openstreetmap.org/wiki/Osm2pgsql)


Licence
--------
This notebook is provided under the [CC-BY 4.0 Licence](https://creativecommons.org/licenses/by/4.0/), so feel free to use it for any purpose. 

<p align="center"> <img src="http://creativecommons.org.nz/wp-content/uploads/2012/05/by.png" style="width: 150px;"></p>
