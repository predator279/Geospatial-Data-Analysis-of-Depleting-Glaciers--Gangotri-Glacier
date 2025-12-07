#Geospatial Data Analysis of Depleting Glaciers

Performed glacier depletion assessment on the Gangotri Glacier using geospatial techniques on Sentinel-2 NDSI GeoTIFFs, applying image processing, threshold-based classification, and raster-to-vector analysis to map glacier boundary changes across years.

Engineered an end-to-end Python pipeline (Rasterio, GeoPandas, Shapely, Matplotlib) that ingests multi-year scenes, performs NDSI snow/ice extraction, vectorises glacier footprints, computes equal-area surface metrics, and visualizes retreat through polygon overlays.

Quantified -425.23 km² (-32.08%) glacier area loss between 2020 and 2025 for the Gangotri Glacier, validating results across multiple NDSI thresholds and removing noise from cloud/shadow artefacts.

<img width="630" height="426" alt="image" src="https://github.com/user-attachments/assets/4b142b58-99d8-4995-b0d0-d584c9bc80d9" />

Glacier area (old): 1325.40 km²

Glacier area (new): 900.17 km²

Loss in glacier area: 425.23 km² (32.08%)
