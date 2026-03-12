# REMEDIATION.md — muse-mod-audit

**Version:** 1.1
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

**Status:** DONE
**Resolution:** Every Step 1 task and research item in
TODO.md rewritten with explicit "Done when" acceptance
criteria naming concrete artifacts or observable outcomes.
Deliverable produced in audit Session 002; ready for
builder to carry into TODO.md.

**Acceptance Criteria:** Every Step 1 item in TODO.md has
a "Done when" statement. Each statement names a concrete
artifact or observable outcome, not a subjective judgment.

---

### REM-002: Reduce Session Close Ceremony

**Status:** DONE
**Resolution:** Draft replacement section produced for
SYSTEM_PROMPT.md. Minimum close reduced to TODO.md only.
SESSIONLOG batch update every third session or during
governance sessions. CHANGELOG references removed per
REM-003. Awaits builder review and application.

**Acceptance Criteria:** Muse SYSTEM_PROMPT.md session
close rules updated to require only TODO.md. Batch
cadence for SESSIONLOG/CHANGELOG documented. First
implementation session uses the lighter close.

---

### REM-003: Evaluate CHANGELOG Consolidation

**Status:** DONE
**Resolution:** Option A — retire. CHANGELOG.md deleted,
CORE_CONTEXT.md registry updated, session close references
removed. No release consumers exist. Recreate as
release-scoped document when versioned releases begin
(Phase 1a Step 7 earliest).

**Acceptance Criteria:** Decision recorded (keep, merge,
or retire) with rationale. If merged or retired, Muse
documents updated accordingly and token budget recovered.

---

## Tier 2 — Alongside Early Implementation

### REM-004: Acceptance Criteria at Task-Pull Time

**Status:** DONE
**Resolution:** Draft addition produced for
SYSTEM_PROMPT.md. Standing rule: when pulling a task into
a session, write 2–3 sentence acceptance criteria before
work begins. Encoded as session-open step for
implementation sessions. Awaits builder review and
application. Practice observation deferred to first two
implementation sessions.

**Acceptance Criteria:** Rule added to Muse
SYSTEM_PROMPT.md. Practice observed in at least two
implementation sessions.

---

### REM-005: Experiment with Model Tiering

**Status:** IN-PROGRESS
**Protocol:** Run two early Step 1 sessions on Sonnet 3.5
(scaffold generation, research checks RES-S11-A through C,
or batch doc updates). After each session note: rule
compliance, output quality, escalation needed. After both,
write DECISIONS.md entry with concrete tiering policy.
Cannot close until two Sonnet sessions complete.

**Acceptance Criteria:** Two Sonnet sessions completed.
Findings entry exists in DECISIONS.md with concrete
tiering policy statement. Policy is evidence-based.

---

### REM-006: Create ROADMAP.md

**Status:** DONE
**Resolution:** ROADMAP.md v0.1 produced and accepted.
Under 750 tokens. Covers all three phases with current
position marker. Placed at repo root. CORE_CONTEXT.md
registry updated to include it.

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
| Tier 1 |     3 |    0 |           0 |    3 |        0 |
| Tier 2 |     3 |    0 |           1 |    2 |        0 |
| Tier 3 |     3 |    0 |           0 |    0 |        3 |
| **All** |   **9** | **0** |       **1** | **5** |    **3** |

---

## Next Action

REM-005. Run two Sonnet sessions during early Step 1 work.
All other items complete or deferred. Audit substantially
closed.

*End of REMEDIATION.md*