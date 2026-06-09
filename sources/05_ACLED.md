# Source 05: ACLED — Armed Conflict Location & Event Data

## 📋 Citation

> Armed Conflict Location & Event Data Project (ACLED). (2024). *ACLED Conflict Data* [Dataset]. Retrieved from https://acleddata.com/

> ACLED Conflict Index: https://acleddata.com/series/acled-conflict-index

---

## 🔍 Source Overview

| Field | Detail |
|---|---|
| **Publisher** | ACLED (independent, impartial non-profit) |
| **Coverage** | All countries and territories globally |
| **Update Frequency** | Near-real-time (weekly updates) |
| **Unit of Analysis** | Individual conflict events (battles, explosions, protests, riots, strategic developments, violence against civilians) |
| **License** | Free for non-commercial use; registration required |
| **Access** | https://acleddata.com/data-export-tool/ |

---

## 📊 Key Data Extracted

### ACLED Conflict Index (2023–2024)
The ACLED Conflict Index assesses every country/territory on **4 indicators:**
1. **Deadliness** — number of fatalities
2. **Danger to civilians** — targeting of non-combatants
3. **Geographic diffusion** — spatial spread of conflict
4. **Number of armed groups** — fragmentation of conflict actors

### Regional Coverage Available
| Region | ACLED Coverage |
|---|---|
| Africa | Full coverage; dedicated regional dashboard |
| Asia-Pacific | Full coverage |
| Europe & Central Asia | Full coverage (includes Ukraine monitor) |
| Latin America & Caribbean | Full coverage |
| Middle East | Full coverage (Gaza conflict monitor, Iran war updates) |
| US & Canada | Full coverage |

### Specialty Monitors (2023)
- **Ukraine Conflict Monitor** — real-time tracking
- **Gaza Conflict Monitor** — event-level data since October 2023
- **Middle East Conflict Monitor** — regional escalation tracking
- **Mozambique Conflict Monitor** — sub-national tracking

### West Africa Analysis (via GitHub: akandeolufelachristianah-cmyk/west-africa-conflict-analysis)
- Covers 2005–2025 using ACLED data
- Python and Power BI analysis
- Demonstrates ACLED's utility for regional trend analysis

---

## 🗒️ Annotation

ACLED is the highest-quality near-real-time conflict data source globally, complementing UCDP's more methodologically conservative annual dataset. Its event-level structure and real-time updates make it particularly valuable for tracking rapidly evolving conflicts like Gaza and Ukraine.

**Strengths:**
- Real-time data with weekly updates — critical for 2023 Gaza conflict coverage
- Covers protests and riots in addition to armed conflict (broader violence spectrum)
- Disaggregated by event type, actor type, and civilian targeting
- ACLED Conflict Index provides a multi-dimensional assessment comparable to GPI
- Strong Africa coverage, including dedicated West Africa analysis
- Widely used by UN agencies, INGOs, and governments

**Limitations:**
- Fatality figures may differ from UCDP (different source protocols and inclusion criteria)
- Requires data export tool registration; bulk downloads can be large
- Protest data may inflate "conflict" counts relative to strictly armed-conflict datasets
- Retrospective coding may introduce inconsistencies over time
- Commercial use requires licensing agreement

**Comparison with UCDP:**
| Feature | ACLED | UCDP |
|---|---|---|
| Update frequency | Weekly (real-time) | Annual |
| Event types | Broad (incl. protests) | Narrow (armed violence) |
| Fatality threshold | None | ≥25/year |
| Geographic detail | Sub-national | Village-level |
| Time coverage | 1997–present | 1989–present |

**Relevance to research question:**
ACLED provides corroboration for UCDP-based fatality estimates and enables real-time monitoring of the regions under study. The ACLED Conflict Index's four-dimensional framework could serve as an alternative dependent variable to the GPI in future analyses.

---

## 🔗 Related Files
- [`sources/04_UCDP_GED.md`](./04_UCDP_GED.md) — complementary dataset
- [`sources/08_GitHub_Repos.md`](./08_GitHub_Repos.md) — ACLED analysis repositories
- [`computed_metrics.md`](../computed_metrics.md) — fatality estimates

---

*Added: June 2026*
