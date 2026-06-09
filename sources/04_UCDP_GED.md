# Source 04: Uppsala Conflict Data Program — Georeferenced Event Dataset (GED)

## 📋 Citation

> Davies, S., Pettersson, T., Sollenberg, M., & Öberg, M. (2025). Organized violence 1989–2024, and the challenges of identifying civilian victims. *Journal of Peace Research, 62*(4).

> Sundberg, Ralph and Erik Melander. (2013). Introducing the UCDP Georeferenced Event Dataset. *Journal of Peace Research, 50*(4).

**Dataset Download:** https://ucdp.uu.se/downloads/index.html#ged_global  
**Codebook:** https://ucdp.uu.se/downloads/ged/ged251.pdf  
**Interactive Portal:** https://ucdp.uu.se/

---

## 🔍 Source Overview

| Field | Detail |
|---|---|
| **Publisher** | Uppsala University, Department of Peace and Conflict Research |
| **Program** | Uppsala Conflict Data Program (UCDP) |
| **Current Version** | GED v25.1 (covers 1989–2024) |
| **Coverage** | Global, 1989–2024 |
| **Unit of Analysis** | Individual violent events (georeferenced to village level) |
| **License** | CC BY 4.0 |
| **Access** | Free download; requires registration |

---

## 📊 Key Data Extracted

### Dataset Characteristics
| Feature | Detail |
|---|---|
| Temporal granularity | Individual day-level events |
| Geographic granularity | Village level (lat/long coordinates) |
| Conflict types | State-based, non-state, one-sided violence |
| Death estimates | Low, best, high estimates |
| Reporting basis | News reports, academic research, contemporary sources |

### 2023 Summary Statistics (via PRIO 2024 synthesis)
| Metric | Value |
|---|---|
| State-based conflicts | 59 in 34 countries |
| Battle-related deaths (best estimate) | >122,000 |
| Non-state conflicts | 75 |
| Non-state deaths | ~21,000 |
| One-sided violence countries | 35 |

### UCDP Conflict Definition
An armed conflict requires **≥25 deaths per year** from fighting between organized groups (or an organized group and civilians). This threshold means:
- Low-intensity conflicts are included
- Sporadic violence below 25 deaths/year is excluded
- The definition has become the **global standard** for conflict research

### Candidate Events Dataset (Preliminary)
- Published monthly with <1 month lag
- Enables near-real-time monitoring
- Used by Our World in Data for 2025–2026 preliminary figures
- Citation: Hegre et al. (2020), *Research & Politics*

---

## 🗒️ Annotation

UCDP GED is the foundational dataset for conflict fatality research. Its disaggregated, georeferenced structure makes it the most analytically flexible source available for regional and temporal comparisons.

**Strengths:**
- Oldest ongoing conflict data collection project globally (40+ year history)
- Gold-standard definition of armed conflict (globally adopted)
- Free, open-access, CC BY 4.0 license
- Multiple death estimates (low/best/high) support uncertainty quantification
- Village-level georeferencing enables sub-national analysis
- Covers all organized violence types (state, non-state, one-sided)

**Limitations:**
- Based primarily on media reports — undercounting in low-media-coverage regions (e.g., rural Sub-Saharan Africa)
- Does not include indirect deaths from disease, famine, or displacement caused by conflict
- 25-death threshold excludes sub-threshold violence
- Data for most recent year is always preliminary and subject to upward revision
- Civilian casualty attribution is methodologically challenging (acknowledged in 2025 paper title)

**Relevance to research question:**
UCDP GED is the primary data source for all fatality numerators in this project. The regional breakdown of deaths (used in `computed_metrics.md` Section 3) derives from UCDP data as synthesized by PRIO 2024. The dataset is also the basis for the Our World in Data conflict visualization (Source 06).

**GitHub Integration:**
The `datapartnership/acled_conflict_analysis` repository on GitHub provides Python tools for similar event-level data processing, applicable to UCDP GED workflows.

---

## 🔗 Related Files
- [`computed_metrics.md`](../computed_metrics.md) — Sections 1, 3
- [`sources/02_PRIO_conflict_trends.md`](./02_PRIO_conflict_trends.md) — PRIO synthesis of UCDP
- [`sources/06_OurWorldInData_conflicts.md`](./06_OurWorldInData_conflicts.md) — UCDP-based visualization
- [`sources/05_ACLED.md`](./05_ACLED.md) — complementary event-level dataset

---

*Added: June 2026*
