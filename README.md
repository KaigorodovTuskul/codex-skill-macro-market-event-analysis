# Macro Market Event Analysis

A Codex skill for verifying and analyzing macroeconomic and market-moving events with current evidence, economic mechanisms, cross-asset data, causal transmission maps, historical analogues, and scenarios.

## What it does

- verifies the actor, instrument, amount, status, dates, and primary source behind a headline;
- separates announcements from implementation and correlation from credible causality;
- classifies monetary, fiscal, sovereign-financing, liquidity, regulatory, geopolitical, and supply shocks;
- traces first-order, second-order, and real-economy consequences;
- analyzes rates, bonds, currencies, equities, credit, commodities, gold, and cryptoassets;
- distinguishes DXY from bilateral exchange rates and finance-ministry operations from central-bank QE;
- builds timelines, pressure maps, cross-asset matrices, scenarios, and falsification criteria;
- clearly separates observation, theory, inference, market narrative, and forecast.

The skill scales from a short explanation to a formal evidence-backed report.

## Example tasks

- Verify a claim that a Treasury buyback is equivalent to quantitative easing and map its consequences.
- Explain how a central-bank decision may affect yields, currencies, equities, gold, oil, and cryptoassets.
- Reconstruct a market reaction around a policy announcement and test competing explanations.
- Assess whether a fall in DXY should change a specific cross rate such as CNY/RUB.
- Compare a current intervention with historical episodes and build base, amplification, reversal, and structural scenarios.
- Identify winners, losers, risks, leading indicators, and conditions that would invalidate the thesis.

## Installation

Clone the repository into the Codex skills directory:

```bash
git clone https://github.com/KaigorodovTuskul/macro-market-event-analysis.git ~/.codex/skills/macro-market-event-analysis
```

On Windows PowerShell:

```powershell
git clone https://github.com/KaigorodovTuskul/macro-market-event-analysis.git "$env:USERPROFILE\.codex\skills\macro-market-event-analysis"
```

Restart Codex after installation if the skill is not discovered immediately.

## Usage

Invoke it explicitly:

```text
Use $macro-market-event-analysis to verify this news, explain the transmission mechanism, and assess the consequences for rates, currencies, equities, commodities, and cryptoassets.
```

The skill also supports automatic discovery for relevant macroeconomic and market-event requests.

## Method

The workflow is evidence-led:

1. freeze the factual cutoff and verify the primary official release;
2. reconstruct the event timeline and pre-event baseline;
3. identify the actual balance-sheet, policy, supply, demand, or liquidity shock;
4. measure market moves over explicit windows and test alternative causes;
5. map transmission across assets, countries, sectors, and time horizons;
6. build causally distinct scenarios with triggers and falsification conditions;
7. deliver a verdict with nearby sources, confidence labels, and unresolved questions.

## Repository structure

```text
macro-market-event-analysis/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── causality-and-scenarios.md
    ├── cross-asset-and-fx.md
    ├── event-brief-template.md
    ├── source-map.md
    └── transmission-framework.md
```

`SKILL.md` contains the main routing and quality requirements. The reference files provide focused frameworks that are loaded only when relevant.

## Scope and limitations

This skill improves research discipline; it does not provide proprietary market data, guarantee causal identification, predict prices with certainty, or replace professional investment, legal, or regulatory advice. Data access and source availability depend on the tools available to the agent.
