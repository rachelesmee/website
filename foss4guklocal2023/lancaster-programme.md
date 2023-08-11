---
layout: program2023
---
## Talks

### Fraser House Hub : Local Sponsor Talk

> Fraser House Hub is a Lancaster "Tech Hub" 

### Lancaster Data Science Institute

> something something

###  Barry Rowlingson : Mapping a 1950s Circumnavigation with Open Source and Open Sources.

Covid lockdown. I started re-reading ""Earth My Friend"", the tale of Group Captain Peter Townsend's 1956-58 world circumnavigation by Land Rover. This time I read it with QGIS open, and mapped all the locations he mentioned. This involved consulting various online gazetteers, place references, old map collections and historical information. I've now released this data in a geopackage and am working on making it into cartographic products. This talk will show some of the challenges both in driving round the world in the 50s, and mapping data in the 2020s.

> I'm a research fellow in the Lancaster Medical School, working on statistical disease modelling and geospatial applications in health and medicine. 


###  Katherine McDonough : MapReader

MapReader is a groundbreaking interdisciplinary tool that emerged from a specific set of geospatial historical research questions. It was inspired by methods in biomedical imaging and geographic information science, which were adapted for use by historians. The success of the tool subsequently generated interest from plant phenotype researchers working with large image datasets, and so MapReader is an example of cross-pollination between the humanities and the sciences made possible by reproducible data science.

https://github.com/Living-with-machines/MapReader


> Katherine McDonough is Lecturer in Digital Humanities in the Department of History at Lancaster University and Senior Research Fellow at The Alan Turing Institute.

> Her digital work uses computational image, text, and spatial analysis to create new ways of doing historical research with large cultural heritage collections as data. With colleagues from Living with Machines, she co-developed the MapReader software library. She is the UK PI on Machines Reading Maps, a project that creates, curates, and analyses datasets of text on maps for research and discovery applications. In addition to her Turing projects she works on GEODE with colleagues in France.


###  Jonny Huck : Paper2GIS: a paper interface to your GIS database

I will introduce my Paper2GIS software (https://github.com/jonnyhuck/Paper2GIS), which was created in 2016 for a participatory GIS (PGIS) project on field course to a remote location in the Indian Himalaya. It has subsequently been deployed in both teaching and research settings, both for PGIS and other data collection applications.

Paper2GIS allows users to generate maps either using their own basemap design, or automatically using OpenStreetMap. Participants can then draw markup onto the map, which is scanned or photographed and given back to the software. The software uses computer vision techniques to isolate and extract the markup, georeference it, and provide it as either a Shapefile or GeoTiff dataset. Data can be extracted 'as drawn' (polygons representing the pen strokes) - or processed into a range of geometry types including filled polygons (using the outer ring of the markup geometry as a boundary), points (using either geometric centroid or representative point) or convex hulls. 

> Senior Lecturer in Geographical Information Science at the University of Manchester


###  Daniel Evans : From space to GeoTIFF - creating remote sensing data products

What does life look like at the start of the geospatial data trail? Remote sensing data products start as raw datasets that are inherently not geospatially aware. I will describe the process that SatVu applies to create useful thermal imaging products that can be used by geospatial software. This involves steps such as decoding and calibrating the raw data from the satellite, georeferencing the resulting images to create GeoTIFFs, computing all of the relevant metadata, and making the whole product available to customers via a STAC interface.

> Having started my career as an astronomer, I am now a geospatial software engineer. I have previously worked on natural hazard and climate change modelling problems, and am now working on creating thermal imaging products from space.


###  Ana Maria Pacheco Pascagaza : Connecting Google Colab and Earth Engine for Satellite Imagery Analysis and Vegetation Monitoring

In a rapid changing Earth and escalating environmental degradation, particularly in terms of vegetation, the need for rapid analysis of satellite imagery is urgent. This presentation unveils the seamless integration of Google Colab with Google Earth Engine, tapping into an extensive repository of remote sensing data. Demonstrating Colab's capabilities, we explore satellite image access, computation of essential vegetation indices, and creation of spatial visualisations. I will present an overview on how generate time series analysis, machine learning, and a practical example of blending diverse data sources to produce various remote-sensing-based maps (e.g., land cover, biomass). 

> Ana María is a Postdoctoral Researcher in the School of Environment, Education and Development at The University of Manchester. She is a specialist in Earth Observation (EO) for monitoring forests structure, and disturbances using a combination of Synthetic Aperture Radar (SAR) data, Optical, LiDAR and field data. Ana Maria is working on the NERC funded project UKFDRS https://ukfdrs.com to generating a national static fuel map essential to understand national fire regimes and dynamics.


###  Tom Nicholls : Bringing Long Running Geostatistical Calculations to Public Health Professionals in the Developing World

Epidemiologists at CHICAS (Centre for Health Informatics, Computing, and Statistics) at Lancaster University have developed code to model disease spread of an important group of Neglected Tropical Diseases. The algorithms are typically written as very long-running ""R"" scripts.  We present an architecture and prototype implementation of an asynchronous, scalable web-based platform that will be used by public health control professionals in the host countries to analyse disease data and design surveys using model-based geostatistics.

Our eventual aim is to make the design sufficiently flexible so that the software could potentially cope with any type of calculation and input/output combination, including staged calculations.


> Tom started his career with a PhD in Optical Physics from Imperial College (some time in the dark ages), and since then has worked in a variety of software engineering jobs in industry.  He returned to academia in 2019 and joined the Centre for Health Informatics,  Computing and Statistics at Lancaster University in May 2023.



