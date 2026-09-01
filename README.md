
# Digital Marketing Performance Dashboard
Cross-platform digital marketing analytics project (Excel + Tableau) analyzing  campaigns across Facebook, Google Ads, Instagram &amp; LinkedIn — pivot tables, ROI/CPC/CTR calculations, and dashboard visualization to identify top-performing campaigns and optimize ad spend.
**Cross-Platform Ad Campaign Analysis — Excel + Tableau**

![Dashboard Preview](Screenshot%2026-09-01%20003113)

---
## Problem Statement

Marketing teams often run paid campaigns across multiple platforms without a unified view of which channel is actually generating the best return. This project analyzes campaign performance across **Facebook, Google Ads, Instagram, and LinkedIn** to answer:

1. Which platform delivers the best ROI, and where should budget be reallocated?
2. Which platforms are cost-efficient (low CPC) versus highly effective (high conversion rate)?
3. Which individual campaigns are top performers — and which are underperforming?
4. Where is ad spend not translating into return?

---

## Dataset

- **40 campaign records** across 4 platforms and 12 campaign types
- **Period:** January – March 2026
- **Metrics tracked:** Impressions, Reach, Clicks, CTR (%), Ad Spend (INR), Conversions, Conversion Rate (%), CPC (INR), ROI (x)
- This is a simulated dataset built to mirror the structure and metrics of real campaign reporting.

---

## Methodology

- Built pivot tables in Excel to aggregate performance by platform and by campaign, applying standard marketing formulas:
  - `CTR (%) = Clicks / Impressions`
  - `Conversion Rate (%) = Conversions / Clicks`
  - `CPC (INR) = Ad Spend / Clicks`
  - `ROI (x) = Revenue / Ad Spend`
- Verified aggregation logic across all pivot tables (using Average for rate-based metrics, Sum for volume metrics) to avoid inflated or misleading totals.
- Rebuilt the analysis visually in **Tableau**, including a dual-axis chart (CPC vs. Conversion Rate), a ranked bar chart, a scatter plot (Spend vs. ROI), and a calculated field using `RANK()` to automatically flag top- and bottom-performing campaigns.

---

## Key Findings

**Platform Performance (by ROI)**

| Platform | Avg. ROI | Avg. CPC (INR) |
|---|---|---|
| Facebook | **10.41x** | ₹108 |
| Google Ads | 9.14x | ₹94 |
| Instagram | 8.52x | ₹80 |
| LinkedIn | 7.01x | ₹159 |

Facebook delivers the strongest return despite a mid-range cost per click. LinkedIn is the most expensive platform per click and also the weakest on ROI — a candidate for budget reduction unless the goal is specifically high-value B2B leads.

**Top Campaigns**

| Campaign | ROI | Conversions |
|---|---|---|
| Lead Gen – Carousel | **78.9x** | 529 |
| B2B Lead Gen | 41.5x | 271 |
| Search – Generic Keywords | 37.2x | 379 |
| Display Remarketing | 34.3x | 144 |

**Weakest Campaign:** Thought Leadership Article — 1.99x ROI on ₹32,541 spend, 55 conversions. A clear candidate to pause or redesign.

**Overall:** ₹4,19,198 total spend → 2,793 conversions → 8.77x average ROI across all campaigns.

---

## How This Project Solves the Problem

This dashboard directly answers each question raised in the Problem Statement:

- **Which platform delivers the best ROI?** → Facebook (10.41x), identified through platform-wise pivot analysis — giving a clear basis for budget reallocation.
- **Cost-efficient vs. highly effective platforms?** → Instagram is cheapest per click (₹80 CPC), while LinkedIn converts best (55%) but costs most (₹159 CPC) — the dual-axis chart makes this trade-off visible at a glance instead of buried in raw numbers.
- **Top vs. underperforming campaigns?** → The ranked bar chart flags Lead Gen – Carousel (78.9x ROI) as the clear winner and Thought Leadership Article (1.99x ROI) as the weakest, using an automated RANK() calculation rather than manual eyeballing.
- **Where is spend wasted?** → The Spend vs. ROI scatter plot isolates high-spend, low-return campaigns visually, making inefficient spend easy to spot without scanning every row.

In short: instead of leaving a marketing team to manually cross-reference spreadsheets, this dashboard turns raw campaign data into a direct, visual answer to "where should our next rupee of ad spend go."

---

## Recommendation

Reallocate budget away from low-performing awareness content (e.g. Thought Leadership Article) toward proven conversion-driven formats — particularly Lead Gen – Carousel and Display Remarketing. Shift a greater share of spend toward Facebook, which is outperforming its cost, and treat LinkedIn as a targeted channel for high-value leads rather than a volume platform given its higher CPC.

*Note: this dataset is simulated. The recommendation reflects the patterns present in the data, applying the same decision logic used for real campaign optimization.*

---

## Dashboard

**Excel — Pivot Table Analysis**
![Excel Pivot Tables](assets/excel-pivots.png)

**Tableau — Interactive Dashboard**
![Tableau Dashboard](assets/tableau-dashboard.png)

🔗 [View Interactive Dashboard on Tableau Public](#)

---

## Tools Used
`Excel (PivotTables, Marketing Formulas, Conditional Formatting)` · `Tableau (Dual-Axis Charts, Calculated Fields, Scatter Plots)`

---

## What I Learned

A short, honest paragraph on what was genuinely difficult or surprising — e.g. catching aggregation errors in pivot tables (summing percentages instead of averaging), understanding why CPC and Conversion Rate need separate axes to compare meaningfully, or what the data revealed about the CTR-to-conversion gap. This section should be written in your own words — it's what makes the project sound like real work, not a template.

---

## Repository Structure
