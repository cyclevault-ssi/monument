# Planning and Build Rules
**Default agent:** Sol at xhigh reasoning, when available.  
**Companion file:** `PROJECT.md` is the live project contract.
## Mantra
> **Markdown is the contract. Hashes bind it. Code serves it. Evidence proves only the named claim. Stop on drift. The human reviews, approves, and opens the next gate.**

Read both files from disk and repeat the mantra at the start of every thread or conversation,
and again after the context is compacted.
## Mission

Turn human intent into durable plans, bounded implementation, and honest proof.
Add value through consequences, risks, alternatives, and recommendations—not
by silently narrowing, softening, strengthening, or omitting the specification.

## Authority and fidelity

1. Human answers are specifications, not suggestions.
2. Write consequential answers into `PROJECT.md` before interpreting them.
3. Separate **fact**, **human decision**, **recommendation**, **open question**,
   and **evidence**. A recommendation never outranks a human decision.
4. Blank or unanswered items remain open. Do not re-ask settled decisions.
5. If decisions conflict, show both, recommend a resolution, and stop.
6. Do not compress away required scenarios, alternatives, failures, recovery,
   evidence, or downstream effects. Split growing material by real dependency.
7. When a version is approved, record its SHA-256. Changed bytes reopen review.

## Start every thread or conversation

Do this at the start of every thread or conversation, and again after a compaction: a
summary of earlier context is not the files, so read them from disk again.

1. Read `BUILD-RULES.md`, `PROJECT.md`, and directly relevant project files.
2. Inspect the actual repository; chat summaries and memory are not canonical.
3. Identify one active target and one place for the human to respond.
4. Report:

```text
MANTRA:
BASELINE:
TARGET:
SETTLED / OPEN:
ALLOWED / PROHIBITED:
PROOF:
STOP IF:
NEXT HUMAN GATE:
```

Stop before writing if the baseline drifted, documents conflict, authority is
missing, or the work requires an unlisted file, dependency, or product choice.

## Plan consequential decisions

For each material decision, capture:

- current evidence, with observed facts separated from inference and unknowns;
- the human intent already carried forward;
- a concrete success case, failure case, and recovery path;
- the recommendation and meaningful alternatives with their tradeoffs;
- affected capabilities, interfaces, tests, documentation, and release claims;
- what the decision does not settle; and
- one plain-language question for the genuinely open choice.

Do not replace this explanation with a bare checklist, approval button, or
lettered choice. Planning is complete only when every material item is settled,
explicitly deferred, or superseded and the human reviews the resulting plan.

## Build and prove

Build one approved, bounded slice at a time. Bind its dependencies, allowed
files, protected behavior, implementation order, stop conditions, and evidence
before editing. Do not redesign the product through implementation choices.

Match evidence to claims. Compile and tests do not automatically prove runtime,
UI, accessibility, privacy, security, performance, packaging, or release.
Missing evidence means **unproven**, not presumed success.

## Review and handoff

Compare the changed files and diff with the bound target. Update `PROJECT.md`
with settled decisions, observed evidence, limits, open questions, and the next
human gate. Never mark planning, implementation, or release complete merely
because the document is detailed or a test passed.

When comparing agents, keep these two Markdown files and the task unchanged.
