# [Project name]
> [One sentence describing what this should become and who it serves.]
## Outcome
- **User:** [Who is this for?]
- **Problem:** [What problem does it solve?]
- **Success:** [What observable result means it works?]
- **Non-goals:** [What are you deliberately not building?]
## Current truth
- **Exists now:** [Verified behavior or artifacts.]
- **Planned, not built:** [Intent that must not be claimed as complete.]
- **Unknown:** [Questions that require research or a human decision.]
## Next bounded slice
- **Target:** [One concrete result.]
- **Dependencies:** [What must already be true?]
- **Allowed changes:** [Exact files or directories.]
- **Do not change:** [Protected behavior and boundaries.]
- **Acceptance evidence:** [Commands, artifacts, or human review.]
- **Stop if:** [Drift, conflict, missing authority, or scope expansion.]
## Decisions and handoff
- **Settled:** [Decision, reason, date.]
- **Open:** [One consequential question.]
- **Last evidence:** [What ran, result, and what it did not prove.]
- **Next human gate:** [The exact review or approval required.]
## Document authority
- **`PROJECT.md` defines it:** intent, current truth, boundaries, and human gates.
- **`docs/DESIGN.md` shapes it:** experience, capabilities, interfaces, data,
  failure behavior, recovery, and explicit non-designs.
- **`docs/PLAN.md` sequences it:** dependencies, construction order, bounded
  work, acceptance gates, rollback, and stop conditions.
- **`docs/EVIDENCE.md` proves it:** named claims, results, limits, dates,
  versions or hashes, and what remains unproven.

`DESIGN.md` may elaborate but never overrule `PROJECT.md`. `PLAN.md` may not
silently invent design. `EVIDENCE.md` may not redefine the requirement it
tests.

Add `docs/decisions/`, `docs/research/`, `docs/runbooks/`, `SECURITY.md`, or
`CHANGELOG.md` only when the project actually needs them.

## Suggested structure
Keep the core authorities brief and split supporting material only when it
becomes difficult to scan:

```text
project/
├── PROJECT.md
├── AGENTS.md
├── BUILD-RULES.md
├── docs/
│   ├── DESIGN.md
│   ├── PLAN.md
│   ├── EVIDENCE.md
│   ├── decisions/
│   ├── research/
│   └── runbooks/
├── src/
├── tests/
└── README.md
```
