# Rail Temperature Climate Risk Map

Static HTML deployment for the rail temperature climate risk map.

This repository intentionally excludes raw source CSV files and intermediate processing outputs. The deployed site contains only derived, map-ready annual summary data.

## Contents

- `index.html`: Leaflet map UI with SSP, year, month, and metric controls.
- `data/points.json`: derived coordinate point list.
- `data/railtemp_annual_SSP*.json`: derived annual point-level climate risk summaries.

## Source Data Policy

Raw input files such as `railtemp_Rank*_SSP*.csv`, merged CSV files, and compressed source-data chunks are not included in this deployment.
