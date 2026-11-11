# Data dictionary

Tables in `data/model/ireland_powerbi_model_data.xlsx`. Row counts include the header row.


## Countries

Rows: 37

- `ISO3 Code`
- `Country`
- `In Generation Data`
- `In Price Data`
- `Is Peer`
- `Is Aggregate`

## Yearly Generation

Rows: 1284

- `ISO3 Code`
- `Country`
- `Year`
- `Bioenergy Share (%)`
- `Bioenergy (TWh)`
- `Coal Share (%)`
- `Coal (TWh)`
- `Gas Share (%)`
- `Gas (TWh)`
- `Hydro Share (%)`
- `Hydro (TWh)`
- `Nuclear Share (%)`
- `Nuclear (TWh)`
- `Other Fossil Share (%)`
- `Other Fossil (TWh)`
- `Other Renewables Share (%)`
- `Other Renewables (TWh)`
- `Renewables Share (%)`
- `Renewables (TWh)`
- `Solar Share (%)`
- `Solar (TWh)`
- `Total Generation (TWh)`
- `Wind Share (%)`
- `Wind (TWh)`
- `Missing Fuel Fields`

## Generation Mix

Rows: 11556

- `ISO3 Code`
- `Country`
- `Year`
- `Fuel`
- `Generation (TWh)`

## Monthly Prices

Rows: 3795

- `ISO3 Code`
- `Date`
- `Price (EUR/MWh)`
- `Year`
- `Month Number`

## Yearly Prices

Rows: 345

- `ISO3 Code`
- `Year`
- `Average Price (EUR/MWh)`
- `Months With Price`

## Country Scatter

Rows: 317

- `ISO3 Code`
- `Country`
- `Year`
- `Renewables Share (%)`
- `Average Price (EUR/MWh)`
- `Months With Price`

## Ireland vs Peers Monthly

Rows: 89

- `Date`
- `Year`
- `Month Number`
- `Ireland Price (EUR/MWh)`
- `Peer Average Price (EUR/MWh)`

## Targets 2030

Rows: 37

- `ISO3 Code`
- `Consumption Target (%)`
- `Consumption Target Source ID`
- `Generation Target Reported (%)`
- `Share Target Clean (%)`
- `Target Basis`
- `Note`

## Ireland 2030 Fuel Shift

Rows: 7

- `Fuel`
- `Share 2025 (%)`
- `Share 2030 Plan (%)`
- `Source ID`
- `Change (pts)`

## Calculation

Scratch sheet with the author's rough working for the pace calculations; not used as a model table.

