# :artificial_satellite: Spatial Module

[![Reproducibility Check](https://github.com/espm-157/spatial-module-3-ashley-erin/actions/workflows/main.yml/badge.svg)](https://github.com/espm-157/spatial-module-3-ashley-erin/actions/workflows/main.yml)

## Team Members

🏙️ Ashley Nguyen
🌆 Erin Dominguez

## Overview

In this notebook, we will explore the environmental impacts of redlining, a racist practice used as a tool of residential segregation. We will compare our findings to those published in Science by Christopher Schell and colleagues, who show that for many cities there persists a significant difference between the amount of greenery in historically white and wealthy areas and redlined ones. We will use NDVI satellite data to determine the average level of “greenness” in every 100 meter block, and determine the average block greenness between areas historically given “A” (best), “B”, “C”, and “D” (worst) ratings for the cities of San Diego and Chicago.

The final layered map of NDVI and historical redlining in Chicago is available to view [here](https://espm-157.github.io/spatial-module-3-ashley-erin/)!

## Science Introduction

This paper contains the analysis we will attempt to partially replicate. It explores evidence for systemic racism by examining the legacy of redlining practices using satellite imagery. 

[Schell et al 2020](https://doi.org/10.1126/science.aay4497).  ([video lecture](https://www.youtube.com/watch?v=nnH9RSzORV0))

## Datasets

**1. [Mapping Inequality](https://dsl.richmond.edu/panorama/redlining/#loc=3/41.245/-105.469&text=intro):**

- This dataset contains vector data describing the broad characteristics of different zones in major American cities, including whether they were residential, commercial, and/or industrial, and what grade they received in the 1935-1940 survey contained in the dataset. The link above links to the introduction to the dataset, but the dataset can be downloaded or streamed (which we will do in this notebook) from the "download" page in the left bar.

**2. [Satellite Imagery from Sentinel-2 catalog](https://planetarycomputer.microsoft.com/dataset/sentinel-2-l2a):**

- This dataset contains satellite imagery in 13 spectral bands at a spatial resolution of approximately 10m-60m (we will reduce the resolution to 100m in our analysis for easier processing). The revisit time for Sentinel-2 is roughly 5 days. While the dataset contains rows from 2015 onward, we will only be streaming data from three months in 2025.


