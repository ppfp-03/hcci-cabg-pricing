# HCCI CABG pricing

Interactive pricing model for coronary artery bypass grafting (CABG) at Health City Cayman Islands.

**Live dashboard:** https://ppfp-03.github.io/hcci-cabg-pricing/

## What it shows

- Recommended price: **$45,000**, all-inclusive, with 100 places a year reserved for patients who cannot pay.
- Target segment: insured patients who live outside the Cayman Islands and whose insurer or employer would otherwise send them to a US hospital.
- Two levers (price, reserved places) and two filters (demand scenario, year). Gold marks the recommendation; every value is compared with it.

## How the numbers are computed

CABG profit = (price − $2,000 variable cost) × paying patients − 30% of the hospital's fixed costs. Demand is calibrated on the project plan (about 200 cases in year 1 and 450 in year 5 at around $50,000) and tested under two scenarios: segment demand based on patients' alternative prices, and low-sensitivity demand (elasticity 0.8 at $50,000). All figures are recomputed in the browser from the assumptions embedded in `index.html`.

## Source

Figures are derived from the Harvard Business School case 714-510, *Health City Cayman Islands* (2014). The case is not included in this repository.
