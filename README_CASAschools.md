---
editor_options: 
  markdown: 
    wrap: 72
---

This README.txt file was generated on 2024-05-23 by Liane Chen, Charlie
Curtin, Kristina Glass, and Hazel Vaquero

**GENERAL INFORMATION**

1\. Title of the Project: Climate Adaptation Solutions Accelerator
through School Community Hubs

2\. Author Information

A. Principal Investigator Contact Information Name: Liane Chen, Charlie
Curtin, Kristina Glass, and Hazel Vaquero

Institution: University of California Santa Barbara Bren School of
Environmental Science & Management

Address: Bren Hall, 2400 University of California, Santa Barbara, CA
93117 Email: [liane\@ucsb.edu](mailto:liane@ucsb.edu){.email},
[charlescurtin\@ucsb.edu](mailto:charlescurtin@ucsb.edu){.email},
[kristinaglass\@ucsb.edu](mailto:kristinaglass@ucsb.edu){.email},
[hazelvaquero\@ucsb.edu](mailto:hazelvaquero@ucsb.edu){.email}

B. Associate or Co-investigator Contact Information Name: Dr. Simone
Pulver Institution: University of California Santa Barbara,
Environmental Studies Program Address: 4001 Bren Hall, 2400 University
of California, Santa Barbara, CA 93117 Email:
[pulver\@ucsb.edu](mailto:pulver@ucsb.edu){.email}

C. Alternate Contact Information Name: Dr. Sarah Anderson

Institution: University of California Santa Barbara Bren School of
Environmental Science & Management

Address: 4510 Bren Hall, 2400 University of California, Santa Barbara,
CA 93117

Email:
[sanderson\@bren.ucsb.edu](mailto:sanderson@bren.ucsb.edu){.email}

d.  Alternate Contact Information Name: Dr. Danielle Harlow

Institution: University of California Santa Barbara The Gevirtz School

Address: Education 3129 Gevirtz Graduate School of Education, University
of California-Santa Barbara, CA 93106

Email:
[danielle.harlow\@ucsb.edu](mailto:danielle.harlow@ucsb.edu){.email}

3\. Date of data collection or obtaining

Hazards Data

-   FEMA Flood NFHL V3.2: 2024-03-13

-   Wildfire Hazard Potential for the United States (270-m) version 2023
    (4th Edition): 2024-04-12

-   Coastal Storm Modeling System: 2024-04-02

-   Cal-Adapt:

    -   Maximum Daily Temperature: 2024-03-13

    -   Maximum Daily Precipitation: 2024-03-13

California Department of Education School Boundaries Data

-   California Schools 2022-2023: 2024-03-05

-   California School District Area 2022-2023

-   CalMatters Disaster Days: 2024-04-1

4\. Geographic location of data collection:

California, CA:

-   Cal-Adapt

-   Coastal Storm Modeling

-   California Schools 2022-2023

-   California School District Areas

-   CalMatters Disaster Days

-   FEMA NFHL

National:

-   Wildfire Hazard Potential for the United States (270-m) version 2023
    (4th Edition):

5\. Information about funding sources that supported the collection of
the data:

**SHARING/ACCESS INFORMATION**

1\. Licenses/restrictions placed on the data:

Open Source:

-   FEMA Flood NFHL V3.2

-   Wildfire Hazard Potential for the United States (270-m) version 2023
    (4th Edition)

-   Coastal Storm Modeling System

-   Cal-Adapt:

    -   Maximum Daily Temperature

    -   Maximum Daily Precipitation

School Boundaries Data

-   California Schools 2022-2023

-   California School District Area 2022-2023

-   CalMatters Disaster Days

2\. Links to location of data:

-   FEMA Flood NFHL V3.2: <https://msc.fema.gov/portal/advanceSearch>

-   Wildfire Hazard Potential for the United States (270-m) version 2023
    (4th Edition):
    <https://www.fs.usda.gov/rds/archive/catalog/RDS-2015-0047-4>

-   Coastal Storm Modeling System:
    <https://ourcoastourfuture.org/hazard-map>

