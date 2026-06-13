# Carbon Intensity API

The Carbon Intensity API is the official carbon intensity forecasting service for Great Britain, developed by the National Energy System Operator (NESO) in partnership with EDF, the University of Oxford, and WWF. It provides real-time, forecast, and historical carbon intensity data alongside generation mix information for GB electricity generation.

- **API Base URL:** https://api.carbonintensity.org.uk
- **Documentation:** https://carbon-intensity.github.io/api-definitions/
- **Website:** https://carbonintensity.org.uk/
- **GitHub:** https://github.com/carbon-intensity
- **License:** CC BY 4.0
- **Authentication:** None required

## Key Capabilities

- Real-time national carbon intensity (current 30-minute settlement period)
- 96+ hour forward forecasts for carbon intensity and generation mix
- Historical data queries (up to 14-day ranges for intensity, 30-day for statistics)
- 14 regional datasets aligned to DNO boundaries across Great Britain
- England, Scotland, and Wales country-level endpoints
- Postcode-level carbon intensity queries
- Generation mix by fuel type (gas, coal, nuclear, wind, solar, hydro, biomass, imports, other)

## Pricing

The API is provided free of charge with no authentication or registration required. NESO applies rate limiting at its discretion and may block high-volume callers per its Terms of Use.

## Profile

This repository contains an APIs.json 0.19 provider profile for the Carbon Intensity API, maintained by [API Evangelist](https://apievangelist.com).
