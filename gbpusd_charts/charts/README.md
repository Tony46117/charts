# GBPUSD M1 news charts

Charts are grouped by high-impact news event, covering January 2016
onward in one folder so a single event can be studied across years.
Files sort chronologically because each name starts with YYYYMMDD.
All images are 4156 x 2660 (2x the reference canvas).

| folder | charts | currency | event family | source |
| --- | --- | --- | --- | --- |
| `BOE_FSR/` | 6 | GBP | BOE_FSR | Bank of England |
| `BOE_MPS/` | 43 | GBP | BOE_MPS | Bank of England |
| `BOE_QF/` | 11 | GBP | BOE_QF | Bank of England |
| `BOE_RATE/` | 80 | GBP | BOE_RATE | Bank of England |
| `BOE_STMT/` | 91 | GBP | BOE_STMT | Bank of England |
| `BOE_VOTES/` | 86 | GBP | BOE_VOTES | Bank of England |
| `BUDGET/` | 16 | GBP | BUDGET | HM Treasury |
| `CLAIMS/` | 60 | GBP | CLAIMS | UK ONS |
| `CPI/` | 114 | GBP | CPI | UK ONS |
| `CURRENT_ACCOUNT/` | 16 | GBP | CURRENT_ACCOUNT | UK ONS |
| `EARNINGS/` | 45 | GBP | EARNINGS | UK ONS |
| `GDP/` | 92 | GBP | GDP | UK ONS |
| `MFG_PROD/` | 46 | GBP | MFG_PROD | UK ONS |
| `PMI_CONST/` | 32 | GBP | PMI_CONST | S&P Global / CIPS |
| `PMI_MFG/` | 88 | GBP | PMI_MFG | S&P Global / CIPS |
| `PMI_SVC/` | 90 | GBP | PMI_SVC | S&P Global / CIPS |
| `POLITICS/` | 34 | GBP | POLITICS | UK Parliament |
| `RETAIL/` | 81 | GBP | RETAIL | UK ONS |
| `SPEECH/` | 285 | GBP | SPEECH | Bank of England |

Joint releases share one PNG (same minute, same candles). That PNG
is copied into every family folder it belongs to. Use `index.csv`
for every chart's release date, local time, UTC time and folders.

The header shows the release date, local release time with its
timezone abbreviation, and the same instant in UTC. The bottom axis
is UTC. The light dashed line marks the release minute.

No chart for these configured releases (market closed / no M1 bars in the window):

- Sunday 01 October 2017  ·  10:00 BST  ·  09:00 UTC - Prime Minister May Speaks
- Saturday 19 October 2019  ·  14:50 BST  ·  13:50 UTC - Parliament Brexit Vote
- Sunday 17 October 2021  ·  14:05 BST  ·  13:05 UTC - BOE Gov Bailey Speaks
- Saturday 15 October 2022  ·  14:00 BST  ·  13:00 UTC - BOE Gov Bailey Speaks
- Sunday 09 July 2023  ·  08:30 BST  ·  07:30 UTC - BOE Gov Bailey Speaks
- Saturday 14 October 2023  ·  16:00 BST  ·  15:00 UTC - BOE Gov Bailey Speaks
- Saturday 23 August 2025  ·  17:25 BST  ·  16:25 UTC - BOE Gov Bailey Speaks
- Saturday 18 October 2025  ·  14:00 BST  ·  13:00 UTC - BOE Gov Bailey Speaks

Charts where source data misses part of the window:

- Monday 19 February 2018  ·  19:45 GMT  ·  19:45 UTC - BOE Gov Carney Speaks - 6 of 184 minutes missing
- Tuesday 13 December 2022  ·  11:00 GMT  ·  11:00 UTC - BOE Gov Bailey Speaks - 32 of 184 minutes missing
- Wednesday 12 June 2024  ·  07:00 BST  ·  06:00 UTC - GDP m/m - 6 of 184 minutes missing
