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

3\. Date of data collection or obtaining (single date, range,
approximate date) \<suggested format YYYY-MM-DD. If multiple data files,
list it accordingly\>:

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

**DATA & FILE OVERVIEW**

1\. File List: relevant files contained in the "casaschools" directory

1.  casaschools/extreme_heat: contains data on extreme heat imported
    from Cal-Adapt and prepared for plotting

    ├── heat_rcp45_2000_20064.csv

    ├── heat_rcp85_2000_20064.csv

    ├── rcp4.5_2006_2034.csv

    ├── rcp4.5_2035_2064.csv

    ├── rcp8.5_2006_2034.csv

    └── rcp8.5_2035_2064.csv

2.  casaschools/flooding: contains flood risk data imported from FEMA,
    as well as intermediate layers prepared for mapping

    ├── 06111C_20240219

    ├── S_FLD_HAZ_AR.shp

    ├── intermediate_layers

    ├── fema_high_union.shp

    ├── fema_reclass.shp

    ├── fema_reclass_simple.shp

    └── NFHL_06_20240401

    ├── NFHL_06_20240401.gdb

    └── NFHL_06_20240401_metadata.xml

3.  casaschools/precipitation: contains data on extreme heat imported
    from Cal-Adapt and prepared for plotting

    ├── century_all.csv

    ├── century_totals_combined45.csv

    ├── century_totals_combined.csv

    ├── curcentury45.csv

    ├── curcentury45_year.csv

    ├── curcentury85.csv

    ├── curcentury85_year.csv

    ├── historic85.csv

    ├── historic85_year.csv

    ├── midcentury45.csv

    ├── midcentury45_year.csv

    ├── midcentury85.csv

    ├── midcentury85_year.csv

    ├── schools_extreme_precip.csv

    ├── years_all.csv

    ├── years_all_zeros.csv

    ├── year_totals_combined45.csv

    └── year_totals_combined.csv

4.  casaschools/sea_level_rise: contains data for sea level rise for
    2000 and 2050 from CoSMoS as well as intermediate layers prepared
    for mapping

    ├── intermediate_layers

    │ ├── ca_slr_2000_simple.shp

    │ ├── ca_slr.shp

    │ ├── ca_slr_simple.shp

    └── raw_data

    ├── cosmos

    │ ├── 2000

    │ │ ├── county_los_angeles_slr000_w100_fldhazd.shp

    │ │ ├── county_monterey_slr000_w100_fldhazd.shp

    │ │ ├── county_orange_slr000_w100_fldhazd.shp

    │ │ ├── county_san_diego_slr000_w100_fldhazd.shp

    │ │ ├── county_santa_barbara_10n_slr000_w100_fldhazd.shp

    │ │ ├── county_santa_barbara_11n_slr000_w100_fldhazd.shp

    │ │ ├── county_ventura_slr000_w100_fldhazd.shp

    │ │ ├── mendocino_fldhazd_slr000_w100.shp

    │ │ ├── san_francisco_fldhazd_slr000_w100.shp

    │ │ ├── san_luis_obispo_fldhazd_slr000_w100.shp

    │ │ ├── san_mateo_fldhazd_slr000_w100.shp

    │ │ ├── santa_cruz_fldhazd_slr000_w100.shp

    │ │ ├── sfb_fldhazd_slr000_w100.shp

    │ │ ├── sonoma_fldhazd_slr000_w100.shp

    │ └── 2050

    │ ├── county_los_angeles_slr025_w100_fldhazd.shp

    │ ├── county_monterey_slr025_w100_fldhazd.shp

    │ ├── county_orange_slr025_w100_fldhazd.shp

    │ ├── county_san_diego_slr025_w100_fldhazd.shp

    │ ├── county_santa_barbara_10n_slr025_w100_fldhazd.shp

    │ ├── county_santa_barbara_11n_slr025_w100_fldhazd.shp

    │ ├── county_ventura_slr025_w100_fldhazd.shp

    │ ├── mendocino_fldhazd_slr025_w100.shp

    │ ├── san_francisco_fldhazd_slr025_w100.shp

    │ ├── san_luis_obispo_fldhazd_slr025_w100.shp

    │ ├── san_mateo_fldhazd_slr025_w100.shp

    │ ├── santa_cruz_fldhazd_slr025_w100.shp

    │ ├── sfb_fldhazd_slr025_w100.shp

    │ ├── sonoma_fldhazd_slr025_w100.shp

