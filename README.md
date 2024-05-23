# Water-Body-Extent-Analysis-Using-Landsat-Imagery
This project analyzes the extent of water bodies using Landsat 8 imagery and the Normalized Difference Water Index (NDWI). The script processes the imagery, calculates monthly mean NDWI, and visualizes the results through various plots.
# Requirements
Python 3.9
Google Earth Engine (GEE) Python API
Geemap
Matplotlib
JSON
# Setup
Prerequisites
Ensure you have Python 3.9 installed. You can download it from the official Python website.
Install Required Libraries
# Google Earth Engine Authentication
You need to authenticate your Google Earth Engine (GEE) account. Run the following command to initialize and authenticate:
# steps to calculate surface water body extents for over time periods
Load the GeoJSON File
Convert GeoJSON to Earth Engine Geometry
Load Landsat Image Collection
Clip the First Image to the AOI
Display the Clipped Image
Calculate NDWI
Calculate Monthly Mean NDWI
Calculate Surface Water Extent
Generate Time Series Data for Visualization
Convert Feature Collection to List of Dictionaries and Extract Dates and NDWI Values
Plot Monthly Mean NDWI
Calculate Surface Water Body Extent for Each Monthly NDWI Image
Plot Surface Water Body Extent Over Time
Normalize and Plot 2D Column Chart for Surface Water Body Extent Over Time
Visualize Monthly Mean NDWI Images