-   Cal-Adapt: <https://ucanr-igis.github.io/caladaptr>

    -   Maximum Daily Temperature

    -   Maximum Daily Precipitation

School Boundaries Data

-   California Schools 2022-2023:
    <https://gis.data.ca.gov/datasets/CDEGIS::california-schools-2022-23/about>

-   California School District Area 2022-2023:
    <https://gis.data.ca.gov/maps/CDEGIS::california-school-district-areas-2022-23/about>

-   CalMatters Disaster Days:
    <https://disasterdays.calmatters.org/california-school-closures>

6\. Recommended citation for the project:

Curtin, Charles; Glass, Kristina; Chen, Liane; Vaquero, Hazel
(Forthcoming 2024). Climate Hazards Data Integration and Visualization
for the Climate Adaptations Solutions Accelerator through
School-Community Hubs [Dataset]. Dryad.
<https://doi.org/10.5061/dryad.1jwstqk3g>

**DATA & FILE OVERVIEW**

1\. File List: relevant files contained in the CASAschools GitHub
organization: <https://github.com/CASAschools>

├── climate_hazards

│ ├── calmatters

│ │ └── calmatter_cleaning.qmd: *Cleaning Calmatters Disaster day .csv to be displayed on dashboard*

│ ├── climate_hazards.Rproj

│ ├── climate_hazard_summary

│ │ └── index_prep.qmd

│ ├── extreme_heat

│ │ ├── caladapt-r.qmd: *Determine maximum daily temperature 98th percentile threshold* 

│ │ ├── dashboard_prep.qmd: *Joined RCP4.5 & RCP8.5 and prepped the dataframe for usage in daashboard*

│ │ ├── schools_extreme_heat_days_rcp_45.qmd: *Extreme heat days calculated for all 10,008 schools in a RCP 4.5 scenario*

│ │ └── schools_extreme_heat_days_rcp85.qmd: *Extreme heat days calculated for all 10,008 schools in a RCP 8.5 scenario*

│ ├── flooding-FEMA

│ │ ├── FEMA_data_prep.qmd

│ │ ├── FEMA_flood.Rproj

│ │ ├── FEMA.qmd

│ │ ├── FEMA_schools.qmd

│ │ ├── FEMA_state.qmd

│ │ ├── flooding_mapping.qmd

│ │ └── flooding.R

│ ├── LICENSE

│ ├── precipitation

│ │ ├── caladapt_precip_r.qmd

│ │ ├── joining_data.qmd

│ │ ├── schools_extreme_precipitation_4.qmd

│ │ └── schools_extreme_precip.qmd

│ ├── sea_level_rise

│ │ └── sea_level_rise.qmd: *cleans sea level rise data and prepares it
for use in the hazard summary score and mapping in the dashboard*

│ └── wildfire

│ ├── wildfire_mapping.qmd: *prepares wildfire data for mapping in the
dashboard*

│ └── wildfire_prep.qmd: *cleans wildfire data and prepares it for use
in the hazard summary score*

├── hazard_summary_metric

│ ├── hazard_summary_metric.Rproj

│ ├── hazard_summary.qmd: *normalizes data on a scale from 0-5 and
prepares for plotting in the dashboard*

├── school-boundaries

│ ├── prepare_school_buffers.qmd

│ ├── README.md

│ ├── school-boundaries.Rproj

│ ├── school_district_boundaries.qmd

│ └── school_point_buffer.qmd

├── shiny_dashboard: *all of the code needed to run the California
Schools Climate Hazards Dashboard*

│ ├── global.R: *datasets, packages, and global options needed to run
the dashboard*

│ ├── R: *scripts that build plots, maps, and reactive text*

│ ├── server.R: *outputs plots, maps, and connects the buttons based on
user input*

│ ├── shiny_dashboard.Rproj

│ ├── text: *markdown files that contain the text for each page*

│ ├── ui.R: *layout elements and structure of the dashboard*

│ └── www: *any images used in the dashboard*

2\. Relationship between files, if important:

All of the repositories up to shiny_dashboard contain the code needed to
create final outputs for use in the California Schools Climate Hazards
Dashboard. The shiny_dashboard uses these datasets, which are included
as a part of this submission.

