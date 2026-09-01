
# Digital Marketing Performance Dashboard
Cross-platform digital marketing analytics project (Excel + Tableau) analyzing  campaigns across Facebook, Google Ads, Instagram &amp; LinkedIn — pivot tables, ROI/CPC/CTR calculations, and dashboard visualization to identify top-performing campaigns and optimize ad spend.

---

## 📊 Dashboard Preview

![Tableau Dashboard](Screenshot%202026-09-01%20003113.png)

**Tableau Dashboard Preview**

---

## Problem Statement

Marketing teams often run paid campaigns across multiple platforms without having a unified view of campaign performance. This project analyzes campaign-level data to understand which platforms and campaigns are delivering the strongest results and where advertising spend may be inefficient.

The analysis focuses on four key business questions:

1. Which platform delivers the best ROI?
2. Which platforms are more cost-efficient based on CPC and conversion performance?
3. Which individual campaigns are performing best and worst?
4. Where is high advertising spend not translating into strong returns?

---

## Dataset

- **40 campaign records**
- **4 advertising platforms:** Facebook, Google Ads, Instagram, LinkedIn
- **12 campaign types**
- **Period:** January – March 2026
- **Currency:** Indian Rupees (₹)
- Dataset is **simulated** and created for portfolio/project demonstration purposes.

### Metrics Analyzed

- Impressions
- Reach
- Clicks
- CTR (%)
- Ad Spend (INR)
- Conversions
- Conversion Rate (%)
- CPC (INR)
- ROI (x)

---

## Methodology

The analysis was completed using **Microsoft Excel** and **Tableau**.

### Excel Analysis

Excel was used to organize the campaign data and create PivotTables for platform-level and campaign-level analysis.

Key calculations included:

- `CTR (%) = Clicks / Impressions × 100`
- `Conversion Rate (%) = Conversions / Clicks × 100`
- `CPC (INR) = Ad Spend / Clicks`
- `ROI (x) = Revenue / Ad Spend`

For PivotTable analysis:

- **Sum** was used for volume metrics such as Spend, Clicks, Impressions, and Conversions.
- **Average** was used for rate-based metrics such as CTR, Conversion Rate, CPC, and ROI where appropriate.

This helped avoid misleading results caused by incorrectly summing percentage or ratio-based metrics.

### Tableau Analysis

The Excel analysis was then visualized in Tableau to make campaign performance easier to interpret.

The dashboard includes:

- Platform performance comparison
- CPC vs. Conversion Rate analysis
- Campaign ROI ranking
- Spend vs. ROI scatter plot
- Top- and bottom-performing campaign identification
- Calculated ranking using `RANK()`

---

## 📈 Key Findings

### Platform Performance

| Platform | Avg. ROI | Avg. CPC (INR) |
|---|---:|---:|
| Facebook | **10.41x** | ₹108 |
| Google Ads | 9.14x | ₹94 |
| Instagram | 8.52x | **₹80** |
| LinkedIn | 7.01x | ₹159 |

### Key Insight

**Facebook** delivered the highest average ROI at **10.41x**, making it the strongest-performing platform in the dataset.

**Instagram** had the lowest average CPC at **₹80**, making it the most cost-efficient platform for generating clicks.

**LinkedIn** had the highest CPC at **₹159** and the lowest average ROI at **7.01x**. However, its higher conversion performance suggests it may still be useful for targeted, high-value B2B campaigns rather than high-volume advertising.

---

## 🏆 Top-Performing Campaigns

| Campaign | ROI | Conversions |
|---|---:|---:|
| Lead Gen – Carousel | **78.9x** | 529 |
| B2B Lead Gen | 41.5x | 271 |
| Search – Generic Keywords | 37.2x | 379 |
| Display Remarketing | 34.3x | 144 |

### ⚠️ Weakest Campaign

**Thought Leadership Article**

- ROI: **1.99x**
- Ad Spend: **₹32,541**
- Conversions: **55**

This campaign represents a potential area for optimization because it combines relatively high spend with significantly lower returns compared with the strongest campaigns.

---

## 💡 Business Insights

The analysis shows that campaign performance differs significantly by both **platform and campaign type**.

### 1. Prioritize high-ROI campaigns

Lead-generation and conversion-focused campaigns produced some of the strongest ROI values in the dataset.

