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
## Suggested structure
Start with only these two Markdown files. Split material out when it becomes
hard to scan:

```text
project/
├── BUILD-RULES.md
├── PROJECT.md
├── docs/
│   ├── decisions/
│   ├── plans/
│   └── evidence/
├── src/
├── tests/
└── README.md
```