**METHODOLOGICAL INFORMATION**

1\. Description of methods used for collection/generation of data:

Data for extreme heat and extreme precipitation were retrieved using API
requests from the caladaptr package. The data retrieved to calculate
extreme heat days were historical observed daily maximum temperature for
1961-2005 and projected daily maximum temperature for 2006-2064. The
data retrieved to calculate extreme precipitation days were historical
observed daily precipitation totals for 1961-2005 and projected daily
precipitation totals for 2006-2064.

Data for wildfire, flooding, and sea level rise were downloaded directly
from their sources and stored in a remote server for use.

2\. Methods for processing the data:

All data were processed in R Studio using Quarto Docs. Tabular data for
extreme heat and precipitation first used the retrieved historical data
to calculate a threshold value to classify an extreme event. The
threshold was determined to be the 98th percentile value of observed
historical data for California. For extreme heat, this is 98°F. For
extreme precipitation, this is 0.73 inches. Then, projected daily values
exceeding these thresholds were assigned a 1, and those not exceeding
assigned a 0. The count of projected extreme days within each year from
2005-2064 was then assigned to each California public school.

Spatial data was mainly processed to serve mapping purposes in the
dashboard. The wildfire raster was clipped to the boundaries of
California and reclassified. The mean wildfire hazard potential score
for each school area was also derived and attached to each school. The
original FEMA flood polygons have many different classifications, which
were reclassified into three categories: high risk, moderate to low
risk, and undetermined risk. The percentage of each school area that
falls within a high risk flood zone was also attached to each school.
The sea level rise polygons simply describe the extent of flooding under
a 0.8 feet sea level rise scenario and a 100-year coastal storm. The
polygons were simplified to decrease map load times in the dashboard.
The percentage of each school area affected by the sea level rise
scenario and a 100-year coastal storm were also attached to each school.

To read a more detailed description of data processing, please refer to
the "Summary of Solution Design" section in CASAschools Technical
Documentation:
<https://bren.ucsb.edu/projects/climate-hazards-data-integration-and-visualization-climate-adaptation-solutions>

3\. Instrument- or software-specific information needed to interpret the
data: \<include full name and version of software, and any necessary
packages or libraries needed to run scripts\>

-   Software: R Studio version 2022.12.0.353.20

-   R version 4.2.2 (2022-10-31)

