# Correlation or Causation: The $109 Airfare Resurgence

> **SusVizz Analytical Series** | Published: 2026-09-08  
> **Topic:** Investigating candidate cost drivers and spurious indicators behind the resurgence of U.S. domestic airfares ($366 to $475).  
> **Visual Deliverables:** [View SusVizz Publications](https://instagram.com/susvizz)

---

## 1. The Locked Factsheet

All visual slides, motion graphics, and captions strictly adhere to these canonical figures:

| Metric Component | Canonical Value | Empirical Context / Benchmark |
| :--- | :--- | :--- |
| **Baseline Airfare Trough** | **$366.02 (May 2025)** | Post-pandemic normalization baseline (BLS CPI = 242.546) |
| **Current Airfare Peak** | **$475.06 (July 2026)** | Surging summer travel peak (BLS CPI = 314.733) |
| **Net Airfare Delta** | **+$109.04 (+29.8%)** | Net consumer price shock across 14 consecutive months |
| **Top Structural Correlation** | **Footwear Import Tariff ($r = +0.887$)** | Spurious cross-sector correlation outpacing traditional cost drivers |
| **Jet Fuel Decoupling** | **$r = -0.063$** | Complete statistical detachment between fuel refinery prices and airfares |

---

## 2. Dataset Catalog & Clean CSV Tables

All data tables below are clean, machine-readable, and formatted according to RFC-4180 standards. Click any table to inspect and search directly on GitHub:

### 📊 [airline_net_income_indexed.csv](airline_net_income_indexed.csv)
**Major U.S. Airline Quarterly Operating Net Income**  
> **Visual Deliverable:** Slide 4: Airline Operating Profits vs. Airfare Surge  
> **Source(s):** [5]  
> **Description:** Quarterly net income and indexed performance for Delta, United, American, and Southwest Airlines during the airfare surge.  
*5 records, 16 columns.*

| Column | Type | Sample Preview |
| :--- | :--- | :--- |
| `quarter` | String | `2025Q2` |
| `fare_national_usd` | Float | `369.1366666666666` |
| `quarter_str` | String | `2025Q2` |
| `quarter_end_date` | String | `2025-06-30` |
| `DAL` | Float | `2130.0` |
| `UAL` | Float | `973.0` |
| `AAL` | Float | `599.0` |
| `LUV` | Float | `213.0` |
| `TOTAL` | Float | `3915.0` |
| `airfare_index` | Float | `100.0` |
| `DAL_index` | Float | `100.0` |
| `UAL_index` | Float | `100.0` |
| `AAL_index` | Float | `100.0` |
| `LUV_index` | Float | `100.0` |
| `TOTAL_index` | Float | `100.0` |
| `Citation` | String | `[5]` |

### 📊 [flight_correlations_10slides.csv](flight_correlations_10slides.csv)
**Monthly U.S. Domestic Airfares & Candidate Cost Drivers (2025–2026)**  
> **Visual Deliverable:** Slides 1–3 & 5–10: Time Series & Candidate Cost Driver Testing  
> **Source(s):** [1], [2], [3], [4], [6], [7], [8], [9], [10], [11], [12], [13]  
> **Description:** 15-month monthly time series tracking airfares alongside jet fuel, crude oil, passenger traffic, and cross-sector indices.  
*15 records, 27 columns.*

| Column | Type | Sample Preview |
| :--- | :--- | :--- |
| `date` | String | `2025-04-01` |
| `airfare_cpi` | Float | `247.922` |
| `jet_fuel_gal` | Float | `1.975714285714285` |
| `whole_milk_gal` | Float | `4.074` |
| `footwear_cpi` | Float | `144.751` |
| `wti_crude_bbl` | Float | `63.54` |
| `mens_suits_cpi` | Float | `275.454` |
| `toys_games_cpi` | Float | `31.917` |
| `passenger_load_factor` | Float | `80.9` |
| `airfare_cpi_indexed` | Float | `118.27` |
| `jet_fuel_gal_indexed` | Float | `139.09` |
| `whole_milk_gal_indexed` | Float | `117.47` |
| `footwear_cpi_indexed` | Float | `107.76` |
| `wti_crude_bbl_indexed` | Float | `122.19` |
| `mens_suits_cpi_indexed` | Float | `123.21` |
| `toys_games_cpi_indexed` | Float | `86.98` |
| `passenger_load_factor_indexed` | Float | `160.83` |
| `import_prices_nonpetro` | Float | `126.3` |
| `fare_national_usd` | Float | `374.13` |
| `fare_nyla_usd` | Float | `414.12` |
| `dal_stock_usd` | Float | `40.91469955444336` |
| `enplanements_millions` | Float | `69.614` |
| `cocoa_usd_mt` | Float | `8132.218491705632` |
| `used_cars_cpi` | Float | `184.8` |
| `used_cars_usd` | Float | `25657.72` |
| `footwear_usd` | Float | `140.45` |
| `Citation` | String | `[1], [2], [3], [4], [6], [7], [8], ` |

---

## 3. Chicago Author-Date Citations

- [1] U.S. Bureau of Labor Statistics (BLS). 2026. "Consumer Price Index for All Urban Consumers: Airline Fares in U.S. City Average (CUSR0000SETG01)." FRED.
- [2] U.S. Bureau of Transportation Statistics (BTS). 2026. "National Average Domestic Air Fares (Table 6)." U.S. Department of Transportation.
- [3] U.S. Energy Information Administration (EIA). 2026. "U.S. Gulf Coast Kerosene-Type Jet Fuel Spot Price FOB (EER_EPJK_PF4_RGC_DPG)." FRED.
- [4] U.S. Energy Information Administration (EIA). 2026. "Crude Oil Prices: West Texas Intermediate (WTI) - Cushing, Oklahoma (DCOILWTICO)." FRED.
- [5] U.S. SEC & BTS TranStats. 2026. "Form 10-Q Quarterly Financial Filings & Form 41 Financial Data: Delta Air Lines, United Airlines Holdings, American Airlines Group, Southwest Airlines." SEC EDGAR & BTS TranStats.
- [6] U.S. Bureau of Transportation Statistics (BTS). 2026. "T-100 Domestic Scheduled Passenger Enplanements & Load Factor." TranStats Database.
- [7] S&P Global / New York Stock Exchange. 2026. "Delta Air Lines Inc. (DAL) Historical Daily/Monthly Adjusted Closing Stock Prices." S&P Capital IQ.
- [8] World Bank Group. 2026. "Commodity Price Data (The Pink Sheet): Cocoa Beans ($/metric ton, PCOCOUSDM)." World Bank Group Development Prospects Group.
- [9] U.S. Bureau of Labor Statistics (BLS). 2026. "Consumer Price Index for All Urban Consumers: Used Cars and Trucks in U.S. City Average (CUSR0000SETA02)." FRED.
- [10] U.S. Bureau of Labor Statistics (BLS). 2026. "Consumer Price Index for All Urban Consumers: Footwear in U.S. City Average (CUSR0000SEAE)." FRED.
- [11] U.S. Bureau of Labor Statistics (BLS). 2026. "Import Price Index (End Use): All Imports Excluding Petroleum (IREXPET)." FRED.
- [12] Cox Automotive. 2026. "Manheim Used Vehicle Value Index & National Average Used Listing Price Benchmark ($25,500 May 2025 Baseline)."
- [13] Circana (NPD Group). 2026. "U.S. Athletic Footwear Market Retail Trends & Average Selling Price Benchmark ($140 May 2025 Baseline)."

---

## License & Attribution

All cleaned datasets are published under the [Creative Commons Attribution 4.0 International (CC-BY-4.0)](../LICENSE) license.  
**Attribution:** SusVizz (`@susvizz`).
