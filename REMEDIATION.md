# REMEDIATION.md — muse-mod-audit

**Version:** 1.0
**Last Updated:** 2026-03-12

---

## Status Key

- **OPEN** — Not started
- **IN-PROGRESS** — Work begun
- **DONE** — Acceptance criteria met
- **DEFERRED** — Moved to Muse TODO.md
- **DROPPED** — Rejected with rationale

---

## Tier 1 — Before Step 1 Implementation Begins

### REM-001: Sharpen Step 1 Tasks with Acceptance Criteria

**Status:** OPEN
**Priority:** Highest — single greatest leverage on
implementation velocity.

Rewrite each Step 1 task and research item in Muse's
TODO.md with explicit acceptance criteria following the
pattern: what artifact exists, what behavior confirms it
works, what the human checks in under a minute.

**Acceptance Criteria:** Every Step 1 item in TODO.md has
a "Done when" statement. Each statement names a concrete
artifact or observable outcome, not a subjective judgment.

---

### REM-002: Reduce Session Close Ceremony

**Status:** OPEN
**Priority:** High — recovers 10–15 min per
implementation session.

Change Muse's minimum session close from three-document
update (TODO + SESSIONLOG + CHANGELOG) to one-document
update (TODO.md only). SESSIONLOG and CHANGELOG become
periodic batch updates every third session or during
scheduled governance sessions.

**Acceptance Criteria:** Muse SYSTEM_PROMPT.md session
close rules updated to require only TODO.md. Batch
cadence for SESSIONLOG/CHANGELOG documented. First
implementation session uses the lighter close.

---

### REM-003: Evaluate CHANGELOG Consolidation

**Status:** OPEN
**Priority:** High — reduces document count, recovers
token budget, eliminates maintenance overlap.

Assess whether CHANGELOG.md should be retired as a
standalone document and its content merged into
SESSIONLOG.md entries. CHANGELOG serves versioned
releases; Muse has no releases yet.

**Acceptance Criteria:** Decision recorded (keep, merge,
or retire) with rationale. If merged or retired, Muse
documents updated accordingly and token budget recovered.

---

## Tier 2 — Alongside Early Implementation

### REM-004: Acceptance Criteria at Task-Pull Time

**Status:** OPEN
**Priority:** Medium — sustains the practice REM-001
establishes.

Add a standing practice: when pulling a task into a
session, write 2–3 sentence acceptance criteria before
any work begins. Encode this in Muse's SYSTEM_PROMPT.md
as a session-open step for implementation sessions.

**Acceptance Criteria:** Rule added to Muse
SYSTEM_PROMPT.md. Practice observed in at least two
implementation sessions.

---

### REM-005: Experiment with Model Tiering

**Status:** OPEN
**Priority:** Medium — reduces cost, validates Muse's
core product thesis.

Try Sonnet-class models for routine documentation,
TODO maintenance, and SESSIONLOG batch updates. Reserve
Opus for architecture and complex implementation. Track
results as user research for the model router.

**Acceptance Criteria:** At least two sessions run on a
lighter model. Outcomes noted (what worked, what didn't).
Findings recorded in Muse DECISIONS.md or research notes.

---

### REM-006: Create ROADMAP.md

**Status:** OPEN
**Priority:** Medium — low cost, immediate orientation
benefit.

Create a minimal ROADMAP.md in the Muse workspace: phase
names, what each delivers, current position. Half a page
maximum. Consolidates roadmap information currently
scattered across TODO.md and ARCHITECTURE.md.

**Acceptance Criteria:** ROADMAP.md exists in Muse
workspace, under 750 tokens, referenced in Muse
CORE_CONTEXT.md document table.

---

## Tier 3 — Defer Until Muse Can Help

### REM-007: Automated Context Assembly

**Status:** DEFERRED
**Rationale:** This is literally what Muse builds.
Manual simulation would cost more than it returns.
Transfers to Muse TODO.md when Tier 1 is complete.

---

### REM-008: Prompt Template Libraries

**Status:** DEFERRED
**Rationale:** Templates emerge from implementation
experience. Defining them before writing code is
premature optimization.

---

### REM-009: Multi-Model Dev Workflow Orchestration

**Status:** DEFERRED
**Rationale:** Requires Muse's own capabilities to
execute meaningfully. REM-005 covers the manual
approximation available now.

---

## Progress Summary

| Tier   | Total | Open | In-Progress | Done | Deferred |
|--------|-------|------|-------------|------|----------|
| Tier 1 |     3 |    3 |           0 |    0 |        0 |
| Tier 2 |     3 |    3 |           0 |    0 |        0 |
| Tier 3 |     3 |    0 |           0 |    0 |        3 |
| **All** |   **9** | **6** |       **0** | **0** |    **3** |

---

## Next Action

REM-001. Produce rewritten Step 1 tasks with acceptance
criteria, ready for the human to carry into Muse's
TODO.md.

*End of REMEDIATION.md*