-   Packages and versions used:

        - abind                [* -> 1.4-5]
        - anytime              [* -> 0.3.9]
        - askpass              [* -> 1.1]
        - backports            [* -> 1.4.1]
        - base64enc            [* -> 0.1-3]
        - BH                   [* -> 1.81.0-1]
        - bit                  [* -> 4.0.5]
        - bit64                [* -> 4.0.5]
        - blob                 [* -> 1.2.3]
        - brew                 [* -> 1.0-8]
        - brio                 [* -> 1.1.4]
        - broom                [* -> 1.0.5]
        - bslib                [* -> 0.7.0]
        - cachem               [* -> 1.0.8]
        - callr                [* -> 3.7.6]
        - cellranger           [* -> 1.1.0]
        - class                [* -> 7.3-20]
        - classInt             [* -> 0.4-10]
        - cli                  [* -> 3.6.2]
        - clipr                [* -> 0.8.0]
        - colorspace           [* -> 2.1-0]
        - commonmark           [* -> 1.8.1]
        - conflicted           [* -> 1.2.0]
        - countrycode          [* -> 1.6.0]
        - cpp11                [* -> 0.4.3]
        - crayon               [* -> 1.5.2]
        - credentials          [* -> 1.3.2]
        - crosstalk            [* -> 1.2.1]
        - curl                 [* -> 5.0.0]
        - data.table           [* -> 1.14.8]
        - DBI                  [* -> 1.2.2]
        - dbplyr               [* -> 2.5.0]
        - desc                 [* -> 1.4.3]
        - devtools             [* -> 2.4.5]
        - dichromat            [* -> 2.0-0.1]
        - diffobj              [* -> 0.3.5]
        - digest               [* -> 0.6.35]
        - downlit              [* -> 0.4.2]
        - dplyr                [* -> 1.1.3]
        - dtplyr               [* -> 1.3.0]
        - e1071                [* -> 1.7-14]
        - ellipsis             [* -> 0.3.2]
        - evaluate             [* -> 0.23]
        - fansi                [* -> 1.0.6]
        - farver               [* -> 2.1.1]
        - fastmap              [* -> 1.1.1]
        - fontawesome          [* -> 0.5.2]
        - forcats              [* -> 1.0.0]
        - fs                   [* -> 1.6.4]
        - gargle               [* -> 1.3.0]
        - generics             [* -> 0.1.3]
        - geojsonsf            [* -> 2.0.3]
        - geometries           [* -> 0.2.4]
        - gert                 [* -> 1.9.2]
        - ggplot2              [* -> 3.5.0]
        - gh                   [* -> 1.4.0]
        - gitcreds             [* -> 0.1.2]
        - glue                 [* -> 1.7.0]
        - googledrive          [* -> 2.0.0]
        - googlesheets4        [* -> 1.0.1]
        - gridExtra            [* -> 2.3]
        - gtable               [* -> 0.3.4]
        - haven                [* -> 2.5.2]
        - here                 [* -> 1.0.1]
        - highr                [* -> 0.10]
        - hms                  [* -> 1.1.3]
        - htmltools            [* -> 0.5.8.1]
        - htmlwidgets          [* -> 1.6.4]
        - httpuv               [* -> 1.6.9]
        - httr                 [* -> 1.4.5]
        - httr2                [* -> 0.2.2]
        - ids                  [* -> 1.0.1]
        - ini                  [* -> 0.3.1]
        - isoband              [* -> 0.2.7]
        - janitor              [* -> 2.2.0]
        - jquerylib            [* -> 0.1.4]
        - jsonify              [* -> 1.2.2]
        - jsonlite             [* -> 1.8.8]
        - KernSmooth           [* -> 2.23-20]
        - knitr                [* -> 1.46]
        - labeling             [* -> 0.4.3]
        - later                [* -> 1.3.0]
        - lattice              [* -> 0.20-45]
        - lazyeval             [* -> 0.2.2]
        - leafem               [* -> 0.2.3]
        - leaflet              [* -> 2.2.2]
        - leaflet.extras       [* -> 1.0.0]
        - leaflet.minicharts   [* -> 0.6.2]
        - leaflet.providers    [* -> 2.0.0]
        - leafsync             [* -> 0.1.0]
        - lifecycle            [* -> 1.0.4]
        - lubridate            [* -> 1.9.2]
        - lwgeom               [* -> 0.2-13]
        - magrittr             [* -> 2.0.3]
        - MASS                 [* -> 7.3-58.1]
        - Matrix               [* -> 1.5-1]
        - memoise              [* -> 2.0.1]
        - mgcv                 [* -> 1.8-41]
        - mime                 [* -> 0.12]
        - miniUI               [* -> 0.1.1.1]
        - modelr               [* -> 0.1.10]
        - munsell              [* -> 0.5.1]
        - nlme                 [* -> 3.1-160]
        - openssl              [* -> 2.0.6]
        - pillar               [* -> 1.9.0]
        - pkgbuild             [* -> 1.4.4]
        - pkgconfig            [* -> 2.0.3]
        - pkgdown              [* -> 2.0.7]
        - pkgload              [* -> 1.3.4]
        - plotly               [* -> 4.10.4]
        - png                  [* -> 0.1-8]
        - praise               [* -> 1.0.0]
        - prettyunits          [* -> 1.1.1]
        - processx             [* -> 3.8.4]
        - profvis              [* -> 0.3.7]
        - progress             [* -> 1.2.2]
        - promises             [* -> 1.2.0.1]
        - proxy                [* -> 0.4-27]
        - ps                   [* -> 1.7.6]
        - purrr                [* -> 1.0.2]
        - R6                   [* -> 2.5.1]
        - ragg                 [* -> 1.2.5]
        - rapidjsonr           [* -> 1.2.0]
        - rappdirs             [* -> 0.3.3]
        - raster               [* -> 3.6-26]
        - rcmdcheck            [* -> 1.4.0]
        - RColorBrewer         [* -> 1.1-3]
        - Rcpp                 [* -> 1.0.12]
        - readr                [* -> 2.1.4]
        - readxl               [* -> 1.4.2]
        - rematch              [* -> 1.0.1]
        - rematch2             [* -> 2.1.2]
        - remotes              [* -> 2.4.2.1]
        - renv                 [* -> 1.0.7]
        - reprex               [* -> 2.0.2]
        - rlang                [* -> 1.1.3]
        - rlist                [* -> 0.4.6.2]
        - rmarkdown            [* -> 2.26]
        - roxygen2             [* -> 7.2.3]
        - rprojroot            [* -> 2.0.4]
        - rstudioapi           [* -> 0.15.0]
        - rversions            [* -> 2.1.2]
        - rvest                [* -> 1.0.3]
        - s2                   [* -> 1.1.6]
        - sass                 [* -> 0.4.9]
        - scales               [* -> 1.3.0]
        - selectr              [* -> 0.4-2]
        - sessioninfo          [* -> 1.2.2]
        - sf                   [* -> 1.0-14]
        - sfheaders            [* -> 0.4.4]
        - shiny                [* -> 1.7.4]
        - shinycssloaders      [* -> 1.0.0]
        - shinydashboard       [* -> 0.7.2]
        - shinyWidgets         [* -> 0.8.6]
        - snakecase            [* -> 0.11.1]
        - sourcetools          [* -> 0.1.7-1]
        - sp                   [* -> 2.1-4]
        - spData               [* -> 2.3.0]
        - stars                [* -> 0.6-4]
        - stringi              [* -> 1.7.12]
        - stringr              [* -> 1.5.0]
        - sys                  [* -> 3.4.1]
        - systemfonts          [* -> 1.0.4]
        - terra                [* -> 1.7-55]
        - testthat             [* -> 3.2.1.1]
        - textshaping          [* -> 0.3.6]
        - tibble               [* -> 3.2.1]
        - tidyr                [* -> 1.3.0]
        - tidyselect           [* -> 1.2.1]
        - tidyverse            [* -> 2.0.0]
        - timechange           [* -> 0.2.0]
        - tinytex              [* -> 0.50]
        - tzdb                 [* -> 0.3.0]
        - units                [* -> 0.8-5]
        - urlchecker           [* -> 1.0.1]
        - usethis              [* -> 2.1.6]
        - utf8                 [* -> 1.2.4]
        - uuid                 [* -> 1.1-0]
        - vctrs                [* -> 0.6.5]
        - viridisLite          [* -> 0.4.2]
        - vroom                [* -> 1.6.3]
        - waldo                [* -> 0.5.2]
        - whisker              [* -> 0.4.1]
        - widgetframe          [* -> 0.3.1]
        - withr                [* -> 3.0.0]
        - wk                   [* -> 0.9.1]
        - xfun                 [* -> 0.43]
        - XML                  [* -> 3.99-0.16.1]
        - xml2                 [* -> 1.3.4]
        - xopen                [* -> 1.0.0]
        - xtable               [* -> 1.8-4]
        - yaml                 [* -> 2.3.8]
        - zip                  [* -> 2.2.2]
        - zoo                  [* -> 1.8-12]

