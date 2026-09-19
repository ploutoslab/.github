<div align="center">

# Ploutos Lab

**A collective workspace for developing robust algorithmic trading systems.**

`research` → `backtest` → `paper` → `live` → `monitor`

![Focus](https://img.shields.io/badge/focus-algorithmic%20trading-0b3d2e?style=flat-square)
![Python](https://img.shields.io/badge/python-3.11+-1f6feb?style=flat-square&logo=python&logoColor=white)
![Status](https://img.shields.io/badge/status-active-2ea043?style=flat-square)

</div>

---

## What we build

Trading systems that survive contact with a live market: data pipelines that
don't silently gap, backtests that don't lie, and execution that fails safe.

| Area | What it covers |
| --- | --- |
| **Market data** | Ingestion, normalization, storage of tick / OHLCV / order book data |
| **Research** | Signal exploration, feature engineering, statistical validation |
| **Backtesting** | Event-driven simulation with realistic fees, slippage and latency |
| **Execution** | Order routing, position management, exchange connectivity |
| **Risk** | Position sizing, exposure limits, kill switches |
| **Ops** | Metrics, logging, alerting — a strategy you can't observe is a strategy you can't trust |

## How we work

- **Risk first.** Sizing and limits are designed before the entry logic.
- **Reproducible.** Same data + same config → same result. Every run is seeded and logged.
- **Paper before live.** Nothing touches real capital without a forward-test track record.
- **Suspicious of good results.** A great backtest is a hypothesis, not a conclusion.
- **Boring infrastructure.** Clever belongs in the alpha, not in the deployment scripts.

## Stack

`Python` · `PostgreSQL / TimescaleDB` · `Docker` · `Grafana` · exchange REST + WebSocket APIs

---

<div align="center">
<sub>Research and engineering only — nothing published here is financial advice.</sub>
</div>
