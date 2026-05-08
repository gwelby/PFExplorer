# Team Strike Status — Phase 0 First

**Date**: 2026-03-31  
**Mission**: Stabilize Journey and Comparison, then ship Phases 1-2 as the core Explorer deliverables  
**Team**: Codex, Qwen, Cascade, Lumi

---

## Current State

- Phase 1 (`journey.html`) exists and is valuable.
- Phase 2 (`comparison.html`) exists and is valuable.
- Main Explorer truth-sync is already in place through `data.js`.
- Narrative pages must now read PF truth from that same layer instead of hardcoding stronger claims.

This document supersedes the earlier "build Phases 2-4 immediately" framing.  
**Current order is: Phase 0 stabilization -> ship Phases 1-2 -> optionally revisit Phases 3-4.**

---

## Ownership

### Codex

- `truth-utils.js`
- Journey / Comparison runtime stability
- final verification gate

Done condition:

- zero console errors on `journey.html`
- zero console errors on `comparison.html`
- PF-facing copy on both pages is sourced from `data.js`

### Qwen

- Journey / Comparison narrative copy under audited constraints

Done condition:

- no conditional PF claim reads as derived
- no empirical signal reads as theorem
- emotional arc remains intact

### Cascade

- docs and public framing

Files:

- `README.md`
- `GRAND_PLAN.md`
- `STRIKE_COMPLETE.md`

Done condition:

- authoritative PF truth is stated as `CLAIMS.md` via `data.js`
- Journey and Comparison are described as narrative fronts
- duration language is unified to **8-minute**
- Phases 3-4 are explicitly deferred

### Lumi

- final honesty pass only

Done condition:

- line-level narrative review after implementation
- no claim inflation

---

## Phase 0 Checklist

### Runtime

- remove `core.js` dependency from narrative pages
- standardize narrative script order:
  - `data.js`
  - `truth-utils.js`
  - page script
- fix Journey renderer scope bugs
- ensure `PARTIAL DERIVATION` renders correctly

### Truth-sync

- Journey Act I uses `CONDITIONAL` Bohr wording
- Journey Act II uses `PARTIAL DERIVATION` for weights and `CONDITIONAL` for `N=3`
- Journey Act III keeps `CONDITIONAL 0.88` for the God Equation
- Journey Act IV runtime-derives audited counts
- Journey falsification wall uses actual `falsifier` text from `data.js`
- Comparison PF column reflects audited truth instead of hardcoded triumphal copy

### Docs

- `README.md` states the authoritative truth layer explicitly
- `GRAND_PLAN.md` reflects the current audited framing
- `STRIKE_COMPLETE.md` reports Phases 1-2 as real, but only ship-ready after Phase 0

---

## Verification

Run:

```powershell
node --check sandbox/explorer/truth-utils.js
node --check sandbox/explorer/journey.js
node --check sandbox/explorer/comparison.js
```

Manual browser checks:

1. Load `journey.html`
2. Confirm zero console errors
3. Walk Opening -> Act IV -> Epilogue
4. Confirm counts and result cards match `data.js`
5. Load `comparison.html`
6. Confirm zero console errors
7. Confirm PF column matches audited repo truth

---

## Deferred Work

Phases 3-4 are **not active work** in the current strike.

- Phase 3: Derivation Chain Visualizer
- Phase 4: Presentation Mode

They stay deferred until Phase 0 is audit-clean and the current narrative fronts are stable enough to ship.

---

## Ship Rule

Once Phase 0 passes:

- Journey becomes the 8-minute narrative front
- Comparison becomes the context front
- Reference Explorer remains the audit/reference front

That is the core deliverable set.
