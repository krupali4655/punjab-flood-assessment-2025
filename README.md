# Flood Impact Assessment using Google Earth Engine (Punjab, India)

This project uses Google Earth Engine (GEE) and Landsat 9 satellite imagery to assess the impact of flooding in Punjab, India. It compares pre-flood (May–June 2025) and post-flood (September–October 2025) conditions to identify areas affected by water inundation and vegetation loss.

The analysis is based on two key spectral indices — the Normalized Difference Water Index (NDWI) and the Normalized Difference Vegetation Index (NDVI). NDWI helps detect surface water changes, while NDVI indicates vegetation health. By comparing these indices before and after the flood, the project highlights flooded zones and regions where vegetation was damaged.

Using Google Earth Engine’s cloud-based processing, the script filters Landsat 9 images, removes cloudy pixels, and computes NDWI and NDVI for both time periods. It then applies threshold values to map flood-affected and vegetation-damaged areas, and calculates their extent in hectares and as a percentage of the total area of interest. The results are displayed on the map and summarized in the console, with options to export maps and summary data.

This project demonstrates how satellite data and GEE can be used for rapid flood impact assessment and agricultural damage analysis over large regions.
