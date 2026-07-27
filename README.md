# energy-event-study
# Energy Event Study

## Overview

This project investigates how major energy market events influence commodity futures and energy-related equities using an event-study methodology.

Historical OPEC announcements, geopolitical shocks, supply disruptions and government interventions are analysed to measure abnormal returns, volatility changes and the persistence of market reactions.

---

## Assets Analysed

- Brent Crude
- WTI Crude
- Natural Gas
- Shell
- BP
- ExxonMobil
- Chevron
- TotalEnergies
- Energy ETF (XLE)
- Airlines ETF (JETS)

---

## Methodology

The project:

- Downloads historical price data using Yahoo Finance
- Calculates benchmark-adjusted returns
- Measures 1-, 3- and 5-day event returns
- Computes abnormal returns relative to the S&P 500
- Analyses volatility before and after events
- Performs statistical significance tests
- Produces summary tables and charts

---

## Example Outputs

<img width="2970" height="1765" alt="image" src="https://github.com/user-attachments/assets/b861929d-4f15-4ffb-994f-d6231fd31990" />

<img width="2970" height="2066" alt="image" src="https://github.com/user-attachments/assets/ae2e1db3-29e0-4cb7-aacb-ac40c7280c7a" />

<img width="4458" height="2367" alt="image" src="https://github.com/user-attachments/assets/d4da47dc-bd8a-4e07-8ffc-47e9e1eff33f" />

<img width="3859" height="1886" alt="image" src="https://github.com/user-attachments/assets/e66fd0db-c851-47f8-bb0a-3a673a41d7f0" />


---

## Technologies

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- yfinance

---

## Future Improvements

- Expand the event database to 40+ events
- Add intraday price analysis
- Extend the framework to metals and LNG markets
