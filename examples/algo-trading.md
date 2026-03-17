# Reconnaissance Briefing: Algorithmic Trading (Event-Driven, Energy Markets)

## Scope

Understand event-driven, strategic trading in niche markets (energy certificates, energy commodities). The core question: What knowledge and signals lead to good decisions — and can they be detected and acted on algorithmically? No high-frequency trading, no "get rich quick." First bot as a learning project, not a money machine.

## Prerequisites

- **Programming:** Available (Python proficiency)
- **Market knowledge:** Missing — understanding how markets work, why prices move on events, and what drives energy/certificate markets is a prerequisite. This is a **separate project** that should come first.
- **Statistics/math:** Partially available (engineering background helps)

**Early Warning:** Without market understanding, algorithmic trading becomes "automating nonsense." The prerequisite project should be prioritized.

## Inventory Check

**Already available:** Python proficiency, engineering statistics background, general interest in energy markets from professional context.

**Utilization:** Fully used — programming and stats are directly applicable. But energy market knowledge is surface-level, not tradeable.

**Diagnosis:** Substance gap — market understanding is genuinely missing, not just poorly connected. This confirms the prerequisite finding above.

## Landscape Map

**Knowledge Half-Life:** Medium (market mechanics are stable, specific strategies and tools change yearly)

**Briefing Expiry:** Valid until approx. 2027-06 (strategies and tools evolve yearly, people and books stay relevant longer)

**Topic Type:** Practice field

**Top Sources:**

| Person | Why Relevant | Grade |
|--------|-------------|-------|
| Ernest P. Chan | PhD Physics (Cornell), Ex-IBM/Morgan Stanley. Books specifically for retail traders, Python code included | A |
| Rishi K. Narang | "Inside the Black Box" — explains how professional quant funds work, no sales pitch | A |
| Larry Harris | "Trading and Exchanges" — market microstructure, how markets actually work | A |
| Michael Covel | "Trend Following" — systematic trend strategies across all markets | B |

**Top Works:**

| Work | Focus | Grade |
|------|-------|-------|
| "Quantitative Trading" — Chan (2nd ed.) | Building a retail algo-trading system from zero, Python/R code | A |
| "Algorithmic Trading" — Chan | Momentum, mean reversion, strategies with implementation | A |
| "Inside the Black Box" — Narang | Understanding quant systems (comprehension, not recipe) | A |
| "Trading and Exchanges" — Harris | Market microstructure — how markets really tick | A |
| "Advances in Financial ML" — de Prado | ML in trading, anti-overfitting, advanced | B |

**Communities:** QuantStart, r/algotrading, QuantConnect (platform + community)

**State of the Art:** Algo-trading in European energy markets is growing (EPEX SPOT, Nord Pool). AI/ML-based signal detection and NLP for event detection are state of the art at professional firms. Python frameworks and cloud backtesting are accessible for retail traders. Energy certificates as a market are very niche and likely too illiquid for classic algo-trading — better suited for informed manual decisions.

## Mistake Audit

| # | Mistake | Why Expensive | How to Avoid |
|---|---------|---------------|--------------|
| 1 | **Overfitting** — optimizing strategy perfectly for historical data | Looks brilliant in backtest, fails live. THE classic mistake | Out-of-sample testing, walk-forward analysis, few parameters |
| 2 | **Ignoring real costs** — transaction costs, slippage, spreads | 20% backtest return becomes -5% in reality | Factor in costs from the start, paper trading before live |
| 3 | **Too complex** — 10 conditions per trade | Overfitting variant, can't debug, can't explain | One simple rule usually beats five complex ones |
| 4 | **Set-and-forget** — bot runs, nobody watches | Markets change, strategy loses validity | Regular monitoring, defined abort criteria |
| 5 | **Starting without market understanding** — jumping straight to code | You automate nonsense | FIRST understand WHY something might work, THEN automate |

## 80/20 Focus

| Priority | Area | Why |
|----------|------|-----|
| **1** | Market logic (→ prerequisite project) | Why do prices move on certain events? Without this, everything else is pointless |
| **2** | Event detection & signal design | The core interest — which signals (regulatory, geopolitical) move energy markets? |
| **3** | Backtesting fundamentals | Test hypotheses without real money — but correctly (avoid overfitting) |
| 4 | Python/coding for trading | Already a coder — this is craft, not the core question |
| 5 | Risk management & position sizing | Only relevant when real money is in play |

## Learning Path

**Timeframe:** ~8–12 weeks (medium complexity, plus prerequisite project)

**Phase 1 (Week 1–2): Overview + Market Logic**
- Chan "Quantitative Trading" chapters 1–3 (overview, what's possible as a retail trader)
- In parallel: understand energy market structure — how does EPEX SPOT work?
- Decision: are energy certificates algo-tradeable or too illiquid?

**Phase 2 (Week 3–4): Event-Driven Concepts**
- Narang "Inside the Black Box" chapters on event-driven strategies
- Research: which events move energy prices? (regulation, weather, geopolitics)
- Formulate first signal hypothesis: "When X happens, Y moves"

**Phase 3 (Week 5–6): First Backtest**
- Set up QuantConnect or local Python environment
- Backtest simplest strategy (e.g., moving average on energy prices)
- Goal: not to make money, but to understand the process

**Phase 4 (Week 7–8): Evaluation**
- What did I learn? What's missing?
- Check against mistake audit: did I fall into a trap?
- Decision: continue, build market knowledge first, or both in parallel?

## Go/No-Go

| Criterion | Assessment |
|-----------|-----------|
| **Effort** | High — requires market knowledge + coding + strategy design. Not "done" in 4 weeks |
| **Risk** | Low with paper trading — no real money. Time investment is the main risk |
| **Fit** | Medium — fits interests (energy, coding, understanding systems), but needs the market knowledge prerequisite |
| **Timing** | Open — no time pressure, but no clear trigger either |

**Recommendation: Go with constraint** — The topic is compelling and fits the profile. But: prioritize the financial market knowledge project first (Priority 1 from 80/20), then build algo-trading on top of it. Otherwise you automate decisions whose foundation you don't yet understand.

**Dependency:** Financial Market Knowledge project → Algo-Trading project
