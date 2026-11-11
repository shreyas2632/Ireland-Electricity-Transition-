# Raw data

Original, unmodified source files for the dashboard. Compiled from [Ember](https://ember-energy.org/data/) open data and distributed via Kaggle:

> Ashik, Khalid. *European Energy: Generation, Prices & 2030 Targets*. Kaggle, 2026. <https://www.kaggle.com/datasets/dkhalidashik/european-energy-generation-prices-and-2030-targets>

| File | Description | Key columns |
|---|---|---|
| `europe_yearly_full_release_long_format.csv` | Ember yearly electricity data, long format: generation, capacity, demand and emissions by country, year and variable (1990 onward) | `Area`, `ISO 3 code`, `Year`, `Category`, `Subcategory`, `Variable`, `Unit`, `Value`, `YoY absolute change`, `YoY % change` |
| `european_wholesale_electricity_price_data_monthly.csv` | Monthly wholesale electricity prices by country (from 2015) | `Country`, `ISO3 Code`, `Date`, `Price (EUR/MWhe)` |
| `targets_download.xlsx` | Ember 2030 renewable targets. Sheets: `raw_data_long`, `sources`, `capacity_target_wide`, `share_target_wide` | `COUNTRY_CODE`, `TARGET_YEAR`, `FUEL_CATEGORY`, `METRIC`, `VALUE`, `SOURCE_ID` |

## How these relate to the model

These files are cleaned and joined into `../model/ireland_powerbi_model_data.xlsx` (country dimension, yearly generation, monthly and yearly prices, 2030 targets, Ireland fuel shift). See [`docs/data-dictionary.md`](../../docs/data-dictionary.md).

## Licence note

Raw files are third-party data and are **not** covered by this repository's MIT licence. Check the Ember and Kaggle terms before redistributing.
