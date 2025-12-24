INLET-INTEGRATED WATERSHED CHARACTERIZATION
========================================

Overview
--------
This repository contains a Jupyter notebook workflow for inlet-integrated watershed characterization in urban settings.
The goal is to connect surface-based units (e.g., depressions/basins/catchments) to stormwater inlets and produce
GIS layers and summary tables that support event-based runoff and connectivity analysis.

Notebook
--------
- inlet_integrated_watershed_characterization_polished_comments.ipynb
  (Documentation and code comments polished for sharing.)

Credits (TAMUCC, 2025)
----------------------
Author 1 : Lapone Techapinyawat, Ph.D.
Author 2: Hua Zhang, Ph.D.
Affiliation: College of Engineering, Texas A&M University–Corpus Christi (TAMUCC)

Inputs
------
Put your input data in a folder such as "data/" (or update file paths inside the notebook). Typical inputs include:
- DEM / rasters: TIFF (elevation)
- Vector layers: Shapefile / GeoPackage / GeoJSON
  - inlets (points)
  - basins / depressions (polygons)
  - optional: buildings, boundary masks

Outputs
-------
The notebook may produce:
- inlet-linked basins/catchments (vector)
- connectivity edges (vector)
- summary tables (CSV)
- figures (PNG)

Citation
--------
If you reuse or adapt this workflow, please cite/credit the repository and associated publications (if applicable).
