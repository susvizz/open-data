# US–Canada Trade War & Heavy Energy Reality

> **SusVizz Analytical Series** | Published: 2026-08-26  
> **Topic:** Empirical analysis of proposed cross-border tariffs, heavy crude trade flows, and PADD 2 refinery infrastructure lock-in.  
> **Visual Deliverables:** [View SusVizz Publications](https://instagram.com/susvizz)

---

## 1. The Locked Factsheet

All visual slides, motion graphics, and captions strictly adhere to these canonical figures:

| Metric Component | Canonical Value | Empirical Context / Benchmark |
| :--- | :--- | :--- |
| **Proposed Headline Tariff** | **25%** | Headline policy announcement on all cross-border imports |
| **Actual Historical Effective Tariff** | **0.0% to 0.2%** | Decades-long NAFTA/USMCA duty-free baseline |
| **Crude Oil Energy Flow** | **4.3 Million Barrels/Day** | Canadian heavy crude supplying 61% of total U.S. crude imports |
| **Midwest (PADD 2) Refinery Lock-In** | **70% reliance** | Refineries chemically engineered for Canadian Western Canadian Select (WCS) |

---

## 2. Dataset Catalog & Clean CSV Tables

All data tables below are clean, machine-readable, and formatted according to RFC-4180 standards. Click any table to inspect and search directly on GitHub:

### 📊 [crude_imports.csv](crude_imports.csv)
**U.S. Crude Oil Imports by Country of Origin**  
> **Visual Deliverable:** Slide 3: U.S. Crude Import Reliance  
> **Source(s):** [6]  
> **Description:** Volume (Million Barrels/Day) and percentage share of U.S. crude imports supplied by Canada vs other global producers.  
*8 records, 6 columns.*

| Column | Type | Sample Preview |
| :--- | :--- | :--- |
| `Country_of_Origin` | String | `Canada` |
| `Volume_Million_Barrels_Per_Day` | Float | `4.3` |
| `Share_of_Total_US_Imports_Pct` | Float | `63.2` |
| `Annual_Value_USD_Billions` | Float | `115.2` |
| `Data_Status` | String | `Hard Data` |
| `Source` | String | `[6]` |

### 📊 [historical_tariffs.csv](historical_tariffs.csv)
**Effective vs. Punitive Tariff Rates (2016–2026)**  
> **Visual Deliverable:** Slide 1: The Effective Tariff Reality  
> **Source(s):** [1], [2], [3]  
> **Description:** Historical customs duties collected vs total merchandise imports under NAFTA/USMCA vs punitive announcements.  
*11 records, 7 columns.*

| Column | Type | Sample Preview |
| :--- | :--- | :--- |
| `Year` | Integer | `2016` |
| `Weighted_Mean_Tariff_All_Goods_Pct` | Float | `0.28` |
| `Headline_Punitive_Tariff_Rate_Pct` | Float | `0.0` |
| `Policy_Era` | String | `NAFTA Duty-Free Baseline` |
| `Data_Status` | String | `Hard Data` |
| `Methodology` | String | `Official USITC DataWeb & CBP custom` |
| `Source` | String | `[1]` |

### 📊 [refinery_reliance.csv](refinery_reliance.csv)
**Midwest (PADD 2) Refinery & Cross-Border Grid Lock-In**  
> **Visual Deliverable:** Slide 4: Midwest Heavy Crude Infrastructure Lock-In  
> **Source(s):** [6], [7]  
> **Description:** Refinery coking capacity reliance on heavy Western Canadian Select and regional electric grid interconnections.  
*4 records, 6 columns.*

| Column | Type | Sample Preview |
| :--- | :--- | :--- |
| `Region_or_Grid_Node` | String | `Midwest (PADD II) Refineries - Heav` |
| `Share_or_Capacity_Pct` | Float | `72.0` |
| `Physical_Metric` | String | `2.8 Million bpd heavy coking capaci` |
| `Strategic_Implication` | String | `Hardwired coking units chemically r` |
| `Data_Status` | String | `Hard Data` |
| `Source` | String | `[6]` |

### 📊 [trade_breakdown.csv](trade_breakdown.csv)
**Cross-Border Trade Flows & Sector Vulnerability**  
> **Visual Deliverable:** Slide 2: The Cross-Border Trade Breakdown  
> **Source(s):** [2], [3], [4], [5]  
> **Description:** Bilateral trade values (USD Billions), targeted tariff exposure, and strategic supply chain exemptions.  
*10 records, 8 columns.*

| Column | Type | Sample Preview |
| :--- | :--- | :--- |
| `Category` | String | `Total Exports to US` |
| `Total_Export_Value_USD_Billions` | Float | `420.5` |
| `Headline_Tariff_Rate_Pct` | String | `5.3% (Weighted)` |
| `Percentage_of_Sector_Targeted` | String | `15.2%` |
| `Impacted_Value_USD_Billions` | Float | `64.1` |
| `Strategic_Status` | String | `15.2% Impacted / 84.8% Untouched` |
| `Data_Status` | String | `Hard Data` |
| `Source` | String | `[4]` |

---

## 3. Chicago Author-Date Citations

- [1] U.S. International Trade Commission (USITC). 2024. "U.S. Trade and Customs Duties Collected on Canadian Merchandise (2016–2024)." USITC DataWeb. Washington, D.C.: USITC.
- [2] Office of the United States Trade Representative (USTR). 2025. "Executive Actions and Section 232 Automotive Tariff Adjustments." Washington, D.C.: Executive Office of the President.
- [3] Office of the United States Trade Representative (USTR). 2026. "Notice of Action in Section 338 Investigation: Canada Targeted Goods." Washington, D.C.: Executive Office of the President.
- [4] U.S. Census Bureau. 2026. "U.S. Trade in Goods with Canada: Foreign Trade Division Statistics." Suitland, MD: U.S. Department of Commerce.
- [5] Global Affairs Canada. 2026. "Notice of Retaliatory Surtaxes on Imported U.S. Goods." Ottawa: Department of Foreign Affairs, Trade and Development.
- [6] U.S. Energy Information Administration (EIA). 2026. "Petroleum Supply Monthly & Refinery Capacity Report." Washington, D.C.: U.S. Department of Energy.
- [7] Canada Energy Regulator (CER). 2026. "Canada's Energy Future and Cross-Border Electricity Trade Review." Calgary, AB: Government of Canada.

---

## License & Attribution

All cleaned datasets are published under the [Creative Commons Attribution 4.0 International (CC-BY-4.0)](../LICENSE) license.  
**Attribution:** SusVizz (`@susvizz`).
