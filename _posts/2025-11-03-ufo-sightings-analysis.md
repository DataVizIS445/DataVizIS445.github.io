---
title: UFO Sightings Visualization Analysis
tags: [Technology, Analysis]
style: fill
color: secondary
description: Analysis and description of the plots in the UFO Sightings Visualization.
---

## Plot 1 - Aggregated UFO Sightings in the U.S.

This visualization shows the distribution of UFO sightings across the US. Each point represents a sighting, positioned using its latitude and longitude.  
I used the count of sightings as a quantitative encoding for color using the "plasma" color scheme for better visibility of differences. Before visualization, I filtered the data to include only U.S. sightings and removed rows missing coordinate information. This visualization helps identify "hotspots" of UFO activity, with notable clusters along the East and West Coasts. The aliens must like the weather.

## Plot 2 - UFO Sightings Over Time by Shape (Interactive)

This line chart shows the number of UFO sightings over time, grouped by the reported shape of the object. The x-axis represents the year of the sighting, while the y-axis represents the number of reports.  Colors show different shapes using the Tableau 10 color scheme, chosen for overall clarity. Data was transformed by converting the datetime column to a pandas datetime type and extracting the year value. The visualization reveals patterns such as spikes in reports during certain decades and differing trends among shapes.

This chart includes an interactive selection mechanic that allows users to focus on a specific UFO shape. When a shape is clicked in the chart, its line becomes highlighted while others fade to gray. This interactivity improves clarity by letting users see which UFO shapes were more frequently reported in certain time periods, without overwhelming them with all categories at once. I did this because I was overwhelmed at first when looking at the chart, so it seemed logical to do.

<div class="right">
{% include elements/button.html link='https://github.com/DataVizIS445/DataVizIS445.github.io/blob/main/python_notebooks/HW5.2.ipynb' text="Python Notebook Link" %}
</div>
