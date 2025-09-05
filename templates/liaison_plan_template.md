# Proposed Plan

<!-- 
This template is used by the CEO Liaison when presenting a plan.
Keep the headings/ordering stable so the runtime (and humans) can rely on it.
Anything in {{double_braces}} is guidance for the model (optional).
-->

## Summary
- **Intent:** {{In 1–2 sentences, restate the user’s request and the core outcome.}}
- **Deliverable:** {{e.g., "Draft docs/charter.md v1" or "Open PR to add ADR-003".}}
- **Why now:** {{One-line rationale or trigger event.}}

## Scope & Boundaries
- **In scope:** {{Bulleted list of what WILL be changed/created.}}
- **Out of scope:** {{Bulleted list of what will NOT be touched.}}
- **Assumptions:** {{Any assumptions being made.}}
- **Open questions (if any):** {{Concise questions for the owner.}}

## Files To Change (Planned)
| Path | Action | Brief rationale |
|---|---|---|
| {{e.g., docs/charter.md}} | {{create/update}} | {{why}} |

## Test / Review Plan
- **Checks:** {{What we’ll verify works (e.g., lint/tests/build, rendering).}}
- **Acceptance criteria:** {{Clear, objective checks for done.}}

## Risks & Mitigations
- **Risks:** {{Short bullets of credible risks.}}
- **Mitigations:** {{How we’ll reduce each risk.}}

## Rollback Plan
- **If something goes wrong:** {{How to revert/disable with minimal blast radius.}}

## Dependencies / Approvals
- **Approvals required:** {{e.g., Owner only / Architect first / Security review.}}
- **Upstream dependencies:** {{Docs, decisions, policies needed before executing.}}

## Estimated Cost / Latency (Model)
- **Model:** {{gpt-5-mini (default) | escalate if owner permits}}
- **Token estimate:** {{Very rough: small / medium / large}}
- **Expected runtime:** {{Seconds/minutes}}

---

## Execution Contract (filled after approval)
- **Branch name:** `agent/{{unix_ts}}-{{slug}}`
- **PR title:** {{Concise, imperative}}
- **Write scope:** `docs/**`, `agents/**` only for MVP
- **Status updates:** 
  - On success: post **PR URL**
  - On failure: post **error + next step** (retry or revise plan)

> **Owner action:** Click **Approve** in the UI to authorize execution.  
> Without approval, no tools or repo writes may run.