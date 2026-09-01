# Evidence pack

Create only the records needed to reproduce material conclusions. Rapid answers may keep these fields inline.

## Source ledger

| ID | Publisher / URL | Published | Event or measurement time | Accessed | Class | Claim supported | Limitation |
|---|---|---|---|---|---|---|---|

## Market-data register

| ID | Provider / series / ticker | Observation time and timezone | Field and convention | Currency | Frequency | Vintage | Adjustment | License / access note |
|---|---|---|---|---|---|---|---|---|

Record price versus yield or total return, clean versus dirty price, spot versus futures, local versus base currency, and any roll, coupon, dividend, holiday, or corporate-action treatment.

## Calculation log

| Output | Formula or transformation | Input IDs | Unit | Window | Assumptions | Cross-check |
|---|---|---|---|---|---|---|

Keep raw observations immutable. Label manual corrections and modeled inputs; never overwrite a conflicting source value silently.

## Attribution and scenario register

| Claim / scenario | Evidence for | Evidence against | Trigger | Probability or confidence | Horizon | Falsification |
|---|---|---|---|---|---|---|

Use probability only for mutually exclusive scenarios with a stated as-of date and total of 100%. Otherwise use qualitative confidence.
