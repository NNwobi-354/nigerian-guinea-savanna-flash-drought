# Spatiotemporal Dynamics and Ecohydrodynamic Decoupling of Flash Drought Cascades in the Nigerian Guinea Savanna (2015–2025)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NNwobi-354/nigerian-guinea-savanna-flash-drought/blob/main/Nigerian_Guinea_Savanna_Flash_Drought_Workflow_FINAL.ipynb)
[![Python 3.10+](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![GitHub Repository](https://img.shields.io/badge/GitHub-NNwobi--354-181717?logo=github)](https://github.com/NNwobi-354/nigerian-guinea-savanna-flash-drought)

---

## 1. Overview & Research Scope

This repository provides an open-source, end-to-end computational pipeline for quantifying flash drought onset trajectories, atmospheric water demand surges, subsurface moisture depletion, and canopy transpiration decoupling across the Nigerian Guinea Savanna (NGS) from 2015 to 2025.

By integrating multi-satellite raster observations from Google Earth Engine (GEE)—including **ERA5-Land**, **SMAP L4**, and **PML_V2.2a VIIRS**—this project establishes a reproducible workflow for spatial statistical analysis, lead-lag cross-correlations, tipping-point threshold modeling, and high-resolution spatial hotspot mapping.

---

## 2. Complete Repository Directory Hierarchy

```text
nigerian-guinea-savanna-flash-drought/
├── Data/
│   ├── GEE Scripts/
│   │   └── Readme.md                                      # Google Earth Engine JavaScript extraction scripts & setup instructions
│   └── NGS_Shapefile/
│       └── Readme.md                                      # Shapefile boundary specifications, coordinate system (EPSG:4326), & metadata
├── .gitignore                                             # Version control rules to ignore checkpoints, raw cache, and byte-code
├── LICENSE                                                # MIT Open Source License file
├── Nigerian_Guinea_Savanna_Flash_Drought_Workflow_FINAL.ipynb  # Comprehensive master Google Colab notebook
└── README.md                                              # Primary repository documentation and execution guide
