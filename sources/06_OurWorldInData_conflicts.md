# Source 06: Our World in Data — Deaths in Armed Conflicts by Region

## 📋 Citation

> Roser, M., Hasell, J., Herre, B., & Macdonald, B. (2025). *Deaths in Armed Conflicts by Region* [Data visualization]. Our World in Data. Retrieved from https://ourworldindata.org/grapher/deaths-in-armed-conflicts-by-region

> Underlying data: Davies, S., Pettersson, T., Sollenberg, M., & Öberg, M. (2025). Organized violence 1989–2024, and the challenges of identifying civilian victims. *Journal of Peace Research, 62*(4).

---

## 🔍 Source Overview

| Field | Detail |
|---|---|
| **Publisher** | Our World in Data (University of Oxford / Global Change Data Lab) |
| **Primary Data Source** | UCDP Georeferenced Event Dataset (GED v25.1) |
| **Coverage** | Global, 1989–2026 (2025–2026 preliminary) |
| **Last Updated** | May 1, 2026 |
| **License** | CC BY 4.0 |
| **Access** | Free; https://ourworldindata.org |

---

## 📊 Key Data Extracted

### Indicator Definition
> "The best estimate of the number of deaths of combatants and civilians due to fighting in interstate, intrastate, extrasystemic, non-state conflicts, and one-sided violence that were ongoing that year."

**Conflict types included:**
- Interstate conflicts
- Intrastate (civil) conflicts
- Non-state conflicts
- One-sided violence against civilians
- Colonial conflicts (historical)
- Extrasystemic conflicts

**NOT included:**
- Deaths from disease or starvation resulting from conflict
- Indirect deaths

### Data Reliability Notes
- 2025–2026 data is **preliminary** — may be too low (underreporting) or too high (over-attribution)
- 2026 data covers Q1 only (added in May 2026)
- UCDP Candidate Events Dataset used for preliminary figures (monthly release cycle)
- "Best" estimates shown; high/low uncertainty bounds also available from UCDP

### Update Schedule
| Quarter | Added to OWID |
|---|---|
| Q1 (Jan–Mar) | May |
| Q2 (Apr–Jun) | August |
| Q3 (Jul–Sep) | November |
| Q4 (Oct–Dec) | February |

---

## 🗒️ Annotation

Our World in Data's conflict deaths visualization is the most accessible and pedagogically effective presentation of UCDP data. Its regional breakdown and long time series (1989–present) make it ideal for identifying structural trends in conflict lethality by region.

**Strengths:**
- Clean, interactive visualization with regional breakdowns
- Directly cites and links to underlying UCDP data (full transparency)
- Free, open-access, CC BY 4.0
- Regular updates with clear vintage labeling
- Accompanied by explanatory text clarifying methodology
- Enables comparison across all major regions simultaneously

**Limitations:**
- Inherits all limitations of UCDP GED (see Source 04)
- Regional groupings may not match PBF or GPI regional classifications exactly
- Preliminary data for recent years should be treated with caution
- Visualization does not show per-capita rates by default (requires external calculation)

**Relevance to research question:**
This source provides the visual and data foundation for the regional death series used in the fatality rate calculations. The regional breakdown enables direct comparison between high-investment regions (SSA, MENA) and low-investment regions (Europe, North America) over time, supporting both cross-sectional and longitudinal analysis.

**Key finding for this project:**
The chart confirms that Sub-Saharan Africa has consistently been the highest-death region in recent years, with MENA peaking during the Syrian war and again in 2023 (Gaza + Yemen). Europe's death toll spiked in 2022–2023 due to Ukraine but remains far lower in per-capita terms than SSA or MENA.

---

## 🔗 Related Files
- [`sources/04_UCDP_GED.md`](./04_UCDP_GED.md) — primary underlying dataset
- [`computed_metrics.md`](../computed_metrics.md) — Section 3 (regional rates)
- [`sources/02_PRIO_conflict_trends.md`](./02_PRIO_conflict_trends.md) — narrative synthesis

---

*Added: June 2026*
