# AUDUSD M1 news charts

Charts are grouped by high-impact news event, covering January 2016
onward in one folder so a single event can be studied across years.
Files sort chronologically because each name starts with YYYYMMDD.
All images are 4156 x 2660 (2x the reference canvas).

| folder | charts | currency | event family | source |
| --- | --- | --- | --- | --- |
| `BUDGET/` | 5 | AUD | BUDGET | Australian Treasury |
| `BUILD_APPROVALS/` | 22 | AUD | BUILD_APPROVALS | ABS Building Approvals |
| `CAPEX/` | 18 | AUD | CAPEX | ABS Capital Expenditure |
| `CONSTRUCTION/` | 1 | AUD | CONSTRUCTION | ABS Construction Work Done |
| `CPI_M/` | 51 | AUD | CPI_M | ABS CPI |
| `CPI_Y/` | 48 | AUD | CPI_Y | ABS CPI |
| `CURRENT_ACCOUNT/` | 2 | AUD | CURRENT_ACCOUNT | ABS Balance of Payments |
| `EMPLOY/` | 129 | AUD | EMPLOY | ABS Labour Force |
| `GDP/` | 42 | AUD | GDP | ABS National Accounts |
| `MINUTES/` | 67 | AUD | MINUTES | RBA |
| `RATE/` | 81 | AUD | RATE | RBA |
| `RBA_FSR/` | 1 | AUD | RBA_FSR | RBA |
| `RBA_MPS/` | 31 | AUD | RBA_MPS | RBA |
| `RBA_PRESS/` | 12 | AUD | RBA_PRESS | RBA |
| `RBA_STMT/` | 111 | AUD | RBA_STMT | RBA |
| `RETAIL/` | 55 | AUD | RETAIL | ABS Retail |
| `SPEECH/` | 132 | AUD | SPEECH | RBA |
| `TRADE/` | 34 | AUD | TRADE | ABS Trade |
| `TRIMMED/` | 46 | AUD | TRIMMED | ABS CPI |
| `UNEMP/` | 129 | AUD | UNEMP | ABS Labour Force |
| `WPI/` | 23 | AUD | WPI | ABS Wage Price Index |

Joint releases share one PNG (same minute, same candles). That PNG
is copied into every family folder it belongs to. Use `index.csv`
for every chart's release date, local time, UTC time and folders.

The header shows the release date, local release time with its
timezone abbreviation, and the same instant in UTC. The bottom axis
is UTC. The light dashed line marks the release minute.

No chart for these configured releases (market closed / no M1 bars in the window):

- Saturday 18 May 2019  ·  11:30 AEST  ·  01:30 UTC - Parliamentary Elections
- Sunday 25 August 2019  ·  02:25 AEST  ·  16:25 UTC - RBA Gov Lowe Speaks
- Saturday 21 May 2022  ·  11:30 AEST  ·  01:30 UTC - Parliamentary Elections
- Saturday 03 May 2025  ·  11:30 AEST  ·  01:30 UTC - Parliamentary Elections

Charts where source data misses part of the window:

- Tuesday 18 October 2016  ·  08:10 AEDT  ·  21:10 UTC - RBA Gov Lowe Speaks - 6 of 184 minutes missing
- Wednesday 13 December 2017  ·  09:15 AEDT  ·  22:15 UTC - RBA Gov Lowe Speaks - 10 of 184 minutes missing
- Tuesday 01 May 2018  ·  14:30 AEST  ·  04:30 UTC - RBA Rate Statement - 6 of 184 minutes missing
- Wednesday 13 June 2018  ·  13:20 AEST  ·  03:20 UTC - RBA Gov Lowe Speaks - 10 of 184 minutes missing
- Friday 17 August 2018  ·  09:34 AEST  ·  23:34 UTC - RBA Gov Lowe Speaks - 6 of 184 minutes missing
- Thursday 15 October 2020  ·  08:45 AEDT  ·  21:45 UTC - RBA Gov Lowe Speaks - 21 of 184 minutes missing
- Wednesday 18 November 2020  ·  09:00 AEDT  ·  22:00 UTC - RBA Gov Lowe Speaks - 14 of 184 minutes missing
- Wednesday 10 March 2021  ·  09:00 AEDT  ·  22:00 UTC - RBA Gov Lowe Speaks - 6 of 184 minutes missing
- Friday 06 August 2021  ·  09:30 AEST  ·  23:30 UTC - RBA Gov Lowe Speaks - 9 of 184 minutes missing
- Friday 11 March 2022  ·  08:45 AEDT  ·  21:45 UTC - RBA Gov Lowe Speaks - 7 of 184 minutes missing
- Monday 28 November 2022  ·  10:00 AEDT  ·  23:00 UTC - RBA Gov Lowe Speaks - 45 of 184 minutes missing
- Friday 17 February 2023  ·  09:30 AEDT  ·  22:30 UTC - RBA Gov Lowe Speaks - 7 of 184 minutes missing
- Friday 09 February 2024  ·  09:30 AEDT  ·  22:30 UTC - RBA Gov Bullock Speaks - 8 of 184 minutes missing
- Thursday 15 February 2024  ·  09:00 AEDT  ·  22:00 UTC - RBA Gov Bullock Speaks - 6 of 184 minutes missing
- Thursday 12 December 2024  ·  11:30 AEDT  ·  00:30 UTC - Employment Change + Unemployment Rate - 10 of 184 minutes missing
- Friday 21 February 2025  ·  09:30 AEDT  ·  22:30 UTC - RBA Gov Bullock Speaks - 6 of 184 minutes missing
- Friday 10 October 2025  ·  09:00 AEDT  ·  22:00 UTC - RBA Gov Bullock Speaks - 11 of 184 minutes missing
