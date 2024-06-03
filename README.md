# Climate Hazards

## Description
The CASAschools capstone team identified 5 climate hazards that are actionable, relevant to schools, and align with California's 4th climate change assessment. These include wildfire, extreme heat, extreme precipitation, flooding, and sea-level rise. This repository contains Quarto Qmd's for each climate variable, the hazard summary metric, and school closure days due to natural disasters with detailed explanations of how the data was wrangled and prepared for summarizing and visualization in the interactive dashboard. 

## Table of Contents
- Data Sources
- Usage
- Authors
- License
  
## Data Sources
The 5 climate hazards were obtained from the following open source databases:
- Extreme heat: [Cal-Adapt caladaptR](https://ucanr-igis.github.io/caladaptr/)
- Flooding: [Federal Emergency Management Agency (FEMA)](https://hazards-fema.maps.arcgis.com/apps/webappviewer/index.html?id=8b0adb51996444d4879338b5529aa9cd)
- Extreme precipitation: [Cal-Adapt caladaptR](https://ucanr-igis.github.io/caladaptr/)
- Sea Level Rise: [National Oceanic and Atmospheric Administration (NOAA)](https://www.climate.gov/maps-data/dataset/sea-level-rise-map-viewer)
- Wildfire: [U.S. Department of Agriculture Forest Service (USFS) Wildfire Hazard Potential](https://www.firelab.org/project/wildfire-hazard-potential)


## Usage
This repository contains folders with Quarto Documents detailing how to access extreme heat and precipitation data from the CalAdapt API through the caladaptR package, and reading in files for wildfire, flooding, and sea-level rise. As well as how the hazard summary metric score was computed and combined all 5 hazards.


### File Structure

```markdown
├── calmatters
│   └── calmatter_cleaning.qmd
├── climate_hazards.Rproj
├── climate_hazard_summary
│   └── index_prep.qmd
├── dashboard_prep
│   └── reactive_text.qmd
├── extreme_heat
│   ├── caladapt-r.qmd
│   ├── dashboard_prep.qmd
│   ├── schools_extreme_heat_days_rcp_45.qmd
│   └── schools_extreme_heat_days_rcp85.qmd
├── flooding-FEMA
│   ├── FEMA_data_prep.qmd
│   ├── FEMA_flood.Rproj
│   ├── FEMA.qmd
│   ├── FEMA_schools.qmd
│   ├── FEMA_state.qmd
│   ├── flooding_mapping.qmd
│   └── flooding.R
├── LICENSE
├── precipitation
│   ├── caladapt_precip_r.qmd
│   ├── joining_data.qmd
│   ├── schools_extreme_precipitation_4.qmd
│   └── schools_extreme_precip.qmd
├── README_CASAschools.html
├── README_CASAschools.md
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
