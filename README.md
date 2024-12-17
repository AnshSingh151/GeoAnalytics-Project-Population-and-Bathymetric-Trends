# GeoAnalytics-Project-Population-and-Bathymetric-Trends
A QGIS-based project analyzing population near roads, marina proximity to large settlements, and depth changes between 2022 and 2023 bathymetric surveys. Includes spatial analysis, raster calculations, and automated data extraction.


Task 1: Spatial Analysis

1. Population Near Roads:

Buffer Highways and State Roads by 500m.

Identify and sum populations from settlements within the buffer.


2. Marinas Near Large Settlements:

Select settlements with populations >10,000.

Buffer them by 20km and find marinas within this area.


3. Distance Along RPL.shp:

Use the KP Find plugin to calculate distances between cities along RPL.shp.

Reverse RPL.shp direction and verify with labels.


---

Task 2: Depth Difference Map

1. Difference Map:

Subtract 2022 raster from 2023 raster.

Visualize differences with a blue-white-red color ramp.


2. Point Attributes:

Automate x/y coordinates (3 decimals), depth values (2 decimals), and differences.

Assign IDs as ID_2023_00X (west-to-east).


3. Map Output:

Include difference raster, labeled points, and cartographic elements.
