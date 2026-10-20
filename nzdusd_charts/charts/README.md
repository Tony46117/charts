# NZDUSD M1 news charts

Charts are grouped by high-impact news event, covering January 2016
onward in one folder so a single event can be studied across years.
Files sort chronologically because each name starts with YYYYMMDD.
All images are 4156 x 2660 (2x the reference canvas).

| folder | charts | currency | event family | source |
| --- | --- | --- | --- | --- |
| `BUDGET/` | 5 | NZD | BUDGET | NZ Treasury |
| `BUSINESS_CONF/` | 30 | NZD | BUSINESS_CONF | ANZ / NZIER |
| `CPI/` | 41 | NZD | CPI | Stats NZ |
| `EMPLOY/` | 43 | NZD | EMPLOY | Stats NZ |
| `GDP/` | 42 | NZD | GDP | Stats NZ |
| `GDT/` | 33 | NZD | GDT | Global Dairy Trade |
| `INFL_EXP/` | 27 | NZD | INFL_EXP | RBNZ |
| `PMI_MFG/` | 1 | NZD | PMI_MFG | BusinessNZ |
| `POLITICS/` | 3 | NZD | POLITICS | NZ Electoral Commission |
| `PPI/` | 7 | NZD | PPI | Stats NZ |
| `RATE/` | 66 | NZD | RATE | RBNZ |
| `RBNZ_FSR/` | 8 | NZD | RBNZ_FSR | RBNZ |
| `RBNZ_MPS/` | 35 | NZD | RBNZ_MPS | RBNZ |
| `RBNZ_PRESS/` | 43 | NZD | RBNZ_PRESS | RBNZ |
| `RBNZ_STMT/` | 74 | NZD | RBNZ_STMT | RBNZ |
| `RETAIL/` | 16 | NZD | RETAIL | Stats NZ |
| `SPEECH/` | 66 | NZD | SPEECH | RBNZ |
| `TRADE/` | 3 | NZD | TRADE | Stats NZ |
| `UNEMP/` | 42 | NZD | UNEMP | Stats NZ |

Joint releases share one PNG (same minute, same candles). That PNG
is copied into every family folder it belongs to. Use `index.csv`
for every chart's release date, local time, UTC time and folders.

The header shows the release date, local release time with its
timezone abbreviation, and the same instant in UTC. The bottom axis
is UTC. The light dashed line marks the release minute.

No chart for these configured releases (market closed / no M1 bars in the window):

- Monday 16 March 2020  ·  08:00 NZDT  ·  19:00 UTC - Official Cash Rate + RBNZ Rate Statement

Charts where source data misses part of the window:

