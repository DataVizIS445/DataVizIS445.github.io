---
name: UFO Sightings Visualizations
tools: [Python, HTML, vega-lite, Altair]
image: assets/pngs/ufo.png
description: Interactive visualizations of UFO sightings using Altair and Vega-Lite.
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---

## Geographic Distribution of UFO Sightings

<vegachart schema-url="/assets/json/ufo_map.json" style="width: 100%"></vegachart>

## UFO Sightings Over Time by Shape (Interactive)

<vegachart schema-url="/assets/json/ufo_time.json" style="width: 100%"></vegachart>

## Search The Data & Methods

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/ufo-scrubbed-geocoded-time-standardized-00.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link='/blog/ufo-sightings-analysis' text="The Analysis" %}
</div>

