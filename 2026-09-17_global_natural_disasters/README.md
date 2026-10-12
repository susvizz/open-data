# The Global Disaster Paradox

> **SusVizz Analytical Series** | Published: 2026-09-17  
> **Topic:** Contrasting recorded disaster reporting spikes against a -98% collapse in human mortality and 25M annual weather displacements.  
> **Visual Deliverables:** [View SusVizz Publications](https://instagram.com/susvizz)

---

## 1. The Locked Factsheet

All visual slides, motion graphics, and captions strictly adhere to these canonical figures:

| Metric Component | Canonical Value | Empirical Context / Benchmark |
| :--- | :--- | :--- |
| **Historical Decadal Mortality (1920s)** | **53.8 deaths / 100k** | Global decadal natural disaster mortality rate |
| **Modern Decadal Mortality (2020s)** | **0.9 deaths / 100k** | -98.3% collapse in global human disaster death rates |
| **Recorded Events Count** | **Spike from 80/yr to 400+/yr** | Artifact of telecommunications and satellite observation maturity |
| **Modern Human Stake** | **25+ Million Displacements/yr** | Internal weather-driven displacements tracked by IDMC GRID |

---

## 2. Dataset Catalog & Clean CSV Tables

All data tables below are clean, machine-readable, and formatted according to RFC-4180 standards. Click any table to inspect and search directly on GitHub:

### 📊 [disaster_displacement_annual.csv](disaster_displacement_annual.csv)
**Annual Weather-Related Internal Displacements (2008–2024)**  
> **Visual Deliverable:** Slide 3: The Modern Threat: Internal Displacement  
> **Source(s):** [2]  
> **Description:** Annual global internal displacements driven by floods, storms, droughts, and extreme weather events.  
*16 records, 7 columns.*

| Column | Type | Sample Preview |
| :--- | :--- | :--- |
| `Year` | Integer | `2008` |
| `New_Displacements` | Integer | `38240123` |
| `New_Displacements_Millions` | Float | `38.240123` |
| `Rolling_3yr_Avg_Millions` | Float | `27.4872015` |
| `Cumulative_Displacements_Millions` | Float | `38.240123` |
| `Status` | String | `Hard Data` |
| `Source_Citation` | String | `[2]` |

### 📊 [disaster_economic_damages.csv](disaster_economic_damages.csv)
**Global Disaster Economic Losses (1980–2024)**  
> **Visual Deliverable:** Slide 4: Rising Economic Losses  
> **Source(s):** [1]  
> **Description:** Annual recorded direct economic damages (USD Billions) from natural disaster events globally.  
*45 records, 6 columns.*

| Column | Type | Sample Preview |
| :--- | :--- | :--- |
| `Year` | Integer | `1980` |
| `Damage_Nominal_USD` | Integer | `32395367064` |
| `Damage_Billions` | Float | `32.395367064` |
| `Rolling_5yr_Avg_Billions` | Float | `19.410002558` |
| `Status` | String | `Hard Data` |
| `Source_Citation` | String | `[1]` |

### 📊 [disaster_events_by_type.csv](disaster_events_by_type.csv)
**Recorded Global Disaster Events by Category (1900–2024)**  
> **Visual Deliverable:** Slide 1: Recorded Events & The Reporting Artifact  
> **Source(s):** [1]  
> **Description:** Annual recorded event counts illustrating telecommunications and satellite observation reporting maturity.  
*55 records, 17 columns.*

| Column | Type | Sample Preview |
| :--- | :--- | :--- |
| `Year` | Integer | `1970` |
| `Drought` | Integer | `9` |
| `Earthquake` | Integer | `12` |
| `Extreme temperature` | Integer | `0` |
| `Storms` | Integer | `25` |
| `Flood` | Integer | `31` |
| `Landslide` | Integer | `6` |
| `Wildfire` | Integer | `1` |
| `Total_Recorded_Events` | Integer | `84` |
| `Flood_5yr_avg` | Float | `20.33333333333333` |
| `Storms_5yr_avg` | Float | `25.33333333333333` |
| `Earthquake_5yr_avg` | Float | `8.333333333333334` |
| `Extreme temperature_5yr_avg` | Float | `1.0` |
| `Wildfire_5yr_avg` | Float | `0.3333333333333333` |
| `Drought_5yr_avg` | Float | `12.33333333333333` |
| `Status` | String | `Hard Data` |
| `Source_Citation` | String | `[1]` |

### 📊 [disaster_mortality_decadal.csv](disaster_mortality_decadal.csv)
**Global Decadal Disaster Mortality Rates (1920s–2020s)**  
> **Visual Deliverable:** Slide 2: The Mortality Paradox  
> **Source(s):** [1], [3]  
> **Description:** Global natural disaster human death rates per 100,000 population collapsing by -98.3% over a century.  
*11 records, 16 columns.*

| Column | Type | Sample Preview |
| :--- | :--- | :--- |
| `Entity` | String | `World` |
| `Code` | String | `OWID_WRL` |
| `Year` | Integer | `1920` |
| `Drought_Rate_Per_100k` | Float | `23.799612` |
| `Earthquake_Rate_Per_100k` | Float | `2.0205214` |
| `Volcanoes` | Float | `0.0007211489` |
| `Flood_Rate_Per_100k` | Float | `0.02155894` |
| `Landslides` | Float | `0.0016697131` |
| `Storm_Rate_Per_100k` | Float | `0.6217152` |
| `Wildfires` | Float | `0.00051550055` |
| `Extreme temperatures` | Float | `0.0` |
| `Death_Rate_Per_100k` | Float | `26.466314` |
| `Avg_Annual_Deaths` | Float | `523941.5` |
| `Decade_Label` | String | `1920s` |
| `Status` | String | `Hard Data` |
| `Source_Citation` | String | `[1], [3]` |

---

## 3. Chicago Author-Date Citations

- [1] Centre for Research on the Epidemiology of Disasters (CRED). 2025. "EM-DAT: The International Disaster Database." UCLouvain, Brussels. Accessed via Our World in Data.
- [2] Internal Displacement Monitoring Centre (IDMC). 2024. "Global Report on Internal Displacement (GRID 2024)." Geneva, Switzerland: IDMC.
- [3] United Nations Department of Economic and Social Affairs (UN DESA). 2024. "World Population Prospects 2024." New York: United Nations.

---

## License & Attribution

All cleaned datasets are published under the [Creative Commons Attribution 4.0 International (CC-BY-4.0)](../LICENSE) license.  
**Attribution:** SusVizz (`@susvizz`).
