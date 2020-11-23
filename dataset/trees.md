---
title: Trees
layout: page
description: Trees
---
Madrid is recognized a '[Tree City of the World 2019](https://www.madrid.es/portales/munimadrid/es/Inicio/Medio-ambiente/Parques-y-jardines/Madrid-reconocida-Ciudad-arborea-del-mundo-2019-por-la-FAO-y-la-Fundacion-Arbor-Day/?vgnextfmt=default&vgnextoid=3cdf84fec1732710VgnVCM2000001f4a900aRCRD&vgnextchannel=2ba279ed268fe410VgnVCM1000000b205a0aRCRD)' by FAO and the Arbor Day Foundation 

The municipality manages over 655,000 trees.

Information about each of these trees is available such as:
- height
- trunk diameter
- crown diameter
- species and genus
- geographic coordinates
- ...
(look the table down)

Trees produce so many benefits and this is important information to know.

This is one of the most important datasets for our challenge.

The dataset contains all the trees managed by the Municipality, excluding trees in parks and gardens, areas of property or areas of recent construction not yet received by the Municipality.
<br/><br/>
You can obtain the dataset in csv format with the coordinates in latitude (y) and longitude (x) in WGS84 (epsg:4326) by downloading the file
* [trees_madrid.zip](https://challenge.greemta.eu/data/green/trees_madrid.zip) (61Mb) (last update 15/11/2020).

The first row of the dataset contains the field with the names in spanish language.<br/>
The spatial reference system is WGS84 - epsg:4326.<br/>

Here a translation of the fields

| column 	| description 	|
|-	|-	|
| x	| longitude |
| y	| latitude  |
| NOMBRE_COMUN 	| common name of the tree type (in spanish) 	|
| MINTLOTE | identify code of the lot | 
| NOMBRE_LOTE | name of the lot |
| MINTDISTRITO | identify code of the district |
| NOMBRE_DISTRITO | name of the district | 
| MINTBARRIO | identify code of the neighborhood |
| NOMBRE_BARRIO | name of the neighborhood |
| MINTHIERARCHYPATH | classification path |
| MINTTIPOVIA | type of street |
| MINTNOMBREVIA | name of street |
| MINTNUMEROVIA | number on street |
| MINTNDP | identify code of area |
| MINTDIRECCIONAUX | identify code of direction |
| MINTCODPOSTAL | postal code |
| SERIALNUM | serial number | 
| MINTUNIDAD_GESTION |  code of management unit|
| NOMBRE_UGESTION | name of management unit |
| MINTSUPVERDE | identify code of green area |
| NOMBRE_SUPVERDE | name of green area |
| ESA_ESPECIE | species abbrevation |
| NOMBRE_ESPECIE | name of the specie (in spanish) | 
| SENESCENCIA| plant senescence | 
| EDAD_FENOL | phenological phase |
| TIPO_INTERFERENCIA | type of interference |
| ESTADO | status |
| ETIQUETA | label | 
| DIAMETRO_COPA | tree crown diameter|
| ALTURA | tree height |
| PERIMETRO | girth of trunk| 



You can also access the file from the ArcGIS Catalog via RestAPI from this end point [http://sigma.madrid.es/arcgismalla/rest/services/MTMOV](http://sigma.madrid.es/arcgismalla/rest/services/MTMOV)

The end-point [http://sigma.madrid.es/arcgismalla/rest/services/MTMOV/MPUAUA/FeatureServer](http://sigma.madrid.es/arcgismalla/rest/services/MTMOV/MPUAUA/FeatureServer) contains additional attributes


The data is open data and is licensed under these conditions<br/>

The general conditions allow the reuse of data for commercial and non-commercial purposes. You have to cite the origin of the data as Madrid City Council and not suggest the Madrid City Council supports your work

Please read the complete license [here](https://datos.madrid.es/portal/site/egob/menuitem.3efdb29b813ad8241e830cc2a8a409a0/?vgnextoid=108804d4aab90410VgnVCM100000171f5a0aRCRD&vgnextchannel=b4c412b9ace9f310VgnVCM100000171f5a0aRCRD&vgnextfmt=default) in particular the section relative to the *Condiciones generales para la reutilización*


