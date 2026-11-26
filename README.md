# River Trip Planner data

Formatted river data for the River Trip Planner app, refreshed about every 6 hours.
Each river has a folder (`salt/` = Upper Salt River, Arizona) with:

| File | What | Sources |
| --- | --- | --- |
| `flows.json` | Daily mean flow by year for the put-in gauge | USGS |
| `outlook.json` | Last 14 days of readings, 7 days at nearby gauges, NWS river forecast, SNOTEL | USGS, NOAA NWS, USDA NRCS |
| `extended.json` | 3-week and 3-month flow outlooks | NOAA Colorado Basin River Forecast Center (HEFS) |
| `snow.json`, `swe.png` | Snow water equivalent map and basin snowpack index | NOAA NOHRSC, USDA NRCS |
| `weather.json` | Typical weather by date, 7-day forecast, water temperature | NOAA (ACIS, NWS), NASA POWER, USGS |

`index.json` lists when each file was generated. The data comes from public agency services and is
provided as is; check the agencies for official forecasts and warnings. Not affiliated with
Recreation.gov or any agency.

This repo keeps a single commit that is replaced on every update.
