# NYC Prostate Cancer and SDOH

This repository contains the code and data required to reproduce the analyses presented in the paper *Prostate Cancer Incidence and Social Determinants of Health in New York City: A Cancer Registry Analysis*

## Data Sources
All data were obtained from publicly available state and federal sources and were archived in Zenodo. The raw data can be found at these sources:

[***CSV Files***](https://github.com/SPhilogene/JREHD-Prostate-SDOH/tree/main/CSV%20Files)

**Cancer Incidence Surveillance Data**

Data analyzed in this study were sourced from existing public data, which are openly available from these sources:
Data on Cancer Incidence by Census Tract, 2013-2017 was obtained from the New York State Cancer Registry. Accessible via Wayback Machine at: https://web.archive.org/web/20230220064015/https://www.health.ny.gov/statistics/cancer/registry/pdf/censustract.pdf (Accessed: March 4, 2025)

**Demographic Data**

American Community Survey 5-Year Data for 2015 was accessed using the web-based API. Users must request an access key to extract data from the [Census API](https://www.census.gov/data/developers.html). Variables were collected from 30 the following data tables:

| Table ID | Table Title |
| ------------- | ------------- |
| B01001[A-I] | Sex by Age |
| B03003 | Hispanic or Latino Origin |
| B04006 | People Reporting Ancestry |
| B05002 | Place of Birth by Nativity and Citizenship Status |
| B05006 | Place of Birth for the Foreign-Born Population in the United States |
| B05007 | Place of Birth by Year of Entry by Citizenship Status for the Foreign-Born Population |
| B06003 | Place of Birth by Sex in the United States |
| B06008 | Place of Birth by Marital Status in the United States |
| B07003 | Geographical Mobility in the Past Year by Sex for Current Residence in the United States |
| B08007 | Sex of Workers by Place of Work--State and County Level |
| B12001 | Sex by Marital Status for the Population 15 Years and Over |
| B15001 | Sex by Age by Educational Attainment for the Population 18 Years and Over |
| B16001 | Language Spoken at Home by Ability to Speak English for the Population 5 Years and Over |
| B17001[A-I] | Poverty Status in the Past 12 Months by Sex by Age |
| B19001[A-I] | Household Income in the Past 12 Months (In 2015 Inflation-Adjusted Dollars) |
| B25040 | House Heating Fuel |
| B27001 | Health Insurance Coverage Status by Sex by Age |
| C24010[A-I] | Sex by Occupation for the Civilian Employed Population 16 Years and Over |
| C24030 | Sex by Industry for the Civilian Employed Population 16 Years and Over |
| C27004 | Employer-Based Health Insurance by Sex by Age |
| DP05 | ACS Demographic and Housing Estimate |
| S0601 | Selected Characteristics of the Total and Native Populations in the United States |
| S0701 | Geographic Mobility by Selected Characteristics in the United States |
| S1501 | Educational Attainment |
| S1603 | Characteristics of People by Language Spoken at Home |
| S1701 | Poverty Status in the Past 12 Months |
| S2201 | Food Stamps/Supplemental Nutrition Assistance Program (SNAP) |
| S2403 | Industry by Sex for the Civilian Employed Population 16 Years and Over |
| S2501 | Occupancy Characteristics |
| S2701 | Selected Characteristics of Health Insurance Coverage in the United States |

**Health Data**

Health outcomes data was obtained from the Center for Disease Control and Prevention [PLACES: Local Data for Better Health](https://www.cdc.gov/places/tools/data-portal.html) online data repository .

[***Shapefiles***](https://github.com/SPhilogene/JREHD-Prostate-SDOH/tree/main/Shapefiles)

**Environmental Data**

Shapefiles for landfills and remediation sites were retrieved from the NYS GIS Clearinghouse:
[Active Landfills](https://data.gis.ny.gov/datasets/nysdec::active-landfills/about), [Inactive Solid Waste Landfills](https://data.gis.ny.gov/datasets/db9225d3962c4f8891fb72231b752ec5_31/about), and [Remediation Sites](https://data.gis.ny.gov/datasets/nysdec::remediation-sites/about).

Air quality information including emissions data, ambient concentrations and health-effect results were obtained through the US Environmental Protection Agency’s [2017 Air Toxics Screening Assessment](https://www.epa.gov/AirToxScreen/2017-airtoxscreen-assessment-results). State Summary files for New York State available in two parts in an MS Access ZIP file format.

**Miscellaneous**

Shapefiles for NYS census tracts—with GEOID provided for joins—were obtained from the US Census Bureau, Geography Division 2015 TIGER/Line Shapefiles for [Census Tracts](https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2015&layergroup=Census+Tracts).

Shapefiles for [New York City census tracts (clipped to shoreline)](https://www.nyc.gov/assets/planning/download/zip/data-maps/open-data/nyct2010_15d.zip) and Shapefiles for New York City [borough boundaries](https://www.nyc.gov/assets/planning/download/zip/data-maps/open-data/nybb_15d.zip) were obtained from the NYC Department of City Planning’s BYTES of the BIG APPLE™ Archive.

## Code

[Prostate Cancer & SDOH Python notebook](https://github.com/SPhilogene/JREHD-Prostate-SDOH/tree/main/Code)
