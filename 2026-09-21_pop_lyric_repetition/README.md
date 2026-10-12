# Pop Lyric Repetition & The 'Thunder' Illusion

> **SusVizz Analytical Series** | Published: 2026-09-21  
> **Topic:** Quantifying vocal repetition frequency, lyrical cadences, and perception vs. reality across modern pop hits.  
> **Visual Deliverables:** [View SusVizz Publications](https://instagram.com/susvizz)

---

## 1. The Locked Factsheet

All visual slides, motion graphics, and captions strictly adhere to these canonical figures:

| Metric Component | Canonical Value | Empirical Context / Benchmark |
| :--- | :--- | :--- |
| **The Repetition Outlier** | **76 repetitions of 'Thunder'** | Imagine Dragons (2017) repeating the title word every 2.4 seconds |
| **Lead Vocal Repetition Velocity** | **24.6 repetitions/minute** | Peak verbal velocity during 3-minute radio broadcast |
| **Perception Illusion** | **77% perceived repeat share** | Listeners perceive repeated words as occupying >75% of lyrical real estate |

---

## 2. Dataset Catalog & Clean CSV Tables

All data tables below are clean, machine-readable, and formatted according to RFC-4180 standards. Click any table to inspect and search directly on GitHub:

### 📊 [pop_lyric_repetition.csv](pop_lyric_repetition.csv)
**Pop Lyric Repetition Master Leaderboard**  
> **Visual Deliverable:** Slide 1: Gross Repetition Volume & Verbal Velocity (The Hall of Fame)  
> **Source(s):** [1], [2], [3], [4], [5], [7]  
> **Description:** Audited repetition counts, lyrical velocities (RPM), Billboard chart peaks, and commercial performance across modern hits.  
*20 records, 21 columns.*

| Column | Type | Sample Preview |
| :--- | :--- | :--- |
| `Song_Title` | String | `Boom Boom Pow` |
| `Artist` | String | `The Black Eyed Peas` |
| `Release_Year` | Integer | `2009` |
| `Genre` | String | `Dance-Pop / Electro-Hop` |
| `Repeated_Word` | String | `Boom` |
| `Word_Type` | String | `Lexical Word` |
| `Duration_Formatted` | String | `04:12` |
| `Duration_Seconds` | Integer | `252` |
| `Lead_Vocal_Repetitions` | Integer | `168` |
| `Total_Layered_Repetitions` | Integer | `168` |
| `Repetition_Velocity_RPM` | Float | `40.0` |
| `Repetition_Cadence_Seconds` | Float | `1.5` |
| `Peak_Billboard_Hot_100` | Float | `1.0` |
| `Weeks_on_Hot_100` | Integer | `38` |
| `Spotify_Streams_Millions` | Float | `572.0` |
| `YouTube_Views_Millions` | Float | `555.0` |
| `RIAA_Certification` | String | `10x Platinum (Diamond)` |
| `Grammy_Status` | String | `Winner (Best Short Form Video)` |
| `Repetition_Category` | String | `Top 10 Hall of Fame` |
| `Methodology_Notes` | String | `Will.i.am stated 168 in Rolling Sto` |
| `Citation_ID` | String | `[1], [2], [3], [4], [5], [7]` |

---

## 3. Chicago Author-Date Citations

- [1] Billboard Media, LLC. 2026. "Billboard Hot 100 Historical Archives & Chart Peaks." Penske Media Corporation. https://www.billboard.com/charts/hot-100/.
- [2] Recording Industry Association of America (RIAA). 2026. "Gold & Platinum Certifications Database." Washington, D.C.: RIAA. https://www.riaa.com/gold-platinum/.
- [3] Spotify AB. 2026. "Spotify Global Stream Counts." Spotify Technology S.A. Accessed via Kworb.net & Chartmetric (September 2026). https://kworb.net/spotify/.
- [4] YouTube. 2026. "Official Music Video & Audio Viewership Counts." Alphabet Inc. Accessed via Kworb.net YouTube Records (September 2026). https://kworb.net/youtube/.
- [5] Genius Media Group. 2026. "Verified Song Lyrics & Transcriptions." Genius.com. https://genius.com.
- [6] Morris, Colin. 2017. "Are Pop Lyrics Getting More Repetitive?" The Pudding (May 2017). https://pudding.cool/2017/05/song-repetition/.
- [7] National Academy of Recording Arts and Sciences. 2026. "Grammy Awards Search & Past Winners Database." The Recording Academy. https://www.grammy.com/awards.

---

## License & Attribution

All cleaned datasets are published under the [Creative Commons Attribution 4.0 International (CC-BY-4.0)](../LICENSE) license.  
**Attribution:** SusVizz (`@susvizz`).
