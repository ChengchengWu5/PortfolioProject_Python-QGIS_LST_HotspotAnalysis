### This is a project to calculate the Surface Land Temperature (LST) for a city in Python and then export the result to QGIS for mapping.
- To be more specific, the project creates a function to calculate the LST in Python for a region where the city is located (using Landsat-8 data) and saves the result as a Geotiff file.
- It then imports the file to QGIS to be reprojected and clipped by the city boundary to produce the LST GIS map for the city.


### Data sources and Python and QGIS versions:

- USGS's Landsat-8 LC09_L1TP_203023_20220716_20230407_02_T1 (Band 4, 5 and 10) data: available at https://earthexplorer.usgs.gov/)
- Birmingham boundary data: available at https://borders.ukdataservice.ac.uk/
- Python version: 3.11.6
- QGIS version: 3.32.1
