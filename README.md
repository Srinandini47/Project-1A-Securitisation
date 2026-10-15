# Project-1A-Securitisation

A Power BI dashboard that models a loan securitisation: pool quality, expected credit loss (ECL), stress testing and the cash waterfall.

## Dashboard Pages
- **ECL by IFRS 9 stage:** loan count, pool balance, EAD, ECL and coverage
- **DPD:** days past due analysis
- **LOSS:** loss analysis
- **STRESS:** PD Stress Multiplier slider, with Stressed ECL and Stress Uplift %
- **VINTAGE:** vintage analysis
- **WATERFALL:** monthly cash waterfall from collections to equity

## Key Results (base case)
- Loan count: 500
- Total pool balance: 317.79M
- Total ECL: 11.66M (3.58% coverage)
- Total collections: 12.43M
- Equity residual: 753.54K

## Stress Test
The PD Stress Multiplier slider (1.00 to 2.00) lowers collections in the waterfall. At 2.00, collections drop sharply and the equity residual turns negative.

## Files
- `screenshot_2.pdf`: 2 screenshots of the waterfall page, with the stress slider at 1.00 and at 2.00
- `securitisation _dashboard - 01.pdf`: screenshots of the full Power BI dashboard (all pages)
- `securitisation _dashboard.pbix`: the working Power BI report. Download it and open it in Power BI Desktop to use the PD Stress Multiplier slider.

## Tools
Power BI, DAX

## Author
Srinandini
