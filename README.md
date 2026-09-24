# PSX-2026-Corporate-Financial-Analytics-Dashboard

# 📊 PSX 2026 Financial Analytics | Power BI Corporate Intelligence Dashboard

## 🖼️ Dashboard Preview

![PSX Financial Dashboard Banner](https://github.com/Abdullahprobro/PSX-2026-Corporate-Financial-Analytics-Dashboard/blob/main/Screenshot%20(1039).png?raw=true)

---

## 1. Project Headline
**PSX 2026 Financial Analytics | Single-Page Power BI Dashboard for Blue-Chip Corporate Intelligence**

---

## 2. Description & Purpose
This project transforms raw, fragmented financial filings from major PSX-listed entities into a standardized, executive-grade Power BI report. The single-page dashboard enables C-suite executives, financial analysts, and market investors to track top-line revenue growth, net profitability, and earnings per share (EPS) across key economic sectors—all while eliminating common reporting distortions such as overlapping quarters and consolidated/unconsolidated double-counting.

---

## 3. Tech Stack
* **Power BI Desktop**: Data modeling, dynamic visual builds, slicer configuration, and report UI formatting.
* **DAX (Data Analysis Expressions)**: Custom financial measures (`Total Revenue`, `Total Net Profit`, `Net Profit Margin %`, `Average EPS`).
* **Power Query (M)**: Data extraction, transformation, schema normalization, and type enforcement.
* **Canva**: Custom-designed 1920x1080 (16:9 Widescreen) container UI layout for modular card design.
* **Microsoft Excel**: Underlying structured financial data source.

---

## 4. Data Source
**PSX Financial Dataset (2025–2026)**:
* **`PnL_Fact_Financials`**: Transactional fact table containing Revenue (PKR mn), Net Profit (PKR mn), Gross Profit, and EPS.
* **`Company_Master`**: Dimension table mapping tickers, companies, industries, sectors, and headquarters.
* **`Dim_Date`**: Custom DAX calendar dimension covering multi-year date horizons (2025–2026).

---

## 5. Feature Highlights
* **Star Schema Architecture**: Clean 1:* relationship model connecting dimension tables (`Company_Master`, `Dim_Date`) to core financial facts for optimized DAX performance.
* **Double-Counting Prevention Controls**: Dedicated slicer logic for `Reporting_Period_Type` (`Annual`, `9M`, `Half-Year`) and `Basis` (`Consolidated` vs `Unconsolidated`).
* **Custom Canva UI Layout**: Embedded 1920x1080 container wallpaper for modern, clean visual separation and card elevation.
* **Single-Page Executive Layout**: Consolidated top-level performance indicators, revenue leaderboards, and detailed company matrix analysis in a streamlined, unified view.

---

## 6. Business Problem
Financial filings on the Pakistan Stock Exchange present unique analytics challenges:
* **Period Overlaps**: Combining annual reports with 9M or quarterly filings in raw pivot tables causes severe double-counting of corporate earnings.
* **Accounting Entity Ambiguity**: Aggregating both consolidated parent figures and standalone unconsolidated subsidiary filings inflates market size estimates.
* **Unstandardized Sector Comparison**: Comparing capital-intensive energy producers against high-margin technology firms without proper margin scaling distorts investment decisions.

---

## 7. Goal of the Dashboard
* Standardize financial reporting metrics across top entities in Banks, Energy, Cement, Fertilizer, Tech, and Automobile sectors.
* Deliver instant visibility into corporate revenue scale vs. actual net retention on a single executive screen.
* Provide an interactive tool to evaluate corporate earnings per share and net profit margins across the PSX index.

---

## 8. Walkthrough of Key Visuals

### Executive Performance Overview
* **KPI Scorecards**: Top-level display of `Total Revenue`, `Total Net Profit`, and `Net Profit Margin %` with real-time responsive updates.
* **Revenue Leaderboard (Clustered Bar Chart)**: Ranks companies by overall top-line volume (`Total Revenue` by `Company_Name`).
* **Financial Matrix Table**: Granular breakdown displaying `Average EPS`, `Total Net Profit`, `Total Revenue`, and `Net Profit Margin %` for company-by-company audits.
* **Period & Basis Slicers**: Top control panel forcing unambiguous selections (e.g., `Annual (FY2026)` + `Consolidated`).

---

## 9. Business Impact & Insights
* **Zero Reporting Distortion**: Eliminates double-counting errors through forced period control, ensuring 100% data integrity for investor presentations.
* **Single-Screen Executive Efficiency**: Consolidates essential top-line metrics into a single screen for quick C-suite evaluation without menu navigation.
* **Sector Concentration Discovery**: Identifies core income drivers across the index, highlighting how Commercial Banks and Energy entities generate a major share of total exchange earnings.
