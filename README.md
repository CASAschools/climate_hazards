# Climate Hazards

## Description
The CASAschools capstone team identified 5 climate hazards that are actionable, relevant to schools, and align with California's 4th climate change assessment. These include wildfire, extreme heat, extreme precipitation, flooding, and sea-level rise. This repository contains Quarto Qmd's for each climate variable, the hazard summary metric, and school closure days due to natural disasters with detailed explanations of how the data was wrangled and prepared for summarizing and visualization in the interactive dashboard. 

To view more details about the analysis, please view the technical documentation here: https://bren.ucsb.edu/projects/climate-hazards-data-integration-and-visualization-climate-adaptation-solutions

## Table of Contents
- Data Sources
- Usage
- Packages and Software
- Authors
- License
  
## Data Sources
The 5 climate hazards were obtained from the following open source databases:
- Extreme heat: [Cal-Adapt caladaptR](https://ucanr-igis.github.io/caladaptr/)
- Flooding: [Federal Emergency Management Agency (FEMA)](https://hazards-fema.maps.arcgis.com/apps/webappviewer/index.html?id=8b0adb51996444d4879338b5529aa9cd)
- Extreme precipitation: [Cal-Adapt caladaptR](https://ucanr-igis.github.io/caladaptr/)
- Sea Level Rise: [U.S. Geological Survey (USGS) Coastal Storm Modeling System](https://www.usgs.gov/centers/pcmsc/science/coastal-storm-modeling-system-cosmos)
- Wildfire: [U.S. Department of Agriculture Forest Service (USFS) Wildfire Hazard Potential](https://www.firelab.org/project/wildfire-hazard-potential)


## Usage
This repository contains folders with Quarto Documents detailing how to access extreme heat and precipitation data from the CalAdapt API through the caladaptR package, and reading in files for wildfire, flooding, and sea-level rise. As well as how the hazard summary metric score was computed and combined all 5 hazards.

## Packages and Software
To view packages used, versions, and software requirements, please view the "session_info.txt" file.


## File Structure
This repository contains individual folders for each climate hazard where wrangling and cleaning is conducted. Descriptions of each folder and file can be viewed in the table below.

|Folders/Files|Description|
--------------|-----------|
| calmatters | Cleaning and prepping calmatters school closure data for dashboard |
| climate_hazard_summary| Development of climate hazard summary score and plotting example |
| extreme_heat | Calculation of maximum daily temperature threshold, number of extreme heat days, and dashboard prep |
| flooding-FEMA | Clipping of flood map to school boundaries, reassigning values, and mapping examples|
| precipitation | Calculation of maximum daily precipitation threshold, number of extreme precipitation days, and dashboard prep|
| sea_level_rise | Clipping of sea level rise map's to school boundaries, reassigning values, and mapping examples (2000 & 2050)|
| wildfire | lipping of wildfire map's to school boundaries, reassigning values, and mapping examples (2012 & 2023)|

```bash
├── calmatters
│   └── calmatter_cleaning.qmd
├── climate_hazards.Rproj
├── climate_hazard_summary
│   └── hazard_summary.qmd
├── extreme_heat
│   ├── dashboard_prep.qmd
│   ├── extreme_heat_threshold.qmd
│   ├── schools_extreme_heat_days_rcp45.qmd
│   └── schools_extreme_heat_days_rcp85.qmd
├── flooding-FEMA
│   ├── FEMA.qmd
│   ├── FEMA_schools.qmd
│   ├── FEMA_state.qmd
│   └── flooding_mapping.qmd
├── LICENSE
├── precipitation
│   ├── caladapt_precip_r.qmd
│   ├── joining_data.qmd
│   ├── schools_extreme_precip_days_rcp45.qmd
│   └── schools_extreme_precip_days_rcp85.qmd
├── README.md
├── sea_level_rise
│   └── sea_level_rise.qmd
├── session_info.txt
└── wildfire
    ├── wildfire_mapping.qmd
    └── wildfire_prep.qmd
```

 
## Authors 
The authors of this dashboard are [Liane Chen](https://github.com/lchenhub), [Charlie Curtin](https://github.com/charliecurtin1), [Kristina Glass](https://github.com/kristinaglass), and [Hazel Vaquero](https://github.com/hazelvaq). For any comments or questions about this dashboard, please reach out to @cp-casaschools@bren.ucsb.edu

## Licence
This work is licensed under a [Creative Commons Zero v1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/deed.en).
