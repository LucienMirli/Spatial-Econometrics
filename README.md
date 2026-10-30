# Spatial Econometrics – Spatial Cluster Detection

## Overview

This repository contains an applied spatial econometrics project based on the research paper *“Scan Methods and Spatial Structure”* (López et al., 2015), published in *Papers in Regional Science*.

The project explores the detection of spatial clusters and the identification of spatial dependence in econometric models, combining traditional spatial autocorrelation tests with spatial scan statistics.

An empirical application is conducted using the **Boston Housing dataset (506 observations)**, with implementations in **R**.

## Methodology

The analysis follows several steps:

1. **Exploratory Spatial Data Analysis (ESDA):** Examination of spatial patterns and spatial autocorrelation using Moran's I.
2. **Spatial Econometric Models:** Estimation and comparison of Ordinary Least Squares (OLS), Spatial Autoregressive (SAR), and Spatial Error Models (SEM).
3. **Spatial Scan Statistics:** Implementation of the scan methodology to identify statistically significant spatial clusters, particularly in model residuals.
4. **Statistical Inference:** Monte Carlo permutation procedures to evaluate cluster significance.
5. **Model Diagnostics:** Comparison of residual spatial structures across econometric specifications to assess whether spatial dependence has been adequately captured.

The project illustrates how spatial scan statistics can complement global autocorrelation measures by identifying **localized spatial structures** that may remain undetected by traditional diagnostic tests.

## Repository Contents

| File | Description |
|---|---|
| `Projet_cluster_detection.Rmd` | Complete R Markdown source code, including data processing, econometric estimations, statistical tests, and visualizations. |
| `Projet_cluster_detection.pdf` | Rendered PDF version of the empirical analysis, including code, results, and interpretations. |
| `Slides_cluster_detection.pdf` | Presentation slides used for the oral defense, covering the theoretical framework, methodology, and empirical findings. |
| `README.md` | Project documentation and overview. |

## Tools and Packages

**Language:** R

Main packages:
- `sf` – Spatial data manipulation
- `spdep` – Spatial weights and autocorrelation tests
- `spatialreg` – Spatial econometric models
- `rsatscan` – Spatial scan statistics using SaTScan
- `ggplot2` and `leaflet` – Spatial visualization

## Reference

López et al. (2015). *Scan Methods and Spatial Structure*. Papers in Regional Science.

## Project Objective

The main objective is to investigate whether spatial econometric models successfully account for spatial dependence and to demonstrate the usefulness of scan statistics as a complementary diagnostic tool for detecting local spatial clusters.
