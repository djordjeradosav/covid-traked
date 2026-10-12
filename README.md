# COVID-19 Tracker

An interactive dashboard showing live COVID-19 statistics worldwide and per country, built with React.

**React · Material-UI · Leaflet · Chart.js · disease.sh API**

## Features

- Worldwide and per-country totals for **cases, recoveries and deaths** (today and all-time)
- **Interactive world map** (Leaflet): circles sized by case count, and the map recenters on the selected country
- **Line graph** of new cases over time
- **Live table** of countries sorted by number of cases
- Toggle between cases / recovered / deaths

Data source: [disease.sh](https://disease.sh), an open COVID-19 API.

## Structure

| File | Description |
|---|---|
| `App.js` | State, data fetching, layout |
| `Map.js` | Leaflet map with per-country circles |
| `LineGraph.js` | Historical chart |
| `Table.js` | Countries ranked by cases |
| `InfoBox.js` | Stat cards |
| `util.js` | Sorting, formatting, map helpers |

> Source files only (`src/`). Drop them into a Create React App project with `@material-ui/core`, `react-leaflet`, `leaflet`, `react-chartjs-2`, `chart.js` and `numeral` installed.
