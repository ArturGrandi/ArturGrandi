# Artur Grandi

Independent researcher building **Grand Time (GT 1.0)** — a **spec-first, research-only** economic protocol exploring **time as an economic primitive**.

**Scope:** research, architecture, verification, controlled reference implementation  
**Non-scope:** production system, token sales, investment offering, deployment promises

---

## Core Research Program and Canonical Reference

### Canonical paper (source of theoretical priority)

**“Time as a Non-Monetary Economic Primitive”**  
Zenodo (CERN) — DOI: https://doi.org/10.5281/zenodo.18190386

This paper introduces the core economic concept of **time as a non-monetary economic primitive** and forms the theoretical foundation of the Grand Time research program.

The DOI represents the canonical record of authorship, priority, and the original economic model.

---

### Related research papers (analytical extensions)

**“Capital Accumulates. Lifetime Does Not: Institutional Constraints on Macroeconomic Stock Representation”**  
Zenodo (CERN) — DOI: https://doi.org/10.5281/zenodo.18912295

This paper analyzes institutional constraints on macroeconomic stock representation and explains the structural asymmetry between capital accumulation and human lifetime.

---

**“Institutional Constraints on Macroeconomic Stock Representation: Why Capital Accumulates but Lifetime Does Not”**  
Zenodo (CERN) — DOI: https://doi.org/10.5281/zenodo.18912296

An extended analytical version refining the formal institutional conditions under which macroeconomic variables qualify for durable stock status.

---

### Research architecture note

All GitHub repositories in this profile serve as **supporting research artifacts**  
(architecture, formula specification, invariant verification, and controlled reference implementation).

They **do not introduce new economic claims** and are not canonical sources of the theory.
## Project hub

This profile acts as the **navigation hub** for all GT 1.0 research artifacts and review entry points.

## Current status

GT 1.0 is in **Frozen Research Specification + Controlled Reference Implementation** stage.

Full canonical scope and status definition:  
https://github.com/ArturGrandi/ArturGrandi/blob/main/STATUS.md

---

## GT 2.0 Research Track (Exploratory, Non-Canonical)

Formal analysis of time-based economic models enabled by decentralized trust.  
Submitted to Ethereum Foundation Ecosystem Support Program (ESP) on February 6, 2026.  
[Grant Proposal PDF](https://github.com/ArturGrandi/ArturGrandi/raw/main/Grand%20Time_%20Time-Based%20Economic%20Models%20under%20Decentralized%20Trust.pdf)  
Repository: [gt2-research-track](https://github.com/ArturGrandi/gt2-research-track)  
Controlled Reference Demo Blueprint (verification-only):  
docs/CONTROLLED_DEMO_BLUEPRINT.md  
Deterministic state machine scaffold for invariant stress-testing (non-executable, no scope expansion).
Research DOI: [10.5281/zenodo.18275133](https://doi.org/10.5281/zenodo.18275133)

Focus: Architectural constraints, invariants, failure modes for non-monetary time normalization under credibly neutral infrastructure.  
All outputs research-only (no code, no production, no tokenomics).

## Seeking Co-Authors / Contributors

Looking for 2–3 senior contributors (Solidity, formal verification, economic primitives experience) to help with:
- Verification & stress-testing of Time Capital activation gates
- Mint coverage enforcement & multi-asset liquidity scenarios
- Oracle handling & emergency segregation invariants

Research-only, unpaid. 
See detailed call in: [Issue #1 → gt1-implementation-reference](https://github.com/ArturGrandi/gt1-implementation-reference/issues/1)
If interested: comment on the issue or DM here / on X @Artur07020283.

## Start Here (Canonical Index)

### 1. grand-time-architecture
**Conceptual architecture & prior art (research-only)**  
Original conceptual framework defining meaning, invariants, boundaries, and non-goals.

- No executable code
- No production intent
- Establishes authorship and chronological origin

Repository:  
https://github.com/ArturGrandi/grand-time-architecture

---

### 2. gt1-formular-standard
**Spec-first mathematical and economic formulas (reference)**  
Formal representation of GT 1.0 formulas and invariants.

- Non-production
- No implementation assumptions
- No genesis constants embedded

Repository:  
https://github.com/ArturGrandi/gt1-formular-standard

---

### 3. gt1-implementation-reference
**GT 1.0 controlled reference implementation**  
Research, simulation, and verification-only implementation space.

- Spec-driven (binding specs in `/spec`)
- No production deployment
- No economic redesign discussions
- All genesis parameters defined **exclusively** in `spec/genesis.md`

Repository:  
https://github.com/ArturGrandi/gt1-implementation-reference

---

### 4. grand-time-calc (ARCHIVED)
**Deprecated prototype / calculator**  
Early experimental work. Retained for historical reference only.

- Archived
- Not aligned with GT 1.0 specs
- Must not be used for validation or implementation

Repository:  
https://github.com/ArturGrandi/grand-time-calc

---

## Canonical Rules

- **GT 1.0 is spec-first.**
- **Genesis constants live only in:**  
  `gt1-implementation-reference/spec/genesis.md`
- Other documents may reference genesis parameters but MUST NOT duplicate values.
- Verification is access control, not economic amplification.
- No protocol-level gas subsidy for user transactions.
- No investment claims, yield, or profit guarantees.

---

## Status

GT 1.0 is currently in **controlled research and implementation phase**.

Future versions, extensions, or revisions may be considered **only after**
full GT 1.0 implementation and verification are complete.

---

## Contact / Collaboration

Collaboration is limited to:
- research,
- formal verification,
- controlled reference implementation,
- security and invariants analysis.

Economic redesign proposals are out of scope.

Use GitHub Issues in the relevant repository if applicable.
