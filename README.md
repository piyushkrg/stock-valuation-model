# stock-valuation-model
DCF &amp; Comparable Company Valuation Model built in Excel
## Project Progress

### Day 1 — Historical Financial Analysis

Completed the initial historical financial analysis for Pidilite Industries Ltd.

#### Historical Analysis
- Added historical Revenue data
- Calculated Revenue Growth %
- Added EBITDA
- Calculated EBITDA Margin %
- Added Depreciation & Amortisation
- Calculated EBIT
- Calculated EBIT Margin %
- Added historical Tax
- Calculated Tax Rate %
- Added Profit After Tax (PAT)
- Calculated PAT Margin %

#### Initial Valuation Inputs
- Added Revenue Growth assumption
- Added EBITDA Margin assumption
- Added Tax Rate assumption


### Day 2 — Working Capital & WACC

Extended the historical analysis and built the initial valuation assumptions.

#### Working Capital Analysis
- Added historical Working Capital
- Calculated Change in NWC
- Calculated Change in NWC as % of Revenue

#### Capex & NWC Assumptions
- Added Capex as % of Revenue assumption
- Added Change in NWC as % of Revenue assumption

#### WACC & Valuation Assumptions
- Added Risk-Free Rate
- Added Beta
- Added Market Return
- Calculated Cost of Equity using CAPM
- Calculated Cost of Debt
- Calculated Debt %
- Calculated Equity %
- Added Market Capitalisation
- Added Debt
- Calculated Total Capital
- Calculated WACC
- Added Terminal Growth assumption
### Day 3 — Forecast, DCF Valuation & Sensitivity Analysis

Extended the historical financial model into a forward-looking valuation framework.

#### 5-Year Forecast Model
- Built a 5-year forecast for FY2027E–FY2031E
- Forecasted Revenue using the Revenue Growth assumption
- Calculated Revenue Growth %
- Forecasted EBITDA using the EBITDA Margin assumption
- Calculated EBITDA Margin %
- Forecasted Depreciation & Amortisation using D&A as % of Revenue
- Calculated EBIT
- Applied the historical Tax Rate assumption
- Calculated Tax
- Calculated NOPAT (EBIT × (1 − Tax Rate))
- Forecasted Capital Expenditure as % of Revenue
- Forecasted Change in NWC as % of Revenue
- Calculated Free Cash Flow to Firm (FCFF)

#### DCF Valuation
- Built a 5-year Discounted Cash Flow valuation
- Calculated annual Discount Factors using WACC
- Calculated Present Value of forecast FCFF
- Calculated Terminal Value using the Gordon Growth Method
- Calculated Present Value of Terminal Value
- Calculated Enterprise Value
- Calculated Net Debt using Debt less Cash & Bank
- Calculated Equity Value
- Added Shares Outstanding
- Calculated Intrinsic Value per Share
- Added the latest available market price used for valuation comparison
- Calculated Upside / (Downside)
- Added the valuation date for transparency and reproducibility

#### DCF Base Case Output
- Enterprise Value: ₹48,925.91 Cr
- Net Debt: ₹118.31 Cr
- Equity Value: ₹48,807.60 Cr
- Shares Outstanding: 101.7766 Cr
- Intrinsic Value per Share: ₹479.56
- Market Price Used: ₹1,517.20
- Upside / (Downside): -68.39%

#### Sensitivity Analysis
- Built a two-way sensitivity analysis for Intrinsic Value per Share
- Tested WACC across 8.75%–10.75%
- Tested Terminal Growth across 4.0%–6.0%
- Calculated valuation under 25 WACC / Terminal Growth combinations
- Linked the base-case WACC and Terminal Growth directly to the DCF assumptions
- Applied conditional formatting to visualize valuation sensitivity

#### Sensitivity Range
- Lowest Implied Value per Share: ₹345.95
- Base Case Value per Share: ₹479.56
- Highest Implied Value per Share: ₹805.93
