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
1. Load the GeoJSON File
2. Convert GeoJSON to Earth Engine Geometry
3. Load Landsat Image Collection
4. Clip the First Image to the AOI
5. Display the Clipped Image
6. Calculate NDWI
7. Calculate Monthly Mean NDWI
8. Calculate Surface Water Extent
9. Generate Time Series Data for Visualization
10. Convert Feature Collection to List of Dictionaries and Extract Dates and NDWI Values
11. Plot Monthly Mean NDWI
12. Calculate Surface Water Body Extent for Each Monthly NDWI Image
13. Plot Surface Water Body Extent Over Time
14. Normalize and Plot 2D Column Chart for Surface Water Body Extent Over Time
15. Visualize Monthly Mean NDWI Images

