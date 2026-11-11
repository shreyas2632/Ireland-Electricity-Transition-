# Methodology

## Objective
Assess whether Ireland can reach its 2030 renewable-electricity target, whether the current trend is sufficient, and what change is required.

## Data
Two open Ember datasets (via a Kaggle compilation): annual electricity generation by fuel and country (1990–2025), and monthly European wholesale prices. The price comparison uses Ireland and ten peer countries: Austria, Belgium, Czechia, Denmark, Finland, Italy, the Netherlands, Portugal, Spain and Sweden.

## Steps
1. Load source tables into Power BI and clean them into the model tables listed in `data-dictionary.md`.
2. Link tables through a country dimension (ISO3 code) and year/date keys.
3. Create DAX measures (see `measures.md`).
4. Build four pages, each answering one question and opening with KPI cards.
5. Pair each chart with its question: area/line for trends, bar for ranking, histogram for distribution, scatter for relationships.
6. Write the report and presentation from the dashboard findings.

## Design conventions
Green highlights Ireland and positive results; blue marks gaps. Red dashed line marks the 80% target.

## Projection logic
Projections are benchmarks, not forecasts: current share plus a constant annual gain (1.25 points a year recent; 2.9 points a year since the post-2020 low) compared with the 6.33 points a year required.
