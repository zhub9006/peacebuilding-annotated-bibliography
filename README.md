# 📚 Peacebuilding Annotated Bibliography

> **Research Project:** Comparing conflict fatality statistics and peace index rankings across regions with **high** vs. **low** peacebuilding investment.

---

## 🗂️ Repository Structure

```
peacebuilding-annotated-bibliography/
├── README.md                          ← You are here
├── computed_metrics.md                ← All calculated comparative statistics
├── sources/
│   ├── 01_GPI_2023.md                 ← Global Peace Index 2023 (IEP)
│   ├── 02_PRIO_conflict_trends.md     ← PRIO Conflict Trends 1946–2023
│   ├── 03_UN_PBF_2023.md              ← UN Peacebuilding Fund 2023 Report
│   ├── 04_UCDP_GED.md                 ← Uppsala Conflict Data Program (GED)
│   ├── 05_ACLED.md                    ← Armed Conflict Location & Event Data
│   ├── 06_OurWorldInData_conflicts.md ← Our World in Data – Conflict Deaths
│   ├── 07_EffectivePeace_Dashboard.md ← Effective Peacebuilding Initiative
│   └── 08_GitHub_Repos.md             ← Relevant GitHub repositories
└── data_notes/
    ├── regional_classification.md     ← How regions are grouped (high/low investment)
    └── methodology.md                 ← Calculation methodology and caveats
```

---

## 🔬 Research Question

**Do regions receiving higher levels of peacebuilding investment (as proxied by UN Peacebuilding Fund allocations and ODA conflict-prevention streams) exhibit lower conflict fatality rates per capita and better Global Peace Index scores?**

---

## 📊 Key Findings at a Glance

| Metric | High-Investment Regions | Low-Investment Regions |
|---|---|---|
| Avg. GPI Score (2023) | ~2.163 (Sub-Saharan Africa) | ~3.409 (MENA) |
| Battle Deaths / 1M pop | ~51.6 (SSA) | ~61.0 (MENA/S.Asia) |
| GPI vs. Europe differential | +0.461 above Europe avg | +1.707 above Europe avg |
| PBF Allocation (2023 est.) | ~$91.1M (Africa, 45%) | ~$20.2M (others, 10%) |

> ⚠️ Full methodology, caveats, and per-source citations are in [`computed_metrics.md`](./computed_metrics.md).

---

## 📖 Sources Overview

| # | Source | Type | Year | Key Data |
|---|---|---|---|---|
| 1 | Global Peace Index (IEP) | Index/Report | 2023 | Regional GPI scores, peace rankings |
| 2 | PRIO Conflict Trends | Academic Paper | 2024 | Battle deaths 2023, conflict counts |
| 3 | UN Peacebuilding Fund SG Report | UN Official | 2023 | $202M spending, 36 countries |
| 4 | UCDP Georeferenced Event Dataset | Dataset | 2025 | Disaggregated fatality data |
| 5 | ACLED Conflict Data | Dataset | Live | Event-level conflict & fatality data |
| 6 | Our World in Data – Conflict Deaths | Visualization | 2025 | Regional death series 1989–2024 |
| 7 | Effective Peacebuilding Initiative | Dashboard | 2023 | 1,000+ peace indicators, 34 datasets |
| 8 | GitHub Repositories | Code | 2024–26 | Analysis tools and conflict notebooks |

---

## 🛠️ How to Use This Repository

1. Start with **`computed_metrics.md`** for the headline numbers and calculations.
2. Read individual source files in **`sources/`** for full citations and annotations.
3. Check **`data_notes/`** for methodological transparency and region definitions.

---

*Last updated: June 2026 | Compiled using IEP GPI 2023, PRIO 2024, UN PBF 2023, UCDP GED 2025, ACLED, Our World in Data, and Effective Peacebuilding Initiative data.*