### 2. Monitor high-spend, low-return campaigns

Campaigns with relatively high advertising spend but weak ROI should be reviewed before additional budget is allocated.

### 3. Consider platform-specific objectives

The cheapest platform is not necessarily the platform with the highest ROI.

For example:

- Instagram → Lowest CPC
- Facebook → Highest average ROI
- LinkedIn → Higher CPC but potentially useful for targeted B2B campaigns

This highlights the importance of evaluating multiple KPIs rather than using CPC alone to make budget decisions.

---

## 📊 How This Project Solves the Problem

The dashboard converts campaign-level advertising data into actionable marketing insights.

### Which platform performs best?

**Facebook**, with an average ROI of **10.41x**, is the strongest platform based on the dataset.

### Which platform is most cost-efficient?

**Instagram** has the lowest average CPC at **₹80**, making it the most cost-efficient platform for clicks.

### Which campaigns perform best?

**Lead Gen – Carousel** is the strongest campaign with **78.9x ROI** and **529 conversions**.

### Where should marketers investigate inefficient spending?

The **Spend vs. ROI scatter plot** helps identify campaigns where relatively high spending is associated with weaker returns.

This allows a marketing team to quickly identify campaigns that may require:

- Budget reduction
- Creative changes
- Audience optimization
- Campaign restructuring
- Testing before additional investment

---

## 🎯 Recommendation

Based on the patterns in the dataset, marketing teams should consider reallocating part of the budget from weaker campaigns toward campaigns with consistently stronger ROI and conversion performance.

In particular:

- Increase focus on high-performing lead-generation campaigns.
- Continue testing **Facebook** due to its strongest average ROI.
- Use **Instagram** where low CPC and efficient traffic generation are important.
- Treat **LinkedIn** as a more targeted B2B channel rather than simply optimizing for low CPC.
- Review or redesign campaigns such as **Thought Leadership Article** before increasing their budgets.

> **Note:** The dataset is simulated. These recommendations demonstrate the analytical decision-making process that could be applied to real advertising data.

---

## 📷 Project Screenshots

### Tableau Dashboard

![Tableau Dashboard](Screenshot%202026-09-01%20003113.png)

**[Open Tableau Dashboard Screenshot](Screenshot%202026-09-01%20003113.png)**

### Excel Pivot Table Analysis

![Excel Pivot Tables](Screenshot%202026-09-01%20190137.png)

**[Open Excel Pivot Table Screenshot](Screenshot%202026-09-01%20190137.png)**

---

## 📁 Project Files

### Excel Analysis

[**Download / View Excel Dashboard & Pivot Analysis**](Digital_Marketing_Performance_Dashboard.xlsx)

Contains the campaign dataset, calculations, PivotTable analysis, and supporting Excel work.

### Tableau Workbook

[**Open Tableau Workbook (.twb)**](Digital%20marketing%20performance%20dashboard.twb)

Contains the Tableau dashboard, calculated fields, charts, rankings, and visual analysis.

### Dashboard Screenshot

[**View Tableau Dashboard Screenshot**](Screenshot%202026-09-01%20003113.png)

### Excel Screenshot

[**View Excel Pivot Table Screenshot**](Screenshot%202026-09-01%20190137.png)

---

##  Tools Used

`Microsoft Excel` · `PivotTables` · `Calculated Metrics` · `Conditional Formatting` · `Tableau` · `Calculated Fields` · `RANK()` · `Data Visualization`

---

##  What I Learned

This project helped me understand how marketing KPIs should be analyzed together rather than individually. One of the important lessons was that metrics such as CTR, Conversion Rate, CPC, and ROI should not be treated in the same way when creating PivotTables. I also learned how Tableau can turn spreadsheet-based analysis into a more interactive visual story. Comparing CPC with Conversion Rate showed me that the cheapest source of clicks is not always the most effective source of conversions, while the Spend vs. ROI analysis helped me understand how dashboards can support practical budget allocation decisions.

---

## 📂 Repository Structure

```text
digital-marketing-performance-dashboard/
│
├── Digital marketing performance dashboard.twb
├── Digital_Marketing_Performance_Dashboard.xlsx
├── README.md
├── Screenshot 2026-09-01 003113.png
└── Screenshot 2026-09-01 190137.png
