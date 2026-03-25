# 🏙️ Dubai Property Investment Comparator

A professional Excel workbook for analysing, comparing, and stress-testing Dubai real estate investment opportunities — covering acquisition costs, DLD fees, rental yields, mortgage financing, and all key investment KPIs.

---

## 📁 File

```
Dubai_Property_Investment_Comparator.xlsx
```

---

## 🗂️ Sheets Overview

| Tab | Purpose |
|-----|---------|
| 🏠 Property Comparison | Main sheet — compare up to 5 properties side by side |
| 🏦 Mortgage Calculator | Mortgage vs cash purchase analysis with full amortisation schedule |
| 📈 Cash Flow Projection | 10-year scenario model with charts |
| 📋 DLD Fee Guide | Dubai Land Department fee reference table |
| 📊 KPI Dashboard | One-page summary with comparison charts |

---

## 🏠 Sheet 1 — Property Comparison

The core of the workbook. Enter details for up to 5 properties and all KPIs calculate automatically.

### Sections

**① Property Details**
- Name, location, type, bedrooms, size (sq ft), purchase price
- Auto-calculates listed price per sq ft

**② Acquisition Costs (One-Time)**
- DLD Transfer Fee — 4% of purchase price (Dubai standard)
- Trustee Office Fee
- NOC Certificate
- Agent Commission — 2% standard
- Mortgage Registration Fee — 0.25% of loan
- Property Valuation Fee
- Furnishing / Fit-Out
- Auto-totals: Total Acquisition Costs + Total Investment

**③ Annual Holding Costs**
- Service charges (per sq ft per year)
- Property management fee (%)
- Maintenance & repairs
- Property insurance
- DEWA / utilities
- Annual mortgage payments
- Auto-total: Total Annual Holding Costs

**④ Rental Income**
- Gross annual rent
- Vacancy rate adjustment
- Management fee deduction
- Auto-calculates: Effective Rent & Net Annual Rental Income

**⑤ Key KPIs & Returns**

| KPI | Formula |
|-----|---------|
| Gross Rental Yield | Gross Rent ÷ Purchase Price |
| Net Rental Yield | (Net Rent − Holding Costs) ÷ Purchase Price |
| ROI | Net Cash Flow ÷ Total Investment |
| ROE | Net Cash Flow ÷ Equity (down payment) |
| Annual Net Cash Flow | Net Rent − Holding Costs |
| Monthly Cash Flow | Annual Cash Flow ÷ 12 |
| Payback Period | Total Investment ÷ Net Cash Flow |

**⑥ Capital Appreciation**
- Annual appreciation rate input
- Holding period (years)
- Projected future value, capital gain, total return
- Annualised Total ROI (rent + appreciation combined)

**⑦ Price Benchmarks**
- Actual price per sq ft
- Annual rent per sq ft
- Price-to-Rent Ratio
- Break-even Occupancy %

**⑧ Investment Score & Rank**
- Composite Score = (Net Yield × 40%) + (ROI × 40%) + (Appreciation Rate × 20%)
- Auto-ranks 1–5 (Rank 1 = best deal)
- Conditional colour scaling across all KPI rows

---

## 🏦 Sheet 2 — Mortgage Calculator

Side-by-side comparison of financing a property vs buying with cash.

### Inputs
- Purchase price, gross rent, holding costs, acquisition costs
- Down payment % (UAE minimum: 20% for expats, 15% for UAE nationals)
- Annual interest rate (typical UAE range: 3.5%–5.5%)
- Loan term (up to 25 years for expats, 30 for nationals)

### Mortgage Calculations
- Monthly payment (PMT formula)
- Annual mortgage payment
- Total interest paid over full term
- Total amount repaid

### KPIs Compared — Mortgage vs Cash

| KPI | What It Tells You |
|-----|------------------|
| Gross Rental Yield | Headline return on purchase price |
| Net Rental Yield | Return after holding costs |
| Cash-on-Cash (CoC) | Net cash flow ÷ cash actually deployed — best leverage measure |
| ROI | Net cash flow ÷ total cash invested |
| ROE | Net cash flow ÷ equity (down payment) — amplified by leverage |
| Leverage Multiplier | ROE ÷ Net Yield — >1x means financing is adding value |
| DSCR | Rent ÷ Mortgage Payment — >1.25x is considered safe by UAE banks |
| Payback Period | Years to recoup cash deployed |
| Break-even Occupancy | % occupancy needed to cover all costs |
| Interest as % of Rent | How much of your rent goes to the bank |

### Verdict Section
Plain-English ✅ / ⚠️ verdicts:
- Which route gives better Cash-on-Cash return
- Which route gives better ROE
- Whether DSCR is safe (>1.25x)
- Whether cash flow is positive or negative

### Amortisation Schedule
25-year annual breakdown showing:
- Principal paid per year
- Interest paid per year
- Running totals

### General Rule
> Mortgage wins when your interest rate < net rental yield (leverage amplifies returns).
> Cash wins when rates are high or you want guaranteed positive cash flow with no debt risk.

