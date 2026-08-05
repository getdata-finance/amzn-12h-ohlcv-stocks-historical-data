# AMZN 12h OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-3_091_rows-blue)](https://getdata.finance/datasets/amzn) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/amzn)

### -> [**Download the full AMZN dataset on getdata.finance**](https://getdata.finance/datasets/amzn)

**AMZN 12h OHLCV us stocks historical data** — ultra high-quality 12h OHLCV for **AMZN**. US equity cash and extended sessions — institutional-style OHLCV candles for US stocks. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 12h OHLCV** for **AMZN** (US stocks)
- **US equity cash and extended sessions — institutional-style OHLCV candles for US stocks**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`12h`) · **9 timeframes** on [getdata.finance](https://getdata.finance/datasets/amzn) · **3,091** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `12h` sample updated in sync

> **Sample on GitHub** · `AMZN_12h.csv` (90 rows, `2026-03-24` -> `2026-07-31`). **Full archive on [getdata.finance](https://getdata.finance/datasets/amzn)** — **3,091** `1m` rows (~0.25 MB), **9 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W), `2011-05-09` -> `2026-07-31`.

## Download sample

**[AMZN_12h.csv](https://github.com/getdata-finance/amzn-12h-ohlcv-stocks-historical-data/blob/main/AMZN_12h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/amzn-12h-ohlcv-stocks-historical-data/main/AMZN_12h.csv)) · [GitHub Releases](https://github.com/getdata-finance/amzn-12h-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/amzn-12h-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/amzn-12h-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/amzn](https://getdata.finance/datasets/amzn)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/amzn))** |
|---|--:|---|
| Instrument | AMZN · US stocks | AMZN · US stocks |
| Timeframes | `12h` (sample) | **9** — 1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W |
| 1m rows | 90 | **3,091** |
| Size | 0.01 MB | ~0.25 MB |
| Period | `2026-03-24` -> `2026-07-31` | `2011-05-09` -> `2026-07-31` |
| File | `AMZN_12h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/amzn) |
| Coverage report | — | [AMZN coverage](https://getdata.finance/coverage/amzn) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`12h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/amzn)**, each full asset archive is delivered as a ZIP with **9 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **12H** · **3D** · **1W**

GitHub = `12h` sample · [getdata.finance](https://getdata.finance/datasets/amzn) = all **9** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `12h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AMZN_12h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-24T12:00:00+00:00 | 217.21 | 217.21 | 213.71 | 214.32 | 136803 |
| 2026-03-25T12:00:00+00:00 | 214.32 | 220.07 | 214.32 | 218.77 | 131996 |
| 2026-03-26T12:00:00+00:00 | 218.77 | 219.95 | 214.18 | 214.71 | 96240 |
| 2026-03-27T12:00:00+00:00 | 214.71 | 214.71 | 206.18 | 206.3 | 101327.918201916 |
| 2026-03-30T12:00:00+00:00 | 206.3 | 210.84 | 206.3 | 207.99 | 114806 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-27T12:00:00+00:00 | 239.53 | 243.07 | 238.4 | 238.87 | 75860.2710729179 |
| 2026-07-28T12:00:00+00:00 | 238.87 | 240.42 | 235.59 | 238.33 | 103799 |
| 2026-07-29T12:00:00+00:00 | 238.33 | 240.3 | 233.49 | 234.25 | 150873.8722484672 |
| 2026-07-30T12:00:00+00:00 | 234.25 | 247.25 | 234.25 | 243.52 | 84118 |
| 2026-07-31T12:00:00+00:00 | 243.52 | 280.71 | 243.52 | 278.85 | 91306 |

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

df = pd.read_csv('AMZN_12h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('AMZN_12h.csv', parse_dates=['datetime'])
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

df = pd.read_csv('AMZN_12h.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **AMZN** archive on **[getdata.finance](https://getdata.finance/datasets/amzn)** includes **9 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W) — **3,091** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full AMZN dataset on getdata.finance](https://getdata.finance/datasets/amzn)**

---
*GetData · AMZN 12h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/amzn) · 2026-08-05 UTC*
