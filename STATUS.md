# GT 1.0 — Project Status Summary (Research Phase)

This document defines the canonical scope, status, and research boundaries of GT 1.0.
All GitHub repositories are supporting artifacts and do not introduce new economic claims beyond the canonical research record.

---

## 1. Canonical research record and authorship

The original research document establishing the concept, economic meaning, and priority of GT 1.0 is:

**“Time as a Non-Monetary Economic Primitive”**  
Zenodo (CERN) — DOI: https://doi.org/10.5281/zenodo.18190386  

This DOI is the immutable, canonical record that defines:

- authorship,
- chronological priority,
- economic meaning of Grand Time,
- and the conceptual definition of time as an economic primitive.

All GitHub repositories are subordinate, supporting artifacts and must not introduce new economic claims beyond what is fixed in the DOI record.

---

## 2. Project framing

GT 1.0 is explicitly defined as:

- **research-only**
- **spec-first**
- **non-production**
- **no investment offering**
- **no token sales**
- **no deployment promises**

GT 1.0 exists as a controlled reference protocol for:

- architectural verification,
- invariant formalization,
- system behavior analysis,
- independent technical and academic review.

It is not a financial product and not a commercial system.

---

## 3. Repository roles

### A. `grand-time-architecture`

Purpose:
- conceptual and architectural fixation of Grand Time,
- prior art,
- economic meaning and system boundaries.

Status:
- research-only,
- Architecture 1.0 frozen,
- contains no executable code,
- serves as the historical and conceptual baseline.

---

### B. `gt1-formular-standard`

Purpose:
- formal mathematical and economic specification of GT 1.0,
- binding formulas and invariants,
- spec-first reference layer.

Contains:
- GT1-FS-000x documents (minting, pricing, gates),
- CR / SR rules,
- 333-day stability standard,
- mint coverage gate,
- Time Capital model,
- bonding premium cap (44%),
- zero protocol fees (gas only),
- multi-asset liquidity (USDT / USDC / DAI),
- emergency asset segregation rules.

Status:
- non-production reference,
- formulas and constraints are considered binding for GT 1.0.

---

### C. `gt1-implementation-reference`

Purpose:
- controlled reference implementation of GT 1.0,
- technical entry point for senior developers, auditors, and researchers.

Status:
- documentation v1.0 frozen,
- research-only,
- spec-first,
- open for external technical review.

Key documents:
- `README.md`
- Canonical Research Reference (DOI)
- Documentation Freeze (GT 1.0)
- `HOW_TO_READ.md`
- `docs/REQUEST_FOR_REVIEW.md`

---

## 4. Binding specification set

The `/spec` directory in `gt1-implementation-reference` contains the complete canonical specification:

### `genesis.md`
The only authoritative source for all numerical parameters, including:
- T0 and virtual prehistory (3333 days),
- M = 10,000,000 GUCT per day,
- initial supply allocation,
- N0 population baseline,
- P0 initial price,
- gas autonomy parameters.

No other file may define or duplicate these values.

---

### `architecture.md`
Defines:
- module boundaries,
- on-chain / off-chain separation,
- GasReserve,
- ETH rail,
- mint gates and pause paths.

---

### `operations.md`
Defines:
- gas autonomy (no social transaction subsidy),
- ETH Time Capital purchase rail,
- enable/disable gates,
- refund correctness,
- P_next_min preservation.

---

### `security.md`
Defines:
- binding security model,
- oracle failure handling,
- asset suspension containment,
- no liquidation,
- no reflexivity,
- mandatory stress cases.

---

### `verification_checklist.md`
Defines:
- acceptance criteria (PASS / FAIL),
- invariants are stronger than tests.

---

### `verification_matrix.md`
Defines:
- mapping between requirements, modules, and tests.

---

## 5. Diagrams and visual layer

The directory `docs/diagrams/` contains SVG diagrams:

- `architecture-overview.svg`
- `funds-flow.svg`
- `oracle-failure-path.svg`
- `gas-depleted-path.svg`
- `stablecoin-suspended-path.svg`

Principles:
- one diagram = one concept or one risk,
- diagrams visualize the specification but do not define rules.

---

## 6. AI, population, and inheritance (GT 1.0 rules)

### AI (GPT)
- read-only and guided actions only,
- no private keys,
- no transaction signing,
- RAG limited to `/spec/*.md` and linked canonical documents.

### Population
- baseline `N0` fixed at deployment,
- no automatic births or deaths,
- changes only via DAO multisig,
- no more than once per year.

### Inheritance (GT 1.0)
- opt-in only,
- inactivityPeriod = 222 days,
- no automatic confiscation of GUCT.

---

## 7. Current stage

GT 1.0 is in:

**Frozen research specification + controlled reference implementation, open for senior technical review.**

It is ready for:
- senior developer review,
- formal architecture critique,
- academic and media analysis,
- institutional study (non-investment).

It is not ready and not intended for:
- product launch,
- token sales,
- investment offerings,
- commercial deployment.
