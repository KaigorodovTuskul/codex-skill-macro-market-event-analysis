---
name: macro-market-event-analysis
description: Verify and analyze macroeconomic, fiscal, monetary, geopolitical, and market-moving events using current primary sources, economic theory, cross-asset data, causal transmission maps, and scenarios. Use when news may affect interest rates, bonds, currencies, equities, commodities, cryptoassets, credit, liquidity, companies, countries, or the real economy.
---

# Macro Market Event Analysis

## Purpose

Turn a market-moving headline into a verified, mechanism-based assessment. Establish what actually happened, distinguish announcement from implementation, measure the market reaction, identify competing explanations, trace first- and second-order consequences, and state what would confirm or reverse the thesis.

The output may be a short explanation, event brief, pressure map, cross-asset table, scenario analysis, presentation, or formal report. Match depth to the request.

For standard or deep work, read `references/evidence-pack.md` and keep the minimum source, market-data, calculation, and scenario records needed to reproduce the conclusion. A short answer does not require a full research pack.

## Start with verification

Read `references/event-brief-template.md` and freeze the factual cutoff. Read `references/source-map.md` before broad external research. Resolve:

- exact actor, legal authority, instrument, amount, maturity, currency, and jurisdiction;
- announcement, effective, transaction, settlement, and publication dates;
- whether the action is proposed, scheduled, executed, completed, or merely discussed;
- whether the source describes a stock, flow, ceiling, target, authorization, or actual observation;
- what changed relative to the prior rule or schedule;
- whether the institution is a finance ministry, central bank, regulator, legislature, or market participant.

Do not describe an announced future operation as an intervention already completed. Do not treat debt-management buybacks by a finance ministry as central-bank quantitative easing unless the balance-sheet and financing facts support that conclusion.

## Build an event timeline and market baseline

Use the narrowest possible timestamps. Record:

1. pre-event conditions and existing expectations;
2. first credible leak or publication;
3. official release and exact wording;
4. market reaction in relevant trading hours;
5. implementation and settlement when they occur;
6. later policy, data, or positioning changes.

Measure assets over explicit windows: intraday, close-to-close, week-to-date, month-to-date, or since a defined prior event. Never quote a percentage without its starting point, price convention, timezone, and source.

Use data that was available at the stated cutoff. Record the series vintage and release timestamp for revised macro data. For securities, state whether the measure is price or total return, clean or dirty price, local or base currency, spot or futures, adjusted or unadjusted, and how holidays, rolls, coupons, dividends, and corporate actions were handled. Do not use a later revision to explain what the market knew at the event time unless it is labeled as hindsight.

## Classify the shock

Read `references/transmission-framework.md`. Identify the primary shock before discussing assets:

- monetary policy or central-bank balance sheet;
- fiscal policy, borrowing, or sovereign debt management;
- inflation, growth, employment, or productivity data;
- liquidity, collateral, funding, positioning, or market plumbing;
- regulation, sanctions, trade, or capital controls;
- commodity, supply-chain, technology, geopolitical, or credit event.

An event can contain several shocks. Separate them rather than assigning one label to the entire story.

## Test causality rather than narrating correlation

Read `references/causality-and-scenarios.md`. Compare the event timestamp with price, yield, volume, volatility, curve, spread, and positioning changes. Check simultaneous releases, speeches, auctions, data surprises, geopolitical news, option expiries, and technical positioning.

Use these verdicts:

- **confirmed mechanism:** timing, surprise, direction, and controls support the link;
- **plausible contributor:** mechanism and timing fit, but competing causes remain;
- **market narrative:** widely repeated explanation without adequate identification;
- **contradicted:** dates, instrument, magnitude, or observed reaction do not fit.

Rate conclusion confidence as `high`, `moderate`, `low`, or `unresolved` from source quality, independence, timing fit, mechanism fit, controls and contradictions. Confidence is not the same as the number of citations.

Do not claim that one headline caused every asset move. Distinguish anticipated policy from genuine surprise and announcement effects from implementation effects.

When using a historical analogue, define the matching variables before selecting the episode: shock type, surprise, policy regime, inflation/growth regime, valuation, positioning, liquidity, and implementation. Report important mismatches and avoid choosing only episodes that support the thesis.

## Trace the transmission

Build a pressure map from the initial shock through intermediate variables to exposed assets and economies:

`event -> supply/demand or balance sheet -> liquidity / term premium / expected policy -> rates and currency -> asset prices and financing -> companies, households, trade, inflation, and growth`

For each arrow state:

