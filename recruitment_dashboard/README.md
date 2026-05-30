# Solver India — Recruitment Analytics Dashboard v3.0

## 📊 Overview
A dual-dataset, interactive, multi-page recruitment analytics dashboard.
Open `index.html` directly in any modern browser — no server needed.

---

## 🆕 What's New in v3.0
- **Unordered Dataset (338 records)** fully integrated as primary view
- **Dataset switcher** in the top bar — toggle between Ordered (68) and Unordered (338)
- **Page 6: Dataset Comparison** — side-by-side KPI table + 3 comparison charts
- **Updated Smart Narratives** for both datasets
- Richer funnel and disposition analysis for the unordered data
- Preferred location analysis using Remark column (city detection)

---

## 🗂 Dashboard Pages

| Page | Description |
|------|-------------|
| **Executive Summary** | 8 KPI cards · Process bar · JL pie · Remark donut · Preferred location |
| **Recruitment Analytics** | Decomposition tree · Key influencers · Treemap · Duplicate analysis |
| **Location Insights** | Source cities · Preferred destinations · Process × Location heatmap |
| **Candidate Funnel** | Pipeline funnel · Disposition breakdown · JL × Process matrix |
| **Data Quality** | Gauge · Field completeness · Duplicate stacked bar |
| **Dataset Comparison** | KPI table · Volume · DQ · JL comparison charts |

---

## 📈 Dataset KPI Summary

| Metric | Ordered (68) | Unordered (338) |
|--------|-------------|-----------------|
| Total Candidates | 68 | 338 |
| Unique Candidates | 61 | 315 |
| Active Processes | 11 | 8 |
| Valid Contacts | 95.6% | 98.8% |
| Valid Emails | 95.6% | 97.9% |
| Duplicate % | 14.7% | 13.0% |
| Data Quality Score | 95.6% | 98.4% ✅ |

---

## 🗂 Unordered Dataset Insights
- **Top Process:** SCM - Varun (29.3%) & Supply Chain Mgmt (29.0%) — 58% of pipeline
- **Preferred Destination:** Bangalore (36.1%) + Bengaluru (10.9%) = 47% combined
- **Top JL:** 3A at 64.7%
- **Pipeline Size:** 5× larger than ordered dataset

---

## ⚙️ Technology
- Pure HTML + CSS + JavaScript (no framework)
- Chart.js 4.4.1 via CDN
- Google Fonts: DM Sans + Syne
- No backend, no build step required
