# Postmates × Uber Eats — City-Portfolio Retention Strategy

**A strategy & operations case study: 44 US metros, 13 months, two apps — and a playbook for running them as a portfolio instead of a single brand.**

Author: Lizhong (Zoe) Wang · [LinkedIn](https://www.linkedin.com/in/lizhongwang) · May 2026

---

## The strategic thesis

Food delivery is not one national market — it is 44 city-level battles. Postmates and Uber Eats share infrastructure but capture structurally different users, occasions, and merchants:

- **Postmates is structurally premium**: AOV $32.57 vs UE $28.99 (+12%), but monetized worse (take rate 12.9% vs 15.1%)
- **Postmates is geographically concentrated, not nationally distributed**: meaningful share (11–43%) in only ~10–12 cities; negligible elsewhere
- **The trend lines diverge**: over the case window, UE grew ~+17% YoY (above the ~+11% industry rate) while PM declined ~−11% — but the decline is *not uniform across cities*, which is exactly why a single national strategy fails

**Conclusion: run the two apps as a portfolio (1 + 1 > 2), with a different play per city tier.**

## The DIM playbook

Every city is scored on PM share, combined growth vs industry, and *absorption* (how much of PM's decline UE actually recaptures), then assigned a tier:

| Tier | Signal | Play |
|---|---|---|
| **Defend** | High PM share, PM decline NOT absorbed by UE | Invest in PM retention — losses leak to competitors |
| **Investigate** | Meaningful PM share, mixed signals | Diagnose before deciding (the pilot cluster) |
| **Maintain** | Healthy combined growth, UE absorbing naturally | Don't over-invest; let the portfolio work |
| **Migrate** | Low PM share, high absorption | Actively transition users to UE |

## The recommendation

**Launch a 3-month Postmates retention pilot in Los Angeles** — the highest-priority Investigate-tier city (36% PM share, combined growth below industry) — targeting a **+2pp retention lift** with a 20% A/B holdout.

Scaled to the 14-city Investigate cluster (base case): **$2.7M Year-1 GB defended, ~2,700 active eaters saved, ~$482K of 3-year compounded LTV** once cross-platform value and Uber One conversion are layered in.

## Repo map

```
├── notebooks/
│   └── uber_so_eda.ipynb          # Full EDA — 21 sections: cleaning, reconciliation,
│                                  #   city-level analysis, tiering, outlier scans
├── data/
│   ├── raw/                       # Original case dataset (44 anonymized metros × 2 apps × 13 months)
│   └── processed/                 # Clean long format, city×app aggregates, YoY + tier view
├── deliverables/
│   ├── Zoe_Wang_Postmates_SO_Case_Study.pptx   # 10-slide strategy deck
│   ├── methodology_summary.docx   # Every metric, model, and assumption documented
│   ├── city_dashboard.html        # Interactive city explorer (4-quadrant + DIM tier views)
│   └── ltv_calculator.html        # Interactive user-side + merchant-side LTV model
└── docs/
    └── industry_benchmarks.md     # External context, every claim sourced
```

## What's inside the analysis

- **Income-statement reconciliation**: GB decomposed to net revenue per app, reconciling to within ~1.5% of GB (tax properly excluded), visualized as waterfalls
- **City-level EDA**: concentration (top 10 cities ≈ 75% of GB), PM penetration distribution, outlier scans on AOV / take rate / engagement, cross-app correlations, rank stability (Kendall τ ≈ 0.95)
- **Two views of retention spend**: PM spends 39% more per GB dollar on existing-eater incentives than UE — quantified per-GB and per-active-eater-month
- **Scenario & LTV modeling**: retention lift scenarios with sensitivity ranges; 3-year LTV compounding cross-platform usage and subscription conversion
- **Instrumentation plan**: the metrics to build before scaling the pilot

## Method notes

- Dataset: simulated case data — 44 anonymized US metros, June 2022 → June 2023, city × app × month granularity (1,144 rows)
- All external market claims are grounded in cited public sources (`docs/industry_benchmarks.md`)
- Assumptions, limitations, and outlier handling documented in `deliverables/methodology_summary.docx`

## Stack

Python (pandas, matplotlib, seaborn) · SQL-style aggregation · Interactive HTML/JS deliverables · Claude Code for analysis automation

---

*Interactive deliverables (`city_dashboard.html`, `ltv_calculator.html`) are self-contained — download and open in any browser.*
