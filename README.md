# U.S. Treasury Crisis Radar 2026–2030

A bilingual static research dashboard that monitors **debt pricing and fiscal capacity**, rather than trying to predict a single "Treasury collapse date."

## Core thesis

> The key question is not *when will U.S. Treasuries collapse?* It is: **when does the United States move from being able to issue large amounts of debt to having to pay increasingly higher prices to issue new debt?**

## Indicators

### Five core market/fiscal indicators
1. 10Y Treasury yield
2. Treasury term premium
3. Interest / federal revenue
4. `g − r` (nominal growth minus effective financing cost)
5. Foreign Treasury demand

### Strategic-fiscal indicator
**Ferguson Limit** — a separate indicator inspired by historian Niall Ferguson's "Ferguson's Law." Ferguson defines the Ferguson limit as the point at which interest payments on national debt exceed defense spending. It is a strategic-fiscal warning signal, not a Treasury default indicator.

The site deliberately avoids treating the Ferguson Limit as a deterministic prediction of decline. Ferguson's formulation is a risk/precursor framework: when debt service consumes more resources than defense, a great power risks losing national power.

## Data status

- **Live:** Treasury Debt to the Penny is fetched in the browser.
- **Reference/baseline:** other indicators are currently displayed as analytical examples or benchmark values and are explicitly labeled as such.
- The project does **not** claim to be a fully real-time multi-source risk engine yet.

## Project structure

```text
.
├── index.html
├── README.md
├── .nojekyll
├── en/
│   └── index.html
├── zh/
│   └── index.html
└── assets/
    ├── app.js
    └── styles.css
```

## GitHub Pages

The project is intentionally framework-free: HTML/CSS/JavaScript only. It can be uploaded directly to a GitHub repository and published with GitHub Pages.

Recommended repository name:

`us-treasury-crisis-radar`

After uploading, enable **Settings → Pages → Deploy from a branch → main → / (root)**.

## Sources

- U.S. Treasury Fiscal Data — Debt to the Penny: https://fiscaldata.treasury.gov/datasets/debt-to-the-penny/
- U.S. Treasury interest rates: https://home.treasury.gov/resource-center/data-chart-center/interest-rates
- New York Fed Treasury Term Premia: https://www.newyorkfed.org/research/data_indicators/term-premia-tabs
- U.S. Treasury TIC system: https://home.treasury.gov/data/treasury-international-capital-tic-system
- CBO, The Budget and Economic Outlook: 2026 to 2036: https://www.cbo.gov/publication/62105
- Niall Ferguson / Hoover Institution, Ferguson's Law: https://www.hoover.org/research/fergusons-law
- Hoover working paper, Ferguson's Law: Debt Service, Military Spending, and Fiscal Limits of Power: https://www.hoover.org/sites/default/files/research/docs/fergusons-law.pdf

## Analytical thresholds

Thresholds in the dashboard are **analyst-created monitoring bands**, not official crisis boundaries. The project emphasizes trends, persistence, and cross-indicator confirmation.

## Disclaimer

Research and educational use only. Not investment, legal, tax, or financial advice.