---

## 📈 Sheet 3 — Cash Flow Projection

10-year forward model for a single property scenario.

### Inputs
- Initial property value
- Annual rent (Year 1)
- Annual appreciation rate
- Annual holding costs
- Rent growth rate per year
- Vacancy rate

### Projected Metrics (Year 1–10)
- Property Value
- Gross Rent (grows annually)
- Effective Rent (after vacancy)
- Holding Costs (inflated 2%/year)
- Net Cash Flow
- Cumulative Cash Flow
- Capital Gain
- Total Wealth (CF + Capital Gain)
- Annual ROI
- Cumulative ROI

### Chart
Line chart with 3 series:
- 🔵 Net Cash Flow (annual)
- 🟢 Cumulative Cash Flow
- 🟡 Total Wealth

---

## 📋 Sheet 4 — DLD Fee Guide

Quick reference table for all Dubai Land Department and transaction fees:

| Fee | Rate |
|-----|------|
| DLD Transfer Fee | 4% of purchase price |
| Trustee Office Fee | AED 4,000 (residential) |
| NOC Certificate | AED 500–5,000 |
| Agent Commission | 2% of purchase price |
| Mortgage Registration | 0.25% of loan + AED 290 |
| Property Valuation | AED 2,500–3,500 |
| Title Deed (e-Title) | AED 580 |
| Service Charges | AED 12–35 per sq ft/year |
| Property Management | 5%–10% of annual rent |
| DEWA Security Deposit | AED 2,000 (apt) / AED 4,000 (villa) |
| Ejari Registration | AED 220 |

---

## 📊 Sheet 5 — KPI Dashboard

Auto-linked summary pulling live from the Property Comparison sheet.

- Side-by-side KPI table for all 5 properties
- Composite Score and Rank (1 = best)
- Bar chart: ROI vs Net Yield across all properties

---

## 🎨 Colour Coding System

| Colour | Meaning |
|--------|---------|
| 🔵 Blue text | User inputs — change these |
| ⚫ Black text | Formula calculations — do not edit |
| 🟢 Green text | Cross-sheet formula links |
| 🟡 Gold rows | Key KPI highlights |
| 🟢 Green background | Positive cash flow / good returns |
| 🔴 Red background | Costs / deductions / risk indicators |
| 🟡 Amber background | Warning / borderline metrics |

---

## 📐 Dubai Mortgage Rules (UAE Central Bank)

| Rule | Detail |
|------|--------|
| Max LTV (Expats, <AED 5M) | 80% (20% down) |
| Max LTV (UAE Nationals) | 85% (15% down) |
| Max LTV (>AED 5M) | 65–70% |
| Max Loan Term (Expats) | 25 years |
| Max Loan Term (Nationals) | 30 years |
| Max Age at Maturity | 65 (salaried) / 70 (self-employed) |
| Debt Burden Ratio (DBR) | Max 50% of monthly income |
| Typical Interest Rates | 3.5%–5.5% (variable/fixed) |

---

## 🔢 Version History

| Version | Date | Changes |
|---------|------|---------|
| v1.0 | 2026-03-24 | Initial build — Property Comparison sheet with 5 properties, DLD fees, KPIs, score & rank |
| v1.1 | 2026-03-24 | Added Cash Flow Projection sheet (10-year model + line chart) and DLD Fee Guide |
| v1.2 | 2026-03-24 | Added KPI Dashboard with bar chart |
| v1.3 | 2026-03-24 | Fixed cash flow chart — was rendering 30 single-point series instead of 3 line series |
| v1.4 | 2026-03-24 | Fixed KPI Dashboard column alignment (D3:H3 → C3:G3), rebuilt dashboard bar chart |
| v1.5 | 2026-03-24 | Added Mortgage Calculator sheet — mortgage vs cash comparison, DSCR, CoC, ROE, leverage multiplier, 25-year amortisation schedule, verdict section |

---

## 🚀 How to Use

1. Open the file in Microsoft Excel or Google Sheets
2. Go to **🏠 Property Comparison** — fill in blue cells for each property
3. Go to **🏦 Mortgage Calculator** — enter your financing details to compare routes
4. Check **📊 KPI Dashboard** for the overall winner
5. Use **📈 Cash Flow Projection** for long-term scenario planning

> **Tip:** All formula cells are black text — only edit blue cells. Green cells are cross-sheet links and will update automatically.

---

## 🛠️ Built With

- Microsoft Excel (openpyxl Python library)
- PMT / PPMT / IPMT functions for mortgage calculations
- Conditional formatting with colour scale rules
- Chart.js-style line and bar charts via openpyxl

---

## 📬 Project Notes

This workbook was built iteratively with Claude (Anthropic) as an AI-assisted financial modelling project for Dubai real estate investment analysis. Designed to UAE/Dubai market standards including DLD fee structures and UAE Central Bank mortgage regulations.
