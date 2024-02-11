### This is a project to calculate the Surface Urban Heat Island (SUHI) in a city (Birmingham, UK is the case study) in Python and then overlay the SUHI map on the forest/woodland map of the city created in QGIS. The following are the steps involved in the process:
#### Create the function to calculate Land Surface Temperature (LST) and save the result as a Geotiff file 
#### Import the file to QGIS to be reprojected to EPSG: 27700 (British National Grid) and then clip it by Birmingham boundary
#### Create the map of the SUHI based on the LST and then overlay the map on forest/woodland map of the city created in QGIS


### Data sources and Python and QGIS versions:

#### USGS's Landsat-8 data LC09_L1TP_203023_20220716_20230407_02_T1 (Band 4, 5 and 10): available at https://earthexplorer.usgs.gov/)
#### Forestry Commission's National Forest Inventory England 2021 data: availalbe at https://data-forestry.opendata.arcgis.com/datasets/a73551a581074e5fa192418c65b43d55_0/about
#### Python version: 3.11.6
#### QGIS version: 3.32.1
