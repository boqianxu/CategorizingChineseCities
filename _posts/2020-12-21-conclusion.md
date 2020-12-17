---
title: "Conclusion"
date: 2020-12-21
excerpt: "Results and discussion."
categories:
  - blog
tags:
---

**Research Context and Research Question:**

China has one of the world’s most diverse territory with various urban and natural resources that are unevenly distributed across the country. Many people agree that the east coast provides abundant amenities for the residents while the west is primarily protected for the wild. However, visualization and analysis on the regional disparity, particularly on open-source media, is still insufficient in existing studies. How to categorize the livability of hundreds of cities in China from the perspectives of amenity and ecology?

**Research Method:** 

This interactive webpage project visualizes and analyzes the urban and natural conditions of the 371 cities in China with the OSM data of amenity and raster datasets of land cover. The central scheme of the study is clustering all the Chinese counties based on the values of public amenity and ecological service. First, the project uses the land cover maps from Google Earth Engine Data Catalog to calculate the ESV, Ecosystem Service Value, of each city. Second, The amenity data from Open Street Map will be mapped and spatial-joined to the 371 cities. The last step of the project is categorizing the 371 cities by the K-means clustering analysis.


**Data Source:**

- Administrative boundary (.shp): RESDC: (http://www.resdc.cn/data.aspx?DATAID=201)
- Amenity: OpenStreetMap
- Land cover:	Earth Engine: (https://developers.google.com/earth-engine/datasets/catalog/ESA_GLOBCOVER_L4_200901_200912_V2_3)
