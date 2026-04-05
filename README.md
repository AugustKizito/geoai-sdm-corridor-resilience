# geoai-sdm-corridor-resilience
Reproducible workflow for GeoAI-integrated Spatial Durbin modeling of corridor resilience and regional divergence, including Earth Observation data processing, spatial econometric analysis, and GeoAI diagnostics.
# GeoAI-SDM Corridor Resilience Analysis

This repository provides the analytical workflow supporting the study:

"GeoAI-Integrated Spatial Durbin Modeling of Corridor Resilience and Regional Divergence"

## Overview

The study integrates spatial econometrics and GeoAI to analyze spatial spillovers, ecological thresholds, and infrastructure–environment interactions.

## Data Sources

- Nighttime Lights (VIIRS/DMSP): NOAA
- NDVI and environmental variables: Google Earth Engine
- Socioeconomic data: National statistical sources

## Methodology

1. Data extraction using Google Earth Engine
2. Spatial discretization using a hexagonal grid (2,680 cells)
3. Spatial Durbin Model (SDM) estimation
4. Random Forest modeling on SDM residuals
5. SHAP-based interpretability analysis

## Reproducibility

All scripts for preprocessing, modeling, and visualization are included or described. Data can be generated from the listed sources using the provided workflow.

## Contact

For additional data or code, contact the corresponding author.
