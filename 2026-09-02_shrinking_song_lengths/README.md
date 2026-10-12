# The Great Pop Song Shrink (1960–2024)

> **SusVizz Analytical Series** | Published: 2026-09-02  
> **Topic:** 65-year structural collapse of Billboard Hot 100 durations, streaming royalty unit economics, and algorithmic skip hazard.  
> **Visual Deliverables:** [View SusVizz Publications](https://instagram.com/susvizz)

---

## 1. The Locked Factsheet

All visual slides, motion graphics, and captions strictly adhere to these canonical figures:

| Metric Component | Canonical Value | Empirical Context / Benchmark |
| :--- | :--- | :--- |
| **All-Time Peak Median** | **4:24 (264s)** | 1995 Billboard Hot 100 median duration (Peak CD album era) |
| **Current Median** | **3:06 (186s)** | 2024 Billboard Hot 100 median duration (Streaming / TikTok era) |
| **Net Duration Delta** | **-78 seconds (-29.5%)** | Total runtime shaved off chart-topping songs since 1995 |
| **Economic Arbitrage** | **+42% revenue yield** | 19.4 plays/hr ($0.068) for 3:06 tracks vs. 13.6 plays/hr ($0.048) for 4:24 tracks |
| **Skip Hazard Cliff** | **24% by Sec 5 / 35% by Sec 30** | Listener abandonment prior to Spotify's 30-second payout trigger |

---

## 2. Dataset Catalog & Clean CSV Tables

All data tables below are clean, machine-readable, and formatted according to RFC-4180 standards. Click any table to inspect and search directly on GitHub:

### 📊 [skip_rates.csv](skip_rates.csv)
**Listener Skip Hazard Curve (Seconds 0–60)**  
> **Visual Deliverable:** Slide 4: The Algorithmic Skip Hazard  
> **Source(s):** [5], [6]  
> **Description:** Second-by-second listener abandonment curve showing the 35% attrition cliff before the monetization threshold.  
*10 records, 7 columns.*

| Column | Type | Sample Preview |
| :--- | :--- | :--- |
| `time_sec` | Integer | `0` |
| `listener_retention_pct` | Float | `100.0` |
| `cumulative_skip_pct` | Float | `0.0` |
| `royalty_status` | String | `Zero Royalty Zone` |
| `algorithmic_signal` | String | `Neutral` |
| `data_status` | String | `Hard Data` |
| `source_id` | String | `[5]` |

### 📊 [song_anatomy.csv](song_anatomy.csv)
**Pop Song Structural Anatomy Breakdown (1995 vs 2024)**  
> **Visual Deliverable:** Slide 2: The Song Autopsy  
> **Source(s):** [4]  
> **Description:** Segment-by-segment duration comparison (intros, verses, choruses, bridges, solos) illustrating structural pruning.  
*13 records, 11 columns.*

| Column | Type | Sample Preview |
| :--- | :--- | :--- |
| `era` | String | `1995 Pop Single (CD Boom Peak)` |
| `year` | Integer | `1995` |
| `segment_order` | Integer | `1` |
| `segment_name` | String | `Atmospheric Intro` |
| `duration_sec` | Integer | `28` |
| `start_sec` | Integer | `0` |
| `end_sec` | Integer | `28` |
| `pct_of_total` | Float | `10.6` |
| `role_description` | String | `Extended synthesizer & drum groove ` |
| `data_status` | String | `Hard Data` |
| `source_id` | String | `[4]` |

### 📊 [song_distribution.csv](song_distribution.csv)
**Billboard Hot 100 Track Durations (1958–2024)**  
> **Visual Deliverable:** Slide 1: The Great Pop Song Shrink (Distribution)  
> **Source(s):** [1], [2], [3]  
> **Description:** Audited runtime measurements across 6,500+ chart-topping songs spanning the Vinyl, CD, and Streaming eras.  
*6500 records, 9 columns.*

| Column | Type | Sample Preview |
| :--- | :--- | :--- |
| `year` | Integer | `1960` |
| `rank` | Integer | `1` |
| `song` | String | `Running Bear` |
| `artist` | String | `Johnny Preston` |
| `duration_sec` | Float | `158.2` |
| `duration_min` | Float | `2.6366666666666663` |
| `era` | String | `Vinyl & 45 RPM Era (1960-1981)` |
| `data_status` | String | `Hard Data` |
| `source_id` | String | `[1], [2]` |

### 📊 [streaming_economics.csv](streaming_economics.csv)
**Streaming Royalty Arbitrage & Turnaround Efficiency**  
> **Visual Deliverable:** Slide 3: The 30-Second Royalty Arbitrage  
> **Source(s):** [5], [6]  
> **Description:** Hourly payout calculations and unpaid audio runtime comparisons under Spotify's 30-second qualification threshold.  
*2 records, 13 columns.*

| Column | Type | Sample Preview |
| :--- | :--- | :--- |
| `track_archetype` | String | `CD Era Peak Average (1995)` |
| `runtime_sec` | Integer | `264` |
| `runtime_formatted` | String | `4:24` |
| `qualification_threshold_sec` | Integer | `30` |
| `unpaid_runtime_sec` | Integer | `234` |
| `unpaid_runtime_pct` | Float | `88.6` |
| `max_plays_per_hour` | Float | `13.64` |
| `royalty_rate_per_stream_usd` | Float | `0.0035` |
| `hourly_revenue_yield_usd` | Float | `0.0477` |
| `relative_revenue_indexed` | Float | `100.0` |
| `monetization_efficiency_comment` | String | `Listener enjoys 3:54 of unpaid musi` |
| `data_status` | String | `Hard Data` |
| `source_id` | String | `[5], [6]` |

### 📊 [yearly_averages.csv](yearly_averages.csv)
**Annual Median & Mean Pop Song Durations (1958–2024)**  
> **Visual Deliverable:** Slide 1: The Great Pop Song Shrink (Yearly Trend)  
> **Source(s):** [1], [2], [3]  
> **Description:** Longitudinal tracking of annual median song length collapsing from 4:24 (1995 peak) to 3:06 (2024).  
*65 records, 13 columns.*

| Column | Type | Sample Preview |
| :--- | :--- | :--- |
| `year` | Integer | `1960` |
| `mean_duration_sec` | Float | `154.54684` |
| `median_duration_sec` | Float | `149.813` |
| `mean_duration_min` | Float | `2.5757806666666663` |
| `median_duration_min` | Float | `2.4968833333333333` |
| `min_duration_min` | Float | `1.65355` |
| `max_duration_min` | Float | `6.210433333333333` |
| `p25_duration_min` | Float | `2.3101666666666665` |
| `p75_duration_min` | Float | `2.746166666666667` |
| `song_count` | Integer | `100` |
| `era` | String | `Vinyl & 45 RPM Era (1960-1981)` |
| `data_status` | String | `Hard Data` |
| `source_id` | String | `[1], [2], [3]` |

---

## 3. Chicago Author-Date Citations

- [1] Billboard. 2024. "Billboard Hot 100 Historical Archives & Year-End Charts (1958–2024)." Billboard Media, LLC. https://www.billboard.com/charts/hot-100/
- [2] Spotify Technology S.A. 2024. "Spotify Web API Track Audio Features & Analytics." Spotify for Developers. https://developer.spotify.com/documentation/web-api/
- [3] Apple Inc. 2024. "Apple Music & iTunes Search API Verified Track Metadata." Apple Media Services. https://developer.apple.com/
- [4] Dalla Riva, Chris. 2025. "Billboard Hot 100 Number Ones: Audio Analysis and Historical Trends (1958–2025)." Can't Get Much Higher / TidyTuesday.
- [5] Lamere, Paul. 2014. "The Skip: The Mechanics of Skipping Music." Music Machinery / The Echo Nest (Spotify). https://musicmachinery.com/2014/05/02/the-skip/
- [6] Copyright Royalty Board & Soundcharts. 2024. "Streaming Royalty Calculations, 30-Second Qualification Rules, and Pro-Rata Pools." Soundcharts Blog & CRB.

---

## License & Attribution

All cleaned datasets are published under the [Creative Commons Attribution 4.0 International (CC-BY-4.0)](../LICENSE) license.  
**Attribution:** SusVizz (`@susvizz`).
