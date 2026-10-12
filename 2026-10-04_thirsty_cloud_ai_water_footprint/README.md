# The Thirsty Cloud: The Secret Water Footprint of AI

> **SusVizz Analytical Series** | Published: 2026-10-04  
> **Topic:** Analyzing Big Tech data center water withdrawals, 10 GW mega-campus footprints, and 2035 grid water projections.  
> **Visual Deliverables:** [View SusVizz Publications](https://instagram.com/susvizz)

---

## 1. The Locked Factsheet

All visual slides, motion graphics, and captions strictly adhere to these canonical figures:

| Metric Component | Canonical Value | Empirical Context / Benchmark |
| :--- | :--- | :--- |
| **Baseline Hyperscaler Withdrawals** | **Google: 55.6B L; MSFT: 13.3B L; Meta: 5.6B L; AWS: 9.5B L** | Operational freshwater withdrawals across leading AI hyperscalers |
| **Single 10 GW Mega-Campus** | **1,033 Billion Liters / Year** | Direct on-site evaporative cooling (150B L) + off-site natural gas power cooling (883B L) |
| **Tangible Real-World Anchor** | **2,491,592 U.S. Households (~2.5M homes)** | Annual water demand of a single 10 GW AI data center campus |
| **Decoupling Dividend (2035)** | **67% water demand avoided** | 7.6 Trillion Liters avoided by deploying dry cooling and clean power |

---

## 2. Dataset Catalog & Clean CSV Tables

All data tables below are clean, machine-readable, and formatted according to RFC-4180 standards. Click any table to inspect and search directly on GitHub:

### 📊 [campus_scale_scenarios.csv](campus_scale_scenarios.csv)
**10 GW Mega-Campus Water Withdrawal Architecture**  
> **Visual Deliverable:** Slide 2: The Energy Supply for Data Centers Consumes Water Too  
> **Source(s):** [4], [5], [6], [16]  
> **Description:** Direct cooling vs. indirect thermoelectric power plant water withdrawal splits for a 10 GW AI facility.  
*3 records, 14 columns.*

| Column | Type | Sample Preview |
| :--- | :--- | :--- |
| `Campus Scale` | String | `10 GW Mega-Campus (Natural Gas)` |
| `IT Power Capacity (GW)` | Float | `10.0` |
| `Component` | String | `Direct On-Site Cooling` |
| `Metric Scope` | String | `Evaporative cooling towers (WUE 1.8` |
| `Water Intensity (L/kWh)` | Float | `1.8` |
| `Annual Water (Billion Liters)` | Float | `149.8` |
| `Annual Water (Billion Gallons)` | Float | `39.57` |
| `Daily Water (Million Liters)` | Float | `410.41` |
| `Daily Water (Million Gallons)` | Float | `108.42` |
| `Share of Total (%)` | Float | `14.5` |
| `Equivalent US Households (EPA 300 gal/day)` | Integer | `361391` |
| `Equivalent Irrigated Cropland (Acres)` | Integer | `80961` |
| `Status` | String | `Modeled Scenario` |
| `Citation` | String | `[4], [5], [6], [16]` |

### 📊 [hyperscaler_water_expanded.csv](hyperscaler_water_expanded.csv)
**Big Tech Hyperscaler Water Withdrawals (2017–2025)**  
> **Visual Deliverable:** Slide 1: The Big Tech Thirst Trap  
> **Source(s):** [2], [3], [9], [10]  
> **Description:** Operational freshwater withdrawals in Billion Liters per year across Alphabet, Microsoft, Meta, and AWS.  
*22 records, 9 columns.*

| Column | Type | Sample Preview |
| :--- | :--- | :--- |
| `Company` | String | `Google` |
| `Year` | Integer | `2019` |
| `Water Withdrawn (Billion L)` | Float | `15.1` |
| `Water Withdrawn (Million Gallons)` | Float | `3989.0` |
| `Water Consumed (Billion L)` | Float | `12.87` |
| `Reporting Metric` | String | `Global Operational Freshwater Withd` |
| `Pledge Status` | String | `Water Positive (120% Replenishment)` |
| `Status` | String | `Hard Data` |
| `Citation` | String | `[3]` |

### 📊 [industry_water_comparison.csv](industry_water_comparison.csv)
**U.S. Industrial Water Consumption Benchmarks**  
> **Visual Deliverable:** Slide 3: Where U.S. Freshwater Actually Goes  
> **Source(s):** [5], [6], [11], [12], [13], [17]  
> **Description:** Freshwater withdrawal comparison between AI data centers, beverage bottling, golf courses, and agriculture.  
*9 records, 9 columns.*

| Column | Type | Sample Preview |
| :--- | :--- | :--- |
| `Sector / Industry` | String | `Thermoelectric Power` |
| `Subsector / Application` | String | `National electric utility cooling` |
| `Annual Water Withdrawal (Billion Gallons)` | Integer | `48500` |
| `Annual Water Withdrawal (Billion Liters)` | Integer | `183590` |
| `Daily Withdrawal (Billion Gallons/day)` | Float | `132.88` |
| `Share of US Total (%)` | Float | `41.3` |
| `5-Year Growth Trend (2020-2025)` | String | `-4.5% (Coal retirements)` |
| `Status` | String | `Hard Data` |
| `Citation` | String | `[11]` |

### 📊 [top10_us_mega_campuses.csv](top10_us_mega_campuses.csv)
**Top 10 Proposed U.S. AI Mega-Campuses**  
> **Visual Deliverable:** Slide 4: The Geography of Data Center Thirst  
> **Source(s):** [5], [14], [15], [16]  
> **Description:** Geographic locations, planned IT capacity (GW), and watershed stress indices for major planned AI campuses.  
*10 records, 15 columns.*

| Column | Type | Sample Preview |
| :--- | :--- | :--- |
| `Rank` | Integer | `1` |
| `Project Name` | String | `Hypergrid Campus` |
| `Location` | String | `Amarillo, TX` |
| `State` | String | `TX` |
| `Planned Capacity (GW)` | Float | `11.0` |
| `Developer` | String | `Fermi America` |
| `Energy Source` | String | `Gas, Nuclear, Solar` |
| `Water Basin` | String | `Ogallala Aquifer / Canadian River` |
| `Water Stress Level` | String | `Extremely High` |
| `Est Annual Consumption (Billion L)` | Float | `112.5` |
| `Est Annual Withdrawal (Billion L)` | Float | `140.6` |
| `US Households Equiv` | Integer | `271412` |
| `Irrigated Farmland (Acres)` | Integer | `45600` |
| `Status` | String | `Public Project Proposal` |
| `Citation` | String | `[5], [14], [15], [16]` |

### 📊 [us_water_projections_2035.csv](us_water_projections_2035.csv)
**U.S. Data Center Water Projections (2020–2035)**  
> **Visual Deliverable:** Slide 5: The 2035 Decoupling Dilemma  
> **Source(s):** [6], [16], [17]  
> **Description:** National water demand projections across Status Quo, Clean Cooling, and Clean Cooling + Clean Energy scenarios.  
*18 records, 9 columns.*

| Column | Type | Sample Preview |
| :--- | :--- | :--- |
| `Year` | Integer | `2018` |
| `IT Capacity (GW)` | Float | `4.5` |
| `Historical Total Water (Billion L)` | Float | `488.0` |
| `Scenario A: Gas & Evaporative (Billion L)` | Float | `488.0` |
| `Scenario B: Clean Cooling Only (Billion L)` | Float | `488.0` |
| `Scenario C: Clean Cooling + Clean Tech (Billion L)` | Float | `488.0` |
| `Scenario D: Dry Cooling + Clean Grid (Billion L)` | Float | `488.0` |
| `Status` | String | `Hard Data` |
| `Citation` | String | `[6], [16], [17]` |

---

## 3. Chicago Author-Date Citations

- [1] Ren, Shaolei, Pengfei Li, Jianyi Yang, and Adam Wierman. 2023. "Making AI Less Thirsty: Uncovering and Addressing the Secret Water Footprint of AI Models." arXiv preprint arXiv:2304.03271.
- [2] Microsoft Corporation. 2025. "2025 Microsoft Environmental Data Fact Sheet." Redmond, WA: Microsoft Corporate Responsibility.
- [3] Alphabet Inc. / Google LLC. 2025. "2025 Environmental Report." Mountain View, CA: Google Sustainability.
- [4] Peer, Rebecca A. M., and Kelly T. Sanders. 2019. "Characterizing the Water Footprint of the US Electricity System." Environmental Science & Technology 53 (20): 12089–12098.
- [5] Siddik, Md Abu Bakar, Arman Shehabi, and Eric Masanet. 2021. "The Environmental Footprint of Data Centers in the United States." Environmental Research Letters 16 (6): 064017.
- [6] Lei, Nuoa, Arman Shehabi, and Eric Masanet. 2024. "Data Center Water Footprints: Determinants, Efficiencies, and Trade-Offs." Environmental Research: Infrastructure and Sustainability.
- [7] Environment and Climate Change Canada (ECCC). 2026. "Primer – Data Centre Water Consumption: Cooling Technologies, Power Sources, and Lifecycle Infrastructure." Ottawa, ON.
- [8] City of The Dalles. 2022. "Water Utility Annual Production and Industrial Consumption Records." The Dalles, OR: Public Works Department.
- [9] Meta Platforms, Inc. 2025. "2025 Environmental Data Index." Menlo Park, CA: Meta Sustainability.
- [10] Amazon.com, Inc. 2025. "AWS Sustainability Disclosures and Customer Water Withdrawal Methodology." Seattle, WA: Amazon Web Services.
- [11] Dieter, Cheryl A., et al. 2018. "Estimated Use of Water in the United States in 2015." U.S. Geological Survey Circular 1441. Reston, VA: USGS.
- [12] Golf Course Superintendents Association of America (GCSAA). 2021. "Water Use and Conservation Practices on U.S. Golf Courses." Lawrence, KS: Environmental Institute for Golf.
- [13] Beverage Industry Environmental Roundtable (BIER). 2023. "Water Use Benchmarking in the Global Beverage Sector." Washington, DC: BIER.
- [14] World Resources Institute (WRI). 2023. "Aqueduct 4.0: Updated Global Water Risk Mapping and Baseline Water Stress Database." Washington, D.C.: World Resources Institute.
- [15] Federal Energy Regulatory Commission (FERC), ERCOT & PJM Interconnection. 2024–2026. "Large-Load Interconnection Queues, Regional Transmission Organization (RTO) Planning Reports, and Public Utility Dockets." Washington, D.C., Austin, TX, and Norristown, PA.
- [16] U.S. Energy Information Administration (EIA). 2023. "Thermoelectric Cooling Water Consumption and Withdrawal Factors (Forms EIA-860 & EIA-923)." Washington, D.C.: U.S. Department of Energy.
- [17] Electric Power Research Institute (EPRI). 2024. "Powering Intelligence: Analyzing Artificial Intelligence and Data Center Energy and Water Consumption." Palo Alto, CA: EPRI.

---

## License & Attribution

All cleaned datasets are published under the [Creative Commons Attribution 4.0 International (CC-BY-4.0)](../LICENSE) license.  
**Attribution:** SusVizz (`@susvizz`).
