# Evaluating CMIP6 Model Performance and Future Precipitation Projections Across Jordan's Water Basins Under SSP Scenarios

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.XXXXXXX.svg)](https://doi.org/10.5281/zenodo.XXXXXXX)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

## Overview

This repository contains the analysis code, station data, and supplementary materials for the study:

> **Omar, H., Abdulla, F., Khomsi, K., & Al-Delaiwy, W.** (2026). Evaluating CMIP6 Model Performance and Future Precipitation Projections Across Jordan's Water Basins Under SSP Scenarios. *Journal of Arid Land*. https://doi.org/XXXXXXX

The study evaluates six bias-adjusted dynamically downscaled CMIP6-driven simulations (HCLIM-ALADIN-38 RCM at 0.1° resolution) over 12 of Jordan's 15 hydrological basins against 49 ground-based stations for the reference period 1995–2014, and projects future precipitation under SSP2-4.5 and SSP5-8.5 scenarios.

---

## Data Availability

Large NetCDF files (raw daily inputs and projection difference outputs, ~1 GB each) are archived on Zenodo:

**Zenodo repository:** [![DOI](https://zenodo.org/badge/1264061443.svg)](https://doi.org/10.5281/zenodo.20613052) 

The Zenodo archive contains:
- `input_nc/` — Raw daily bias-adjusted HCLIM-ALADIN-38 simulations for 6 driving GCMs (historical + SSP2-4.5 + SSP5-8.5)
- `projection_differences/` — NetCDF files of projected precipitation differences (future minus reference period)

---

## Models and Scenarios

| Driving GCM | Institution |
|---|---|
| CMCC-CM2-SR5 | CMCC, Italy |
| CNRM-ESM2-1 | CNRM-CERFACS, France |
| EC-Earth3-Veg | EC-Earth Consortium |
| IPSL-CM6A-LR | IPSL, France |
| MPI-ESM1-2-LR | MPI-M, Germany |
| NorESM2-MM | NCC, Norway |

**Scenarios:** SSP2-4.5, SSP5-8.5  
**Reference period:** 1995–2014  
**Future periods:** 2021–2040, 2041–2060, 2061–2080, 2081–2100  
**Resolution:** 0.1° (~11 km) — RICCAR Mashreq Domain

---

## Repository Structure
