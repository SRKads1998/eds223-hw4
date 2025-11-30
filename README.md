# Aquaculture Suitability Mapping: An Analysis of EEZ zones by species suitability

### By Stephan Kadonoff

![Mussel Aquaculture](https://godeepaquaculture.com/wp-content/uploads/2015/04/Mussel-Farming-Methods-Banner.jpg)

## Purpose

With concerns surrounding the long term health and availability of wild caught oceanic species, both due to over-fishing and climate change, understanding what domestic areas are available for aquaculture is incredibly important. Not only would it help peserve wild populations of many at risk species, it would also ensure the internalization of economic pipeline by which these creatures are brought to our shores.

This repository and it's contents are to serve as a way to analyze Economic Exclusion Zones, or EEZs, along the Pacific Coast of the United States, and determine how viable these regions are for aquaculture for different types of marine life. We looked at two important and easily harvested species, Oysters and Blue Mussels, and mapped what areas along the west coast of the United States would be best for aquaculture.

## Repository Contents

```
├── .Rhistory
├── .gitignore
├───   data/
│   ├── average_annual_sst_2008.tif
│   ├── average_annual_sst_2009.tif
│   ├── average_annual_sst_2010.tif
│   ├── average_annual_sst_2011.tif
│   ├── average_annual_sst_2012.tif
│   ├── depth.tif
│   ├── wc_regions_clean.shp
├── EDS223-hw4.Rproj
├── Aquaculture and Species Suitability.qmd
├── Images/
│   ├── screenshot1.png
│   ├── screenshot2.png
│   ├── screenshot3.png
├── README.md
```

## References and Citations
“SeaLifeBase.” Search SeaLifeBase, www.sealifebase.ca/search.php. Accessed 25 Nov. 2025. 
Watch, NOAA Coral Reef. NOAA Coral Reef Watch Daily 5km Satellite Coral Bleaching Heat Stress SST Anomaly Product (Version 3.1), coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php. Accessed 28 Nov. 2025. 
“Gridded Bathymetry Data.” GEBCO, www.gebco.net/data-products/gridded-bathymetry-data#area. Accessed 28 Nov. 2025. 
Marine Regions, www.marineregions.org/eez.php. Accessed 28 Nov. 2025. 

## Data Access

All data required for the analysis conducted within the quarto document "Aquaculture Species Suitability" can be freely accessed at the following website links:

Species parameter information for temperature and depth ranges: https://www.sealifebase.ca/search.php

Sea Surface Temperature readings: https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php

Bathymetry data: https://www.gebco.net/data-products/gridded-bathymetry-data#area

Exclusive Economic Zone shapefiles: https://www.marineregions.org/eez.php
