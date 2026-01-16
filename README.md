# Impact of Prenatal Noise Pollution on Birth Weight

## Project Overview

This research project investigates the relationship between **prenatal exposure to transportation-related noise pollution** and **birth weight outcomes** at the community level. By integrating environmental, maternal health, and socioeconomic datasets, the study evaluates whether higher average noise exposure during pregnancy is associated with increased low birth weight (LBW) rates after accounting for key confounding factors.

---

## Data Sources

All datasets used in this project are **publicly available**.

### Primary Datasets

**Birth and Maternal Health Data**

* **Source:** California Department of Public Health (Cal-ViDa)
* **Description:** ZIP-code–level birth outcome data used to construct low birth weight rates, along with maternal indicators including education level, prenatal care timing, and maternal age. Data were aggregated across the 2018–2022 period to stabilize rates for smaller populations.
* * **Link**: https://cal-vida.cdph.ca.gov/VSQWeb/ReportBuilder/BirthReport

**Socioeconomic and Demographic Data**

* **Source:** American Community Survey (ACS), U.S. Census Bureau
* **Description:** Census-derived socioeconomic and demographic indicators, including income, race/ethnicity composition, insurance coverage, and housing characteristics. Data were processed and normalized to proportions for comparability across ZIP codes.
* **Link**: https://data.census.gov/

**Environmental Justice Indicators**

* **Source:** U.S. Environmental Protection Agency (EPA) – EJScreen
* **Description:** Census tract–level environmental justice indicators, including environmental exposure variables. These data were spatially aggregated to ZIP codes using weighted crosswalks.
* **Link**: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/JISNPL
**Transportation Noise Data**

* **Source:** U.S. Department of Transportation (DOT)
* **Description:** Modeled transportation noise exposure data for road, rail, and aviation sources provided in raster (GeoTIFF) format. Noise values were extracted and averaged within ZIP code boundaries to estimate mean noise exposure in decibels.
* **Link**: 
**Social Vulnerability Index (SVI)**

* **Source:** Centers for Disease Control and Prevention (CDC) / Agency for Toxic Substances and Disease Registry (ATSDR)
* **Description:** Census tract–level social vulnerability indicators measuring socioeconomic status, household composition, minority status, and housing and transportation factors.
* **Link**: https://www.atsdr.cdc.gov/place-health/php/svi/svi-data-documentation-download.html
**Geographic Crosswalk and Boundary Data**

* **Source:**

  * U.S. Department of Housing and Urban Development (HUD) – ZIP–Census Tract Crosswalk
  * U.S. Census Bureau – ZIP Code Tabulation Area (ZCTA) shapefiles
* **Description:** Geographic reference files used to spatially align census tract–level datasets with ZIP-code–level birth and maternal health data.
* **Link**: https://www.huduser.gov/portal/datasets/usps_crosswalk.html
## Data Usage and Ethical Considerations
All analyses are conducted using aggregated, de-identified data. No personally identifiable information is accessed or disclosed.





