---
title: "2. Mapping Amenity Value of Chinese cities"
date: 2020-12-21
published: true
tags: 
excerpt: "This section examines amenities with OSM data."
toc: true
toc_sticky: true
read_time: false
---

## Amenity Value

This research loaded three types of Point Of Interest (POI) from Open Street Map (OSM), including restaurant, hospital, and school. A higher POI density indicates that a city is  more amenity-valuable. Below is the map of amenity values.

![Average Amenities in Chinese cities]({{ site.url }}{{ site.baseurl }}/assets/images/Average Amenities in Chinese cities.png)

## Notes:
- OSM data is very limited in China, except for Hong Kong, Macau, and Taiwan. OSM only has 152537 restaurants, 77699 hospitals, and 152585 schools, which is not even close to expectation.
- Querrying OSM data at a large scale requires Google BigQuery.

```python
from google.cloud import bigquery
```
