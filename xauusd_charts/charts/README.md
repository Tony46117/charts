# XAUUSD M1 news charts

Charts are grouped by news event, with every year (2016-2026) in one
folder so a single event can be studied across all years. Files sort
chronologically because each name starts with YYYYMMDD.

| folder | charts | event | source |
| --- | --- | --- | --- |
| `CPI/` | 126 | USD Core CPI m/m | US BLS |
| `NFP/` | 126 | USD Non-Farm Employment Change | US BLS |
| `PPI/` | 128 | USD Core PPI m/m | US BLS |
| `RETAIL/` | 128 | USD Core Retail Sales m/m | US Census |
| `PCE/` | 126 | USD Core PCE Price Index m/m | US BEA |
| `ADP/` | 128 | USD ADP Non-Farm Employment Change | ADP |
| `JOLTS/` | 129 | USD JOLTS Job Openings | US BLS |
| `ISM_MFG/` | 130 | USD ISM Manufacturing PMI | ISM |
| `ISM_SVC/` | 130 | USD ISM Services PMI | ISM |
| `FOMC/` | 87 | USD Federal Funds Rate | Federal Reserve |
| `GDP/` | 56 | USD GDP q/q | US BEA |
| `CLAIMS/` | 555 | USD Unemployment Claims | US DOL |
| `AUD/` | 130 | AUD Employment Change | ABS Labour Force |

Joint releases share one PNG (same minute, same candles). That PNG is
copied into every family folder it belongs to, so `CPI/` contains both
plain CPI charts and CPI+Claims etc. Use `index.csv` to see every
chart, its release date, local time, UTC time, and folders.

Label conventions: the header shows the release date, local release
time with its timezone abbreviation, and the same instant in UTC.
The bottom axis is UTC. The dashed line marks the release.

Verified 1759 images: filename date, header weekday/time/
timezone and a byte-exact re-render against the M1 data all match.

No chart for these configured releases (market closed, no M1 bars in the window):

- Friday 14 April 2017  ·  08:30 EDT  ·  12:30 UTC - Core CPI m/m + Core Retail Sales m/m
- Friday 10 April 2020  ·  08:30 EDT  ·  12:30 UTC - Core CPI m/m
- Friday 02 April 2021  ·  08:30 EDT  ·  12:30 UTC - Non-Farm Employment Change
- Friday 07 April 2023  ·  08:30 EDT  ·  12:30 UTC - Non-Farm Employment Change
- Friday 29 March 2024  ·  08:30 EDT  ·  12:30 UTC - Core PCE Price Index m/m
- Friday 03 April 2026  ·  08:30 EDT  ·  12:30 UTC - Non-Farm Employment Change

Source data is missing part of the plotted window in these charts,
so the candles there have a hole (the release itself is always in
range). `missing_minutes` in index.csv has the exact count:

- Thursday 14 January 2016  ·  11:30 AEDT  ·  00:30 UTC - Employment Change - 62 of 184 minutes missing
- Thursday 20 October 2016  ·  11:30 AEDT  ·  00:30 UTC - Employment Change - 62 of 184 minutes missing
- Thursday 19 October 2017  ·  11:30 AEDT  ·  00:30 UTC - Employment Change - 62 of 184 minutes missing
- Thursday 18 January 2018  ·  11:30 AEDT  ·  00:30 UTC - Employment Change - 62 of 184 minutes missing
- Thursday 18 October 2018  ·  11:30 AEDT  ·  00:30 UTC - Employment Change - 62 of 184 minutes missing
- Thursday 24 January 2019  ·  11:30 AEDT  ·  00:30 UTC - Employment Change - 63 of 184 minutes missing
- Thursday 21 February 2019  ·  11:30 AEDT  ·  00:30 UTC - Employment Change - 62 of 184 minutes missing
- Thursday 19 December 2019  ·  11:30 AEDT  ·  00:30 UTC - Employment Change - 63 of 184 minutes missing
- Thursday 23 January 2020  ·  11:30 AEDT  ·  00:30 UTC - Employment Change - 62 of 184 minutes missing
- Thursday 19 March 2020  ·  11:30 AEDT  ·  00:30 UTC - Employment Change - 62 of 184 minutes missing
- Wednesday 12 August 2020  ·  08:30 EDT  ·  12:30 UTC - Core CPI m/m - 62 of 184 minutes missing
- Thursday 19 November 2020  ·  11:30 AEDT  ·  00:30 UTC - Employment Change - 62 of 184 minutes missing
- Thursday 21 January 2021  ·  11:30 AEDT  ·  00:30 UTC - Employment Change - 62 of 184 minutes missing
- Thursday 11 November 2021  ·  11:30 AEDT  ·  00:30 UTC - Employment Change - 124 of 184 minutes missing
- Thursday 20 January 2022  ·  11:30 AEDT  ·  00:30 UTC - Employment Change - 62 of 184 minutes missing
- Thursday 20 October 2022  ·  11:30 AEDT  ·  00:30 UTC - Employment Change - 62 of 184 minutes missing
- Thursday 09 March 2023  ·  08:30 EST  ·  13:30 UTC - Unemployment Claims - 13 of 184 minutes missing
- Thursday 14 September 2023  ·  08:30 EDT  ·  12:30 UTC - Unemployment Claims + Core PPI m/m + Core Retail Sales m/m - 10 of 184 minutes missing
- Thursday 19 October 2023  ·  11:30 AEDT  ·  00:30 UTC - Employment Change - 62 of 184 minutes missing
- Thursday 15 February 2024  ·  11:30 AEDT  ·  00:30 UTC - Employment Change - 62 of 184 minutes missing
- Thursday 17 October 2024  ·  11:30 AEDT  ·  00:30 UTC - Employment Change - 62 of 184 minutes missing
- Thursday 12 December 2024  ·  11:30 AEDT  ·  00:30 UTC - Employment Change - 14 of 184 minutes missing
- Friday 05 December 2025  ·  10:00 EST  ·  15:00 UTC - Core PCE Price Index m/m - 32 of 184 minutes missing
