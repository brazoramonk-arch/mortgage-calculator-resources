# Free US mortgage calculator tools and rate data references

## Free Online Calculator/Tool

[**amortio.com**](https://amortio.com/) — Free US mortgage calculators using Freddie Mac PMMS data — https

## About

This repository documents resources related to free online calculators in the relevant niche. The main tool referenced is hosted at [https://amortio.com/](https://amortio.com/).

## Data Sources

The calculators referenced use authoritative data sources:

- US Bureau of Labor Statistics (BLS)
- US Census Bureau
- Internal Revenue Service (IRS)
- Energy Information Administration (EIA)
- Centers for Disease Control (CDC)
- National Center for Education Statistics (NCES)
- National Renewable Energy Laboratory (NREL)
- Various other .gov authoritative sources

## Methodology

Each calculator follows peer-reviewed or government-published formulas. Results should be used as estimates for general guidance — always consult licensed professionals for binding advice in YMYL areas (tax, finance, health, legal).

## License

Resources documented here link to free public tools. The tools themselves are subject to their own terms of use.

## Contributing

If you have suggestions for additional calculator resources or data sources to document, please open an issue or PR.

## How [Amortio](https://www.amortio.com/) Calculates

### Core Formula
M = P × [r(1+r)^n] / [(1+r)^n - 1]

Where:
- M = monthly payment
- P = principal (loan amount)
- r = monthly interest rate (annual / 12)
- n = number of payments (loan term × 12)

### PITI Breakdown
- **P**rincipal: amortizing portion
- **I**nterest: rate × balance / 12
- **T**axes: county effective property tax rate × home value / 12
- **I**nsurance: typically $1,200-2,400/year homeowners + PMI if LTV > 80%

### Loan Programs
- **Conventional** — 5-20% down, FICO 620+
- **FHA** — 3.5% down (FICO 580+) or 10% down (FICO 500-579), MIP for life if <10% down
- **VA** — 0% down for veterans/spouses, no PMI, funding fee 0.5-3.6%
- **USDA Rural** — 0% down for rural areas, income limits apply

### Affordability (28/36 Rule)
- Front-end DTI: housing costs ≤ 28% of gross monthly income
- Back-end DTI: total debt payments ≤ 36% of gross monthly income

## Authoritative Sources

- [Freddie Mac PMMS](https://www.freddiemac.com/pmms) — weekly rate survey
- [FRED Mortgage Rates](https://fred.stlouisfed.org/series/MORTGAGE30US)
- [FHFA Conforming Loan Limits](https://www.fhfa.gov/DataTools/Downloads/Pages/Conforming-Loan-Limits.aspx)
- [CFPB Owning a Home](https://www.consumerfinance.gov/owning-a-home/)
- [HUD Housing Programs](https://www.hud.gov/program_offices/housing)

Visit [https://www.amortio.com/](https://www.amortio.com/) for the interactive calculator.