- direction and mechanism;
- time horizon;
- conditions required;
- strength of evidence;
- offsetting forces;
- observable indicator that would confirm or reject it.

Separate immediate market mechanics, days-to-weeks positioning, months-long financing effects, and quarterly real-economy consequences.

## Analyze rates, assets, and currencies correctly

Read `references/cross-asset-and-fx.md` when the event crosses asset classes or currencies.

At minimum distinguish:

- bond price from yield;
- nominal yield from real yield, expected inflation, and term premium;
- policy-rate expectations from long-end supply and liquidity effects;
- broad dollar indices from bilateral exchange rates;
- spot moves from hedged returns and funding costs;
- gold's real-yield, dollar, risk, and reserve-demand channels;
- cryptoasset liquidity, leverage, regulation, adoption, and risk-appetite channels;
- commodity price effects from producer-currency and importer-currency effects.

A fall in DXY means the dollar weakened against the index basket, not against every currency. Derive each cross rate from its two bilateral legs and analyze the local currency's own drivers.

## Use theory as a mechanism, not decoration

Apply only theory that changes the explanation or scenario. Possible tools include duration and convexity, term-premium decomposition, portfolio balance, liquidity preference, safe-asset demand, covered and uncovered interest parity, fiscal and monetary interaction, wealth and collateral effects, credit transmission, exchange-rate pass-through, and balance-of-payments adjustment.

State assumptions and known empirical limits. A textbook sign is conditional, not a forecast.

## Build scenarios and consequences

Use a small set of causally distinct scenarios:

- base case: the announced mechanism works as intended;
- amplification: positioning, liquidity, policy reaction, or feedback loops strengthen it;
- reversal: implementation is smaller, offset by issuance or other policy, or the initial move was crowded;
- structural case when the event can alter regimes, institutions, or long-run capital allocation.

For each scenario show trigger, affected variables, winners and losers, time horizon, leading indicators, and falsification conditions. Separate directional pressure from a point forecast.

Attach probabilities only when the evidence supports them. State the as-of date, base rates or anchors, and assumptions; make mutually exclusive scenario probabilities sum to 100%. Do not disguise an unsupported point target as a probability-weighted forecast.

## Institutional controls

- Use public, licensed, user-provided, or otherwise authorized information. Do not seek or infer material non-public information; if supplied information may be confidential or price-sensitive, stop using it and flag the information-barrier or compliance issue.
- Respect market-data licenses, privacy, sanctions, and source terms. Minimize personal data and do not expose credentials, private contacts, or restricted documents.
- Preserve an audit trail for material numbers: source or series ID, data vintage, retrieval time, transformation, formula, and unit. Keep raw observations separate from adjusted or modeled values.
- Treat the output as analyst decision support. Require qualified human review before publication, client use, trading, risk-limit changes, or regulatory reliance.

## Produce decision-ready visuals

Use a timeline when announcement and implementation differ; a flow diagram when three or more transmission links matter; a cross-asset matrix for directional effects; a yield-curve or spread chart for rate events; and an FX triangle when a cross rate is being misunderstood.

Inspect every rendered visual. Labels, signs, units, dates, timezones, and evidence status must remain readable at final size.

## Deliver the answer

Lead with a verdict, then provide only the necessary sections:

1. what happened and what did not happen;
2. why the event matters mechanically;
3. what markets actually did and over which window;
4. causal confidence and alternative explanations;
5. first- and second-order transmission map;
6. impact by asset, currency, sector, country, and time horizon;
7. scenarios, winners, losers, risks, and leading indicators;
8. unresolved facts and the next evidence needed.

Every material factual claim needs a nearby source. Label market data with timestamp and convention. Separate observation, theory, inference, scenario, and rumor. Do not present directional analysis as personalized investment advice.

## Completion gate

Before delivery verify:

- the primary official release was checked;
- actor, instrument, amount, status, and dates are correct;
- announcement is not confused with execution or settlement;
- finance-ministry operations are not mislabeled as central-bank policy;
- market windows and price conventions are explicit;
- data vintages, revisions, return conventions, and transformations are explicit;
- contemporaneous alternative causes were tested;
- DXY is not treated as every bilateral dollar rate;
- first-, second-, and real-economy effects are separated by horizon;
- diagrams show conditional arrows rather than false certainty;
- scenarios contain triggers and falsification conditions;
- any scenario probabilities are anchored, dated, and internally coherent;
- restricted or potentially material non-public information was excluded or escalated;
- facts, causal judgments, and forecasts remain visibly distinct.
