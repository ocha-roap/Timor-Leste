# Timor-Leste: El Niño Situation and Outlook

Draft dashboard by OCHA ROAP Information Management on the El Niño situation and outlook in Timor-Leste, for every administrative post.

**View it:** open `index.html` in a browser, or the GitHub Pages address of this repository once Pages is turned on.

## Pages

- **Overview:** FAO Combined Drought Index (CDI) and its indicators (rainfall, soil moisture, vegetation, rainfall forecast) by administrative post, with 2025 population and the ENSO / IOD outlook.
- **Risk and vulnerability:** FAO/UNOSAT INFORM sub-national risk model, with the indicator view of the UNOSAT FAO-DSS application.
- **Seasonal crop:** national crop calendar and expected impacts, and maize and rice planting and harvest months by suco.
- **Methodology:** how the CDI is built.

## Data

| Data | Source |
|---|---|
| Combined Drought Index, observation September 2026, forecast October–December 2026 | FAO Timor-Leste |
| INFORM sub-national risk model and administrative post boundaries (February 2025) | FAO and UNOSAT |
| Crop phenology by suco, seasons 1 and 2 | FAO |
| Population 2025 by administrative post | Populace |
| ENSO outlook, strength and probabilities (October 2026) | NOAA Climate Prediction Center |
| ENSO and IOD state (8 October 2026) | WMO |
| National crop calendar and expected impacts | OCHA, Asia and the Pacific Snapshot (28 August 2026) |
| Basemap | UN OCHA ROAP Mapbox style |

All data are embedded in `index.html`; nothing else needs to be uploaded. An internet connection is needed for the basemap, the map library (Mapbox GL JS), d3 and the Roboto font.

## Updating

The page is generated from the project source with `WebApp/scripts/build_standalone.ps1`. To update, rebuild it there and replace `index.html` in this repository.

## Disclaimer

Draft for review. The boundaries and names shown and the designations used on this map do not imply official endorsement or acceptance by the United Nations.