- Wednesday 18 May 2016  ·  10:45 NZST  ·  22:45 UTC - PPI Input q/q - 24 of 184 minutes missing
- Wednesday 25 May 2016  ·  10:45 NZST  ·  22:45 UTC - Trade Balance - 14 of 184 minutes missing
- Thursday 16 June 2016  ·  10:45 NZST  ·  22:45 UTC - GDP q/q - 15 of 184 minutes missing
- Friday 12 August 2016  ·  10:45 NZST  ·  22:45 UTC - Retail Sales q/q - 11 of 184 minutes missing
- Wednesday 17 August 2016  ·  10:45 NZST  ·  22:45 UTC - Employment Change q/q + PPI Input q/q + Unemployment Rate - 10 of 184 minutes missing
- Thursday 15 September 2016  ·  10:45 NZST  ·  22:45 UTC - GDP q/q - 6 of 184 minutes missing
- Tuesday 18 October 2016  ·  10:45 NZDT  ·  21:45 UTC - CPI q/q - 8 of 184 minutes missing
- Wednesday 02 November 2016  ·  10:45 NZDT  ·  21:45 UTC - Employment Change q/q + Unemployment Rate - 12 of 184 minutes missing
- Wednesday 30 November 2016  ·  11:00 NZDT  ·  22:00 UTC - RBNZ Gov Wheeler Speaks - 9 of 184 minutes missing
- Wednesday 07 December 2016  ·  11:00 NZDT  ·  22:00 UTC - RBNZ Gov Wheeler Speaks - 15 of 184 minutes missing
- Thursday 26 January 2017  ·  10:45 NZDT  ·  21:45 UTC - CPI q/q - 8 of 184 minutes missing
- Monday 20 February 2017  ·  10:45 NZDT  ·  21:45 UTC - PPI Input q/q - 116 of 184 minutes missing
- Thursday 20 April 2017  ·  10:45 NZST  ·  22:45 UTC - CPI q/q - 11 of 184 minutes missing
- Wednesday 03 May 2017  ·  10:45 NZST  ·  22:45 UTC - Employment Change q/q + Unemployment Rate - 11 of 184 minutes missing
- Monday 15 May 2017  ·  10:45 NZST  ·  22:45 UTC - Retail Sales q/q - 7 of 184 minutes missing
- Thursday 15 June 2017  ·  10:45 NZST  ·  22:45 UTC - GDP q/q - 10 of 184 minutes missing
- Tuesday 18 July 2017  ·  10:45 NZST  ·  22:45 UTC - CPI q/q - 6 of 184 minutes missing
- Monday 14 August 2017  ·  10:45 NZST  ·  22:45 UTC - Retail Sales q/q - 10 of 184 minutes missing
- Thursday 17 August 2017  ·  10:45 NZST  ·  22:45 UTC - PPI Input q/q - 8 of 184 minutes missing
- Thursday 21 September 2017  ·  10:45 NZST  ·  22:45 UTC - GDP q/q - 11 of 184 minutes missing
- Saturday 23 September 2017  ·  09:45 NZST  ·  21:45 UTC - Parliamentary Elections - 138 of 184 minutes missing
- Tuesday 17 October 2017  ·  10:45 NZDT  ·  21:45 UTC - CPI q/q - 9 of 184 minutes missing
- Wednesday 29 November 2017  ·  13:00 NZDT  ·  00:00 UTC - RBNZ Gov Spencer Speaks - 6 of 184 minutes missing
- Thursday 30 November 2017  ·  13:00 NZDT  ·  00:00 UTC - ANZ Business Confidence - 9 of 184 minutes missing
- Tuesday 19 December 2017  ·  13:00 NZDT  ·  00:00 UTC - ANZ Business Confidence - 11 of 184 minutes missing
- Friday 23 February 2018  ·  10:45 NZDT  ·  21:45 UTC - Retail Sales q/q - 6 of 184 minutes missing
- Wednesday 28 February 2018  ·  13:00 NZDT  ·  00:00 UTC - ANZ Business Confidence - 12 of 184 minutes missing
- Tuesday 13 March 2018  ·  12:45 NZDT  ·  23:45 UTC - RBNZ Gov Spencer Speaks - 10 of 184 minutes missing
- Thursday 15 March 2018  ·  10:45 NZDT  ·  21:45 UTC - GDP q/q - 17 of 184 minutes missing
- Thursday 21 June 2018  ·  10:45 NZST  ·  22:45 UTC - GDP q/q - 11 of 184 minutes missing
- Tuesday 17 July 2018  ·  10:45 NZST  ·  22:45 UTC - CPI q/q - 26 of 184 minutes missing
- Wednesday 01 August 2018  ·  10:45 NZST  ·  22:45 UTC - Employment Change q/q + Unemployment Rate - 10 of 184 minutes missing
- Friday 07 September 2018  ·  09:27 NZST  ·  21:27 UTC - RBNZ Gov Orr Speaks - 7 of 184 minutes missing
- Wednesday 07 November 2018  ·  10:45 NZDT  ·  21:45 UTC - Employment Change q/q + Unemployment Rate - 6 of 184 minutes missing
- Monday 26 November 2018  ·  10:45 NZDT  ·  21:45 UTC - Retail Sales q/q - 110 of 184 minutes missing
- Wednesday 28 November 2018  ·  11:00 NZDT  ·  22:00 UTC - RBNZ Gov Orr Speaks - 9 of 184 minutes missing
- Monday 25 February 2019  ·  10:45 NZDT  ·  21:45 UTC - Retail Sales q/q - 107 of 184 minutes missing
- Monday 24 February 2020  ·  10:45 NZDT  ·  21:45 UTC - Retail Sales q/q - 109 of 184 minutes missing
- Thursday 18 June 2020  ·  10:45 NZST  ·  22:45 UTC - GDP q/q - 6 of 184 minutes missing
- Thursday 17 September 2020  ·  10:45 NZST  ·  22:45 UTC - GDP q/q - 9 of 184 minutes missing
- Saturday 17 October 2020  ·  10:45 NZDT  ·  21:45 UTC - Parliamentary Elections - 141 of 184 minutes missing
- Wednesday 25 November 2020  ·  11:00 NZDT  ·  22:00 UTC - RBNZ Gov Orr Speaks - 13 of 184 minutes missing
- Thursday 17 December 2020  ·  10:45 NZDT  ·  21:45 UTC - GDP q/q - 15 of 184 minutes missing
- Friday 22 January 2021  ·  10:45 NZDT  ·  21:45 UTC - CPI q/q - 16 of 184 minutes missing
- Friday 26 February 2021  ·  12:30 NZDT  ·  23:30 UTC - RBNZ Gov Orr Speaks - 10 of 184 minutes missing
- Wednesday 21 April 2021  ·  10:45 NZST  ·  22:45 UTC - CPI q/q - 9 of 184 minutes missing
- Wednesday 04 August 2021  ·  10:45 NZST  ·  22:45 UTC - Employment Change q/q + Unemployment Rate - 12 of 184 minutes missing
- Monday 18 October 2021  ·  10:45 NZDT  ·  21:45 UTC - CPI q/q - 52 of 184 minutes missing
- Wednesday 02 February 2022  ·  10:45 NZDT  ·  21:45 UTC - Employment Change q/q + Unemployment Rate - 10 of 184 minutes missing
- Tuesday 19 April 2022  ·  08:00 NZST  ·  20:00 UTC - RBNZ Gov Orr Speaks - 10 of 184 minutes missing
- Wednesday 04 May 2022  ·  10:45 NZST  ·  22:45 UTC - Employment Change q/q + Unemployment Rate - 26 of 184 minutes missing
- Wednesday 04 May 2022  ·  11:00 NZST  ·  23:00 UTC - RBNZ Gov Orr Speaks - 12 of 184 minutes missing
- Thursday 26 May 2022  ·  09:10 NZST  ·  21:10 UTC - RBNZ Gov Orr Speaks - 14 of 184 minutes missing
- Monday 18 July 2022  ·  10:45 NZST  ·  22:45 UTC - CPI q/q - 6 of 184 minutes missing
- Friday 26 August 2022  ·  10:30 NZST  ·  22:30 UTC - RBNZ Gov Orr Speaks - 7 of 184 minutes missing
- Thursday 15 September 2022  ·  10:45 NZST  ·  22:45 UTC - GDP q/q - 7 of 184 minutes missing
- Tuesday 18 October 2022  ·  10:45 NZDT  ·  21:45 UTC - CPI q/q - 16 of 184 minutes missing
- Wednesday 02 November 2022  ·  10:45 NZDT  ·  21:45 UTC - Employment Change q/q + Unemployment Rate - 7 of 184 minutes missing
- Thursday 03 November 2022  ·  09:00 NZDT  ·  20:00 UTC - RBNZ Gov Orr Speaks - 7 of 184 minutes missing
- Thursday 15 December 2022  ·  10:45 NZDT  ·  21:45 UTC - GDP q/q - 14 of 184 minutes missing
- Thursday 16 March 2023  ·  10:45 NZDT  ·  21:45 UTC - GDP q/q - 12 of 184 minutes missing
- Wednesday 03 May 2023  ·  10:45 NZST  ·  22:45 UTC - Employment Change q/q + Unemployment Rate - 9 of 184 minutes missing
- Saturday 14 October 2023  ·  10:45 NZDT  ·  21:45 UTC - Parliamentary Elections - 139 of 184 minutes missing
- Wednesday 06 November 2024  ·  10:45 NZDT  ·  21:45 UTC - Employment Change q/q + Unemployment Rate - 108 of 184 minutes missing
- Wednesday 05 February 2025  ·  10:45 NZDT  ·  21:45 UTC - Employment Change q/q + Unemployment Rate - 6 of 184 minutes missing
- Monday 20 October 2025  ·  10:45 NZDT  ·  21:45 UTC - CPI q/q - 51 of 184 minutes missing
