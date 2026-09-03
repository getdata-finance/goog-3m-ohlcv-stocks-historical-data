# GOOG 3m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-211_728_rows-blue)](https://getdata.finance/datasets/goog) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/goog)

### -> [**Download the full GOOG dataset on getdata.finance**](https://getdata.finance/datasets/goog)

**GOOG 3m OHLCV stocks historical data** — ultra high-quality 3m OHLCV for **Alphabet**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 3m OHLCV** for **Alphabet** (US stocks)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/goog) · **211,728** `3m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3m` sample updated in sync

> **Sample on GitHub** · `GOOG_3m.csv` (18,480 rows, `2026-02-06` -> `2026-09-01`, 1.17 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/goog)** — **211,728** `3m` rows (full `1m`: 635,127), **11 timeframes**, `2020-02-25` -> `2026-09-01`.

## Download sample

**[GOOG_3m.csv](https://github.com/getdata-finance/goog-3m-ohlcv-stocks-historical-data/blob/main/GOOG_3m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/goog-3m-ohlcv-stocks-historical-data/main/GOOG_3m.csv)) · [GitHub Releases](https://github.com/getdata-finance/goog-3m-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/goog-3m-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/goog-3m-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/goog](https://getdata.finance/datasets/goog)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/goog))** |
|---|--:|---|
| Instrument | Alphabet · US stocks | Alphabet · US stocks |
| Timeframes | `3m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 3m rows | 18,480 | **211,728** |
| Size | 1.17 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/goog) |
| Period | `2026-02-06` -> `2026-09-01` | `2020-02-25` -> `2026-09-01` |
| File | `GOOG_3m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/goog) |
| Coverage report | — | [GOOG coverage](https://getdata.finance/coverage/goog) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/goog)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `3m` sample · [getdata.finance](https://getdata.finance/datasets/goog) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`GOOG_3m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-06T20:00:00+00:00 | 321.78 | 322.22 | 321.64 | 322.16 | 460 |
| 2026-02-06T20:03:00+00:00 | 322.16 | 322.53 | 321.93 | 322.49 | 446 |
| 2026-02-06T20:06:00+00:00 | 322.49 | 322.64 | 322.26 | 322.3 | 501 |
| 2026-02-06T20:09:00+00:00 | 322.3 | 322.76 | 322.3 | 322.57 | 518 |
| 2026-02-06T20:12:00+00:00 | 322.57 | 322.86 | 322.45 | 322.75 | 457 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-01T19:45:00+00:00 | 330.94 | 330.97 | 330.83 | 330.86 | 258 |
| 2026-09-01T19:48:00+00:00 | 330.86 | 331.15 | 330.75 | 331.11 | 385 |
| 2026-09-01T19:51:00+00:00 | 331.11 | 331.29 | 331.02 | 331.29 | 361 |
| 2026-09-01T19:54:00+00:00 | 331.29 | 331.73 | 331.19 | 331.39 | 597 |
| 2026-09-01T19:57:00+00:00 | 331.39 | 331.78 | 331.22 | 331.61 | 886 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('GOOG_3m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('GOOG_3m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('GOOG_3m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3min')
print(pf.stats())
```

## Download full data

The complete **GOOG** archive on **[getdata.finance](https://getdata.finance/datasets/goog)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **211,728** rows at `3m`, plus all other timeframes in the same ZIP.

**[-> Get the full GOOG dataset on getdata.finance](https://getdata.finance/datasets/goog)**

---
*GetData · GOOG 3m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/goog)*
