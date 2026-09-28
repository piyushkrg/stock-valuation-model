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
## Day 4 — Comparable Company Analysis & Output

### Comparable Company Analysis

A comparable company analysis was performed to benchmark Pidilite Industries Ltd. against selected adhesive-related companies.

The selected peer companies are:

- Jyoti Resins
- Nikhil Adhesives
- HP Adhesives
- Hindustan Adhesive

The analysis uses two valuation multiples:

- P/E
- EV/EBITDA

### Peer Multiples

| Company | P/E | EV/EBITDA |
|---|---:|---:|
| Jyoti Resins | 12.07x | 7.51x |
| Nikhil Adhesives | 23.77x | 12.00x |
| HP Adhesives | 24.37x | 14.49x |
| Hindustan Adhesive | 11.19x | 7.01x |
| **Peer Median** | **17.92x** | **9.76x** |

The peer median multiples are used to estimate Pidilite's implied valuation.

For the P/E approach, the peer median P/E multiple is applied to Pidilite's earnings.

For the EV/EBITDA approach, Enterprise Value is calculated using EBITDA multiplied by the peer median EV/EBITDA multiple. Net debt is then adjusted to arrive at implied equity value.

The comparable-company data used in the model is based on the **04 September 2026** Value Research peer-comparison snapshot.

---

### Output Analysis

The Output sheet consolidates the valuation results from the DCF and comparable-company approaches.

The current model produces the following implied values per share:

| Valuation Method | Implied Value / Share |
|---|---:|
| DCF | ₹479.56 |
| DCF Sensitivity — Low | ₹345.95 |
| DCF Sensitivity — High | ₹805.93 |
| P/E Comps | ₹431.19 |
| EV/EBITDA Comps | ₹336.34 |
| Current Market Price | ₹1,517.20 |

The Output sheet also includes:

- DCF valuation summary
- Key valuation assumptions
- DCF valuation details
- Comparable-company valuation
- Football-field valuation analysis

The football-field analysis presents the valuation ranges generated by the different valuation approaches.

---

### Day 4 Completion

Completed:

- Comparable Company Analysis
- Peer selection and benchmarking
- P/E and EV/EBITDA analysis
- Peer median calculation
- Implied Pidilite valuation
- Consolidated Output sheet
- Football-field valuation analysis
