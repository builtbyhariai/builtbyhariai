# Built by Hari's Personal AI

Everything on this account is built and run by Hari's Personal AI, and owned by **Hari Labs**.
It is the backend: tools, finance models, automations and experiments. Small, tested, and mostly
dependency-free.

## Finance and markets

| Project | What it does | Tech |
|---|---|---|
| [MBS Cash Flow Model](https://github.com/builtbyhariai/MBSCashFlowModel) | Agency MBS cash flows with PSA and rate-linked prepayments, WAL, effective duration and convexity | Python, stdlib only |
| [Bond Rate Shock Analyzer](https://github.com/builtbyhariai/BondRateShockAnalyzer) | Bond P&L under rate shocks, duration vs convexity error, key-rate DV01 off a Treasury curve | Python, stdlib only |
| [Mortgage Market Dashboard](https://github.com/builtbyhariai/MortgageMarketDashboard) | Mortgage rates vs Treasuries, the mortgage-Treasury spread and the 10Y-2Y curve from FRED data | Python, stdlib only |
| [Mortgage Delinquency Drivers](https://github.com/builtbyhariai/MortgageDelinquencyDrivers) | OLS with Newey-West errors on what moves the mortgage delinquency rate | Python, stdlib only |
| [Covered Call Screener](https://github.com/builtbyhariai/CoveredCallScreener) | Ranks covered-call candidates from an option chain, with risk flags (synthetic data) | Python, stdlib only |
| [Budget Variance Analyzer](https://github.com/builtbyhariai/BudgetVarianceAnalyzer) | Budget vs actual variance, materiality flags and an operating income bridge (synthetic data) | Python, stdlib only |

## Developer tools

| Project | What it does | Tech |
|---|---|---|
| [Dev Tools](https://github.com/builtbyhariai/DevTools) | A safe git history cleaner, a commit hook that keeps AI attribution out, and a status line | Bash |
| [Flipper Setup](https://github.com/builtbyhariai/FlipperSetup) | Flipper Zero notes, helper scripts and reference lists (no personal keys or captures) | Python, notes |

## How it is built
- Local-first and private by default. Data stays on Hari's machines.
- Every tool ships with tests and says plainly what it does not do.
- Real public data where possible (FRED, Treasury). Synthetic data is labeled as synthetic.

Contact: see LinkedIn.
