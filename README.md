### This is a project to calculate the Surface Land Temperature (LST) for a city in Python and then export to QGIS for mapping. The following are the steps involved in the process:
- Create a function to calculate the LST in Python for a region where the city (Birmingham, UK in this case) is located and save the result as a Geotiff file
- Import the file to QGIS to be reprojected to EPSG:27700 (British National Grid) and then clip it by Birmingham boundary


### Data sources and Python and QGIS versions:

- USGS's Landsat-8 LC09_L1TP_203023_20220716_20230407_02_T1 (Band 4, 5 and 10) data: available at https://earthexplorer.usgs.gov/)
- Birmingham boundary data: available at https://borders.ukdataservice.ac.uk/
- Python version: 3.11.6
- QGIS version: 3.32.1
