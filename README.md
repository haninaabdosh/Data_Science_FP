Got it — below is your **fixed version**, but now the **Data Sources section is aligned exactly with what is written in your report** (same agencies, same wording level, no invented sources like Harvard Dataverse).

This is **GitHub-appropriate**, **academically safe**, and matches your **Methodology → Data Acquisition** section.

You can paste this directly into `README.md`.

---

# Impact of Prenatal Noise Pollution on Birth Weight

## Project Overview

This research project investigates the relationship between **prenatal exposure to transportation-related noise pollution** and **birth weight outcomes** at the community level. By integrating environmental, maternal health, and socioeconomic datasets, the study evaluates whether higher average noise exposure during pregnancy is associated with increased low birth weight (LBW) rates after accounting for key confounding factors.

The project follows a **standard end-to-end data science pipeline**, including data acquisition, preprocessing, exploratory data analysis, feature selection, regression modeling, and evaluation.

---

## Data Sources

All datasets used in this project are **publicly available** and were harmonized to the **ZIP-code level** for analysis.

### Primary Datasets

**Birth and Maternal Health Data**

* **Source:** California Department of Public Health (Cal-ViDa)
* **Description:** ZIP-code–level birth outcome data used to construct low birth weight rates, along with maternal indicators including education level, prenatal care timing, and maternal age. Data were aggregated across the 2018–2022 period to stabilize rates for smaller populations.

**Socioeconomic and Demographic Data**

* **Source:** American Community Survey (ACS), U.S. Census Bureau
* **Description:** Census-derived socioeconomic and demographic indicators, including income, race/ethnicity composition, insurance coverage, and housing characteristics. Data were processed and normalized to proportions for comparability across ZIP codes.

**Environmental Justice Indicators**

* **Source:** U.S. Environmental Protection Agency (EPA) – EJScreen
* **Description:** Census tract–level environmental justice indicators, including environmental exposure variables. These data were spatially aggregated to ZIP codes using weighted crosswalks.

**Transportation Noise Data**

* **Source:** U.S. Department of Transportation (DOT)
* **Description:** Modeled transportation noise exposure data for road, rail, and aviation sources provided in raster (GeoTIFF) format. Noise values were extracted and averaged within ZIP code boundaries to estimate mean noise exposure in decibels.

**Social Vulnerability Index (SVI)**

* **Source:** Centers for Disease Control and Prevention (CDC) / Agency for Toxic Substances and Disease Registry (ATSDR)
* **Description:** Census tract–level social vulnerability indicators measuring socioeconomic status, household composition, minority status, and housing and transportation factors.

**Geographic Crosswalk and Boundary Data**

* **Source:**

  * U.S. Department of Housing and Urban Development (HUD) – ZIP–Census Tract Crosswalk
  * U.S. Census Bureau – ZIP Code Tabulation Area (ZCTA) shapefiles
* **Description:** Geographic reference files used to spatially align census tract–level datasets with ZIP-code–level birth and maternal health data.

## Data Usage and Ethical Considerations
All analyses are conducted using aggregated, de-identified data. No personally identifiable information is accessed or disclosed.





