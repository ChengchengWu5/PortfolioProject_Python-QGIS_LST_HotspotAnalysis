### This is a project to calculate the Surface Land Temperature (LST), produce the LST map, and perform the Hopspot Analysis on LST in Python and QGIS.
- To be more specific, the project creates a function to calculate LST in Python for a region where the city (Birmingham, UK in this case) is located using the Landsat-8 data (band 4, 5, and 10) and saves the result as a Geotiff file. 
- It then imports the file to QGIS to be reprojected to EPSG:27700 (British National Grid) and clipped by Birmingham boundary to produce the LST map for the city.
- After that, it converts the raster pixels of the file within the city boundary to points (shapefile) in QGIS, intersects the
points by ward boundaries within the city and saves the intersected points as a csv file before joining with the ward boundary data.
- The processed dataset ('Birmingham_LST_result_by_ward.shp') is then imported to Python for the Hotspot Analysis.

### Data sources and Python and QGIS versions:

- USGS's Landsat-8 LC09_L1TP_203023_20220716_20230407_02_T1 (Band 4, 5 and 10) data: available at https://earthexplorer.usgs.gov/)
- Birmingham city and ward boundary data: available at https://borders.ukdataservice.ac.uk/
- Python version: 3.11.6
- QGIS version: 3.32.1
