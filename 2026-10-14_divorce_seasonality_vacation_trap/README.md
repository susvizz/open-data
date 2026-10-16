# The Seasons of Divorce

> **SusVizz Analytical Series** | Published: 2026-10-14  
> **Topic:** 10-year empirical analysis of Washington State court dissolutions (210,000+ cases) and Google Trends proving biannual post-vacation divorce peaks and the 60-day financial retainer lag.  
> **Visual Deliverables:** [View SusVizz Publications](https://instagram.com/susvizz)

---

## 1. The Locked Factsheet

All visual slides, motion graphics, and captions strictly adhere to these canonical figures:

| Metric Component | Canonical Value | Empirical Context / Benchmark |
| :--- | :--- | :--- |
| **Holiday Truce Trough (Dec)** | **1,461 dissolutions/month (Index 72.5)** | Annual court low as couples hold the line through the holidays; Google Trends index 82.2 |
| **January Post-Holiday Rebound** | **1,702 dissolutions/month (+16.5%)** | Filings rebound immediately after holidays; travel friction exposes chronic marital cracks |
| **Winter Court Filings Peak (March)** | **2,014 dissolutions/month (+37.9%)** | Annual #1 filing peak (Index 100.0) following the 60-day legal retainer and W-2 disclosure lag |
| **Summer Court & Search Peak (August)** | **1,933 dissolutions/month (+32.3%)** | Annual #2 filing peak (Index 95.9) coinciding with Google search apex (Index 100.0) before school resumes |
| **Financial & Legal Buffer** | **$3,500–$5,000 upfront cash retainer** | Mandatory employer W-2 and 1099 disclosure bottleneck delays sworn petitions until late winter |

---

## 2. Dataset Catalog & Clean CSV Tables

All data tables below are clean, machine-readable, and formatted according to RFC-4180 standards. Click any table to inspect and search directly on GitHub:

### 📊 [filing_friction_timeline.csv](filing_friction_timeline.csv)
**The 4 Stages of Post-Holiday Legal and Financial Filing Friction**  
> **Visual Deliverable:** Slide 2: The Cost of Walking Out  
> **Source(s):** [1], [2], [3], [4], [5]  
> **Description:** Chronological timeline detailing the 60-day lag between January post-trip reality checks, mandatory W-2/1099 tax disclosures, cash retainers, and the March courtroom surge.  
*4 records, 7 columns.*

| Column | Type | Sample Preview |
| :--- | :--- | :--- |
| `stage_number` | Integer | `1` |
| `timeframe` | String | `Weeks 1–2 (Jan 1–15)` |
| `stage_name` | String | `The Post-Trip Reality Check` |
| `psychological_or_legal_reality` | String | `Return from vacation; holiday argum` |
| `google_search_level` | String | `Elevated (82.2)` |
| `court_filing_volume` | String | `Rebound (+16.5%)` |
| `source_tag` | String | `[1], [2], [3], [4]` |

### 📊 [monthly_divorce_filings.csv](monthly_divorce_filings.csv)
**Washington State Superior Court Monthly Divorce Filings (2016–2025)**  
> **Visual Deliverable:** Slide 1: The Seasons of Divorce  
> **Source(s):** [1], [2]  
> **Description:** 10-year monthly averages of dissolution of marriage petitions filed across Washington State Superior Courts (210,951 total cases), seasonal index, and percentage change from December trough.  
*12 records, 7 columns.*

| Column | Type | Sample Preview |
| :--- | :--- | :--- |
| `month` | String | `January` |
| `month_num` | Integer | `1` |
| `avg_monthly_filings` | Integer | `1702` |
| `filings_index_vs_peak` | Float | `84.5` |
| `delta_vs_december_trough_pct` | Float | `16.5` |
| `ritual_phase` | String | `Post-Holiday Inquiry & Resolution` |
| `source_tag` | String | `[1], [2]` |

### 📊 [search_vs_filings.csv](search_vs_filings.csv)
**Google Search Intent vs. Court Filings Seasonality (2016–2025)**  
> **Visual Deliverable:** Slide 1: The Seasons of Divorce  
> **Source(s):** [1], [2], [3]  
> **Description:** Normalized Google Trends monthly search volume index for 'divorce lawyer' in Washington State (US-WA) paired against actual court dissolution filings across a 10-year matched decade.  
*12 records, 7 columns.*

| Column | Type | Sample Preview |
| :--- | :--- | :--- |
| `month` | String | `January` |
| `month_abbr` | String | `Jan` |
| `google_search_index` | Float | `82.2` |
| `court_filings_index` | Float | `84.5` |
| `search_to_filing_divergence` | Float | `-2.3` |
| `key_behavior` | String | `Post-Holiday Rebound & Inquiries (S` |
| `source_tag` | String | `[1], [2], [3]` |

---

## 3. Chicago Author-Date Citations

- [1] Brines, Julie, and Brian Serafini. 2016. "Is Divorce Seasonal? The Importance of Family Ritual in a Postsentimental Era." Working Paper presented at the 111th Annual Meeting of the American Sociological Association (ASA), Seattle, WA.
- [2] Washington State Administrative Office of the Courts (AOC). 2026. "Superior Court Monthly Caseload Reports: Domestic Relations Cases Filed by Type of Case (2016–2025 Decade Archive)." Olympia, WA: Administrative Office of the Courts. https://www.courts.wa.gov/caseload/.
- [3] Google LLC. 2026. "Google Trends: Search Volume Index for 'Divorce Lawyer' in Washington State (US-WA) (Monthly Average, 2016–2025 10-Year Matched Decade)." Mountain View, CA: Google Trends. https://trends.google.com/trends/.
- [4] American Bar Association (ABA) Section of Family Law. 2023. "Family Law Retainer and Case Initiation Benchmarks: Practice Management Survey." Chicago, IL: American Bar Association. https://www.americanbar.org/groups/family_law/.
- [5] Benson, Harry. 2020. "Divorce Day: The Myth of the January Spike." Marriage Foundation Research Brief. London, UK: Marriage Foundation. https://marriagefoundation.org.uk/.

---

## License & Attribution

All cleaned datasets are published under the [Creative Commons Attribution 4.0 International (CC-BY-4.0)](../LICENSE) license.  
**Attribution:** SusVizz (`@susvizz`).
