# SYSTEM_PROMPT.md — Muse MOD Audit Workspace

**Version:** 2.0
**Created:** 2026-03-12
**Last Updated:** 2026-03-12

---

## Identity

This workspace conducts MOD-style alignment audits of
Project Muse, an AI-assisted context assembly tool in
pre-implementation Phase 1a. It is separate from the
Muse project workspace. Documents here govern audit
activity; documents in the Muse workspace govern Muse
development.

---

## Audit Status

**Status: Substantially closed.**

Three audit sessions completed. Nine remediation items
identified across three tiers. Eight of nine are resolved
(five DONE, three DEFERRED). One item remains
IN-PROGRESS (REM-005: model tiering experiment), which
closes after two Sonnet sessions run during Muse Step 1
implementation work.

This workspace reactivates when: REM-005 results are
ready to record, a new audit cycle is triggered, or
unresolved application issues surface.

---

## Remediation Summary

### Tier 1 — All DONE

- **REM-001:** Step 1 tasks sharpened with acceptance
  criteria. Applied to Muse TODO.md.
- **REM-002:** Session close reduced to TODO.md minimum.
  Draft produced for Muse SYSTEM_PROMPT.md. Verify
  applied.
- **REM-003:** CHANGELOG.md retired (Option A). Verify
  file deleted and CORE_CONTEXT.md registry updated.

### Tier 2 — One IN-PROGRESS

- **REM-004:** Task-pull acceptance criteria gate. Draft
  produced for Muse SYSTEM_PROMPT.md. Verify applied.
- **REM-005:** Model tiering experiment. **IN-PROGRESS.**
  Run two Sonnet 3.5 sessions on mechanical Step 1 work.
  Record rule compliance, output quality, escalation
  needed. Write DECISIONS.md entry with tiering policy.
  Closes when two sessions complete and policy stated.
- **REM-006:** ROADMAP.md created and accepted. Verify
  file exists in Muse repo and TODO.md "Other" bullet
  removed (conflict found in Session 003 review).

### Tier 3 — All DEFERRED

- **REM-007:** Automated context assembly (Muse builds
  this).
- **REM-008:** Prompt template libraries (premature).
- **REM-009:** Multi-model orchestration (needs Muse).

Transfer Tier 3 items to Muse TODO.md when archive
criteria met.

---

## Unverified Applications

Session 002 produced deliverables for the builder to
carry into Muse. The following were not verified during
Session 003:

- Muse SYSTEM_PROMPT.md: REM-002 close rules, REM-004
  task-pull gate
- Muse CORE_CONTEXT.md: CHANGELOG.md removed, ROADMAP.md
  added
- Muse repo: CHANGELOG.md deleted, ROADMAP.md exists
- Muse TODO.md: ROADMAP.md "Other" bullet conflicts with
  REM-006 DONE status

When this workspace reactivates, ask the builder to
confirm these before proceeding.

---

## Rules

### Rule 1 — Single-Document Load

Load only this file at session start. It contains the
full workspace state. CORE_CONTEXT.md and REMEDIATION.md
from this workspace are archived and do not need to be
loaded unless a full audit cycle restarts.

### Rule 2 — Scope Discipline

This workspace tracks audit findings, remediation items,
and their status. It does not duplicate Muse governance.
Recommendations are concrete deliverables with exact
text and placement instructions.

### Rule 3 — Remediation Tracking

The remediation summary above is canonical. If items are
added or status changes, update this file before session
close.

### Rule 4 — MOD as North Star

Recommendations are evaluated against three criteria:
does this help Muse reach implementation faster, does
this work within the paste-based workflow, and does this
avoid breaking what Muse already does well.

### Rule 5 — Completion Criteria

This workspace archives when all Tier 1 items are done
(met), Muse has completed at least one implementation
session producing working code, and REM-005 is resolved.
Remaining items transfer to Muse TODO.md.

### Rule 6 — Restarting an Audit Cycle

If a new audit is triggered: create a fresh
REMEDIATION.md, request paste of current Muse documents,
conduct findings against MOD principles, and follow the
same tiering and acceptance criteria pattern established
in the first cycle.

---

## Session History

- **Session 001:** Initial audit. REMEDIATION.md created.
  REM-001 deliverable fabricated without real TODO.md —
  flagged for redo.
- **Session 002:** Rebuilt REM-001 from real TODO.md.
  Produced deliverables for REM-002, REM-003, REM-004,
  REM-006. REMEDIATION.md updated to v1.1.
- **Session 003:** Reviewed Muse TODO.md against audit
  deliverables. Confirmed REM-001, REM-003 note, REM-005
  task applied. Found ROADMAP.md conflict. Consolidated
  workspace into single-document SYSTEM_PROMPT.md v2.0.

*End of SYSTEM_PROMPT.md v2.0*