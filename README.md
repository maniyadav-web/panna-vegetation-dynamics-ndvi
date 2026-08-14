# Vegetation Dynamics Analysis of Panna Study Area (2022–2026)

## Overview

This project assesses changes in observed vegetation greenness in the Panna
study area of Madhya Pradesh using multi-temporal Resourcesat-2A LISS-III
imagery and GIS-based NDVI analysis.

## Objectives

- Generate NDVI maps for 2022 and 2026
- Quantify pixel-wise NDVI change
- Classify change into vegetation loss, stable, and gain
- Quantify the area of each change category

## Data

- Resourcesat-2A / LISS-III
- 21 March 2022
- 24 March 2026
- Spatial resolution: 24 m
- Data source: ISRO/NRSC Bhoonidhi
- Study-area boundary: NTCA Protected Areas / Tiger Reserves dataset

## Methodology

Resourcesat-2A imagery
        ↓
Study-area masking
        ↓
NDVI calculation
        ↓
NDVI 2022 + NDVI 2026
        ↓
NDVI Change = NDVI₂₀₂₆ − NDVI₂₀₂₂
        ↓
Classification
        ↓
Loss / Stable / Gain

### NDVI

NDVI = (NIR − Red) / (NIR + Red)

### Change Classification

- NDVI change < -0.05 → Vegetation Loss
- -0.05 ≤ NDVI change < +0.05 → Stable
- NDVI change ≥ +0.05 → Vegetation Gain

## Results

| Metric | 2022 | 2026 |
|---|---:|---:|
| Mean NDVI | 0.2762 | 0.3058 |

Mean NDVI increased by approximately 0.0296 NDVI units (10.7%).

### Change Classification

- Vegetation Loss: 3.88% (20.32 km²)
- Stable: 68.26% (357.54 km²)
- Vegetation Gain: 27.86% (145.94 km²)

Analyzed area: 523.80 km²

## Maps

Include:
- Study Area
- NDVI 2022
- NDVI 2026
- NDVI Change 2022–2026

## Tools

- QGIS
- Raster analysis
- Remote sensing
- NDVI
- GeoTIFF
- Resourcesat-2A LISS-III

## Limitations

The analysis was restricted to the usable/cloud-free portion of the selected
study-area boundary. NDVI change indicates change in observed vegetation
greenness and does not by itself establish changes in forest health or identify
causal drivers.