5.  casaschools/wildfire: contains data for wildfire hazard potential
    for 2012 and 2023 from the US Forest Service as well as intermediate
    layers prepared for mapping

    ├── intermediate_layers

    │ ├── whp_ca.tif

    │ ├── whp_reclass2012.tif

    │ └── whp_reclass.tif

    └── raw_data

    ├── whp_2012

    │ ├── w001001.adf

    └── whp2023_cls_conus.tif

6.  casaschools/hazard_summary: contains .csv files summarizing climate
    hazards for each school as well as a table joining the hazard
    summary scores for each school

    ├── individual_tables

    │ ├── flood_schools.csv

    │ ├── schools_extreme_heat.csv

    │ ├── schools_extreme_precip.csv

    │ ├── schools_slr.csv

    │ └── schools_whp.csv

    └── testing

    └── schools_hazards_intervals.csv

7.  casaschools/shiny_dashboard: contains additional data used in the R
    Shiny dashboard

    ├── extreme_heat

    │ ├── extreme_heat.csv

    └── precipitation

    ├── extreme_precipitation.csv

2\. Relationship between files, if important:

3\. Additional related data collected that was not included in the
current data package:

4\. Are there multiple versions of the dataset? \<A. If yes, name of
file(s) that was updated: i. Why was the file updated? ii. When was the
file updated?\>

**METHODOLOGICAL INFORMATION**

1\. Description of methods used for collection/generation of data:
\<Include links or references to publications or other documentation
containing experimental design or protocols used in data collection\>

2\. Methods for processing the data: \<describe how the submitted data
were generated from the raw or collected data\>

-   Data were processed in R Studio using Quarto Docs. Tabular data were
    cleaned and summarized over a smaller range of years. Spatial data
    were cleaned and reclassified to serve mapping purposes.

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

4\. Standards and calibration information, if appropriate:

5\. Environmental/experimental conditions:

6\. Describe any quality-assurance procedures performed on the data:

7\. People involved with sample collection, processing, analysis and/or
submission:

**DATA-SPECIFIC INFORMATION FOR:**

Final tables and spatial needed for the R Shiny dashboard

1.  extreme_heat.csv

    1.  number of variables: 7

    2.  number of cases/rows: 1180944

    3.  variable list: CDSCode, year, total, scenario, DistrictNa,
        SchoolName

    4.  missing data code: NA

    5.  specialized formats or other abbreviations used:

2.  extreme_precipitation.csv

    1.  number of variables: 9

    2.  number of cases/rows: 1180944

    3.  variable list: ...1, CDSCode, year, total, century, scenario,
        City, DistrictNa, SchoolName

    4.  missing data code: NA

    5.  specialized formats or other abbreviations used:

3.  schools_hazards_intervals.csv

    1.  number of variables: 13

    2.  number of cases/rows: 10008

    3.  variable list: CDSCode, SchoolName, DistrictNa, slr_percent,
        FEMA_percent, schools_heat, schools_precip, whp, flood_score,
        slr_score, heat_score, precip_score, hazard_score

    4.  missing data code: NA

    5.  specialized format or other abbreviations used:

4.  ca_slr_simple.shp

    1.  number of variables: 2

    2.  number of features: 82

    3.  variable list: FID, geometry

    4.  missing data code: NA

    5.  coordinate reference system: EPSG 4326

5.  whp_reclass2012.tif

    1.  raster file format: GeoTIFF

    2.  raster dimensions: 3871 rows, 3334 columns

    3.  spatial resolution: 270 meters

    4.  coordinate reference system: EPSG 3857

    5.  missing data code: NA

6.  whp_reclass.tif

    1.  raster file format: GeoTIFF

    2.  raster dimensions: 3871 rows, 3334 columns

    3.  spatial resolution: 270 meters

    4.  coordinate reference system: EPSG 3857

    5.  missing data code: NA

7.  fema_reclass_simple.shp

    1.  number of variables: 24

    2.  number of features: 57136

    3.  variable list: DFIRM_I, VERSION, FLD_AR\_, STUDY_T, FLD_ZON,
        ZONE_SU, SFHA_TF, STATIC\_, V_DATUM, DEPTH, LEN_UNI, VELOCIT,
        VEL_UNI, AR_REVE, AR_SUBT, BFE_REV, DEP_REV, DUAL_ZO, SOURCE\_,
        GFID, SHAPE_L, SHAPE_A, fld_risk, geometry

    4.  missing data codes: NA

    5.  coordinate reference system: EPSG 4269