**DATA-SPECIFIC INFORMATION FOR:**

These are the datasets associated with this submission. They are the
tables and spatial data needed for the California Schools Climate
Hazards Dashboard.

1.  extreme_heat.csv: *contains the total number of projected extreme
    heat days for every California public school between 2006-2064*

    1.  number of variables: 7

    2.  number of cases/rows: 1180944

    3.  relevant variables:

        1.  CDSCode: *unique school identifier*

        2.  year: *year from 2006-2064*

        3.  total: *total number of extreme heat days in a given year
            for a given RCP scenario*

        4.  scenario: *Representative Concentration Pathway (RCP),
            either 4.5 or 8.5*

        5.  DistrictNa: *school district*

        6.  SchoolName: *school name*

    4.  missing data code: NA

2.  extreme_precipitation.csv: *contains the total number of projected
    extreme precipitation days for every California public school
    between 2006-2064*

    1.  number of variables: 9

    2.  number of cases/rows: 1180944

    3.  relevant variables:

        1.  CDSCode: *unique school identifier*

        2.  year: *year from 2006-2064*

        3.  total: *total number of extreme precipitation days in a
            given year for a given RCP scenario*

        4.  scenario: *Representative Concentration Pathway (RCP),
            either 4.5 or 8.5*

        5.  City: *city that the school is in*

        6.  DistrictNa: *school district*

        7.  SchoolName: *school name*

    4.  missing data code: NA

