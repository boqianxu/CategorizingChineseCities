---
title: "3. Clustering Analysis"
date: 2020-12-21
published: true
tags: 
excerpt: "This section categorizes the cities based on ESV and Amenity Value."
altair-loader:
  altair-chart-1: "charts/Clusters_altair.json"
hv-loader:
  hv-chart-1: "charts/measlesHvplot.html"
toc: true
toc_sticky: true
---

This post will show examples of embedding interactive charts produced using [Altair](https://altair-viz.github.io) and [Hvplot](https://hvplot.pyviz.org/).

## Altair Example

Lastly, this research categorized the 371 cities into six categories (five by K-Means analysis, the other is the outliers with much more OSM data).

<div id="altair-chart-1"></div>


```python
import altair as alt
alt.renderers.enable('notebook')
```

## HvPlot Example

Lastly, the measles incidence produced using the HvPlot package:

<div id="hv-chart-1"></div>

## Notes

- See the [raw source code](https://raw.githubusercontent.com/MUSA-550-Fall-2020/github-pages-starter/master/_posts/2019-04-13-measles-charts.md) of this post for details on how these charts were embedded.
- See the [lecture 13A slides](https://github.com/MUSA-550-Fall-2020/week-13/blob/master/lecture-13A.ipynb) for the code that produced these plots.

**Important: When embedding charts, you will likely need to adjust the width/height of the charts before embedding them in the page so they fit nicely when embedded.**---
