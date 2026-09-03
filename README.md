# USDCHF 1m OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-9_169_329_rows-blue)](https://getdata.finance/datasets/usdchf) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/usdchf)

### -> [**Download the full USDCHF dataset on getdata.finance**](https://getdata.finance/datasets/usdchf)

**USDCHF 1m OHLCV forex historical data** — ultra high-quality 1m OHLCV for **US Dollar / Swiss Franc**. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1m OHLCV** for **US Dollar / Swiss Franc** (Forex)
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/usdchf) · **9,169,329** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `USDCHF_1m.csv` (55,440 rows, `2026-07-09` -> `2026-09-02`). **Full archive on [getdata.finance](https://getdata.finance/datasets/usdchf)** — **9,169,329** `1m` rows, **11 timeframes**, `2001-11-28` -> `2026-09-02`.

## Download sample

**[USDCHF_1m.csv](https://github.com/getdata-finance/usdchf-1m-ohlcv-forex-historical-data/blob/main/USDCHF_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/usdchf-1m-ohlcv-forex-historical-data/main/USDCHF_1m.csv))

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/usdchf))** |
|---|--:|---|
| Instrument | US Dollar / Swiss Franc · Forex | US Dollar / Swiss Franc · Forex |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 55,440 | **9,169,329** |
| Period | `2026-07-09` -> `2026-09-02` | `2001-11-28` -> `2026-09-02` |
| File | `USDCHF_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/usdchf) |
| Coverage report | — | [USDCHF coverage](https://getdata.finance/coverage/usdchf) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/usdchf)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes**:

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples refreshed weekly, in sync with getdata.finance.

## Data preview

First and latest rows from the GitHub sample **`USDCHF_1m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-09T13:32:00+00:00 | 0.79408 | 0.79409 | 0.79398 | 0.79402 | 179 |
| 2026-07-09T13:33:00+00:00 | 0.79402 | 0.79427 | 0.79402 | 0.79421 | 144 |
| 2026-07-09T13:34:00+00:00 | 0.79421 | 0.79421 | 0.79397 | 0.7941 | 167 |
| 2026-07-09T13:35:00+00:00 | 0.7941 | 0.79418 | 0.79405 | 0.79418 | 177 |
| 2026-07-09T13:36:00+00:00 | 0.79418 | 0.79418 | 0.794 | 0.794 | 184 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-02T01:56:00+00:00 | 0.81303 | 0.81313 | 0.81303 | 0.81313 | 65 |
| 2026-09-02T01:57:00+00:00 | 0.81313 | 0.81313 | 0.81306 | 0.81311 | 69 |
| 2026-09-02T01:58:00+00:00 | 0.81311 | 0.81312 | 0.813 | 0.813 | 55 |
| 2026-09-02T01:59:00+00:00 | 0.813 | 0.813 | 0.81286 | 0.81286 | 113 |
| 2026-09-02T02:00:00+00:00 | 0.81286 | 0.81309 | 0.81285 | 0.813 | 147 |

## Schema

| Column | Description |
| --- | --- |
| `time` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
time,open,high,low,close,volume
```

## Download full data

Full USDCHF archive — 11 timeframes, gap-free, updated weekly:

**[-> Get the full USDCHF dataset on getdata.finance](https://getdata.finance/datasets/usdchf)**