3.  schools_hazards_intervals.csv: *contains a single number summary of
    each hazard for each school, the normalized score from 0-5 of each
    hazard for each school, and the total score*

    1.  number of variables: 13

    2.  number of cases/rows: 10008

    3.  relevant variables:

        1.  CDSCode: *unique school identifier*

        2.  SchoolName: *school name*

        3.  DistrictNa: *school district*

        4.  slr_percent: *percentage of school area affected by sea
            level rise and a 100-year coastal storm*

        5.  FEMA_percent: *percentage of school area within a high risk
            flood zone*

        6.  schools_heat: *total number of extreme heat days between
            2025-2030*

        7.  schools_precip: *total number of extreme precipitation days
            between 2025-2030*

        8.  whp: *mean wildfire hazard potential score from 0-5*

        9.  flood_score: *FEMA_percent normalized from 0-5*

        10. slr_score: *slr_percent normalized from 0-5*

        11. heat_score: *schools_heat normalized from 0-5*

        12. precip_score: *schools_precip normalized from 0-5*

        13. hazard_score: *the total hazard score, or the sum of whp,
            flood_score, slr_score, heat_score, and precip_score*

    4.  missing data code: NA

4.  ca_slr_simple.shp: *simplified polygons describing flooding extent
    under 0.8 feet of sea level rise (projected 2050 sea levels) and a
    100-year coastal storm for California*

    1.  number of variables: 2

    2.  number of features: 82

    3.  variable list: FID, geometry

    4.  missing data code: NA

    5.  coordinate reference system: EPSG 4326

5.  ca_slr_2000_simple.shp: *simplified polygons describing flooding
    extent with no sea level rise (2000 sea levels) and a 100-year
    coastal storm for California*

    1.  number of variables: 2

    2.  number of features: 95

    3.  variable list: FID, geometry

    4.  missing data code: NA

    5.  coordinate reference system: EPSG 4326

6.  whp_reclass2012.tif: *a raster of wildfire hazard potential for
    California from 2012 reclassified to very low, low, moderate, high,
    and very high*

    1.  raster file format: GeoTIFF

    2.  raster dimensions: 3871 rows, 3334 columns

    3.  spatial resolution: 270 meters

    4.  coordinate reference system: EPSG 3857

    5.  missing data code: NA

7.  whp_reclass.tif: *a raster of wildfire hazard potential for
    California from 2023 reclassified to very low, low, moderate, high,
    and very high*

    1.  raster file format: GeoTIFF

    2.  raster dimensions: 3871 rows, 3334 columns

    3.  spatial resolution: 270 meters

    4.  coordinate reference system: EPSG 3857

    5.  missing data code: NA

8.  fema_reclass_simple.shp: *simplified polygons describing flood risk
    for California reclassified to high risk, moderate to low risk, and
    undetermined risk*

    1.  number of variables: 24

    2.  number of features: 57136

    3.  variable list: DFIRM_I, VERSION, FLD_AR\_, STUDY_T, FLD_ZON,
        ZONE_SU, SFHA_TF, STATIC\_, V_DATUM, DEPTH, LEN_UNI, VELOCIT,
        VEL_UNI, AR_REVE, AR_SUBT, BFE_REV, DEP_REV, DUAL_ZO, SOURCE\_,
        GFID, SHAPE_L, SHAPE_A, fld_risk, geometry

    4.  missing data codes: NA

    5.  coordinate reference system: EPSG 4269
