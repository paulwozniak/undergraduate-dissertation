# undergraduate-dissertation
Code and links to datasets used for my final year dissertation as part of my undergraduate degree at University of Bath studying BSc (Hons) International Development with Economics.

## Project Overview
This project examines whether household proximity to environmentally protected areas is associated with multidimensional poverty outcomes, explored through the case study of Uganda. I answer this question using an original logistic regression model, which controls for household and spatial characteristics.

## Repository structure
- `scripts/` R scripts (run in numeric order)
- `data/raw/` raw inputs (not included in this repo)
- `data/processed/` derived datasets (if included)
- `outputs/` figures and tables

## Data access
Raw UNPS/LSMS microdata is not redistributed in this repository.  
To reproduce the analysis, obtain the datasets from: (add source + instructions)
Place raw files in `data/raw/` following the naming conventions in `data/README.md`.


Spatial layers:
- Protected areas (WDPA): (add citation / link)
- Human Footprint Index: (add citation / link)
- Topography (EarthEnv): (add citation / link)
- Major cities (Esri): (add citation / link)


## Reproducibility
This repo uses `renv` for package version control.

To restore packages:
```r
renv::restore()
