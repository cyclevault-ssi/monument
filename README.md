# Monument

A starting kit for building something with AI agents without losing the plot.

Long projects with agents drift: decisions get forgotten, scope creeps, and "done" means whatever the last message said. Monument is two plain Markdown files you drop into a project so the intent, the decisions and the proof live somewhere every person and every agent reads first.

## Start in five minutes

1. Copy [`PROJECT.md`](PROJECT.md) and [`BUILD-RULES.md`](BUILD-RULES.md) into your project.
2. Fill in `PROJECT.md`: what you're building, for whom, what "done" looks like, and the next step you want.
3. Point your agent at [`AGENTS.md`](AGENTS.md) and give it one small, bounded task.
4. After each step, update `PROJECT.md`: what was decided, what was proven, what's next.

That's it. Add `docs/decisions`, `docs/plans` or `docs/evidence` only when the project gets too big to scan.

## The loop

**Read → plan one step → build it → prove it → you review → next step.**

- **Read** the project file before touching anything.
- **Plan** one step small enough to check.
- **Build** only that step.
- **Prove** it with evidence that matches the claim (a test, a screenshot, a measurement), and say what it does *not* prove.
- **Review**: a person approves before the next step starts.

## What it helps with

- Decisions survive across long projects and new sessions.
- Facts, decisions, guesses and proof stay separate.
- Work stops when it drifts outside what was asked.
- Someone else (or another agent) can pick the project up cold.

A detailed plan isn't a correct plan. Monument keeps review and evidence as their own steps for that reason.

## Going further

Once a project has repeating work (reviews, tests, releases), the same ideas scale up into a software factory: [Gas City](https://github.com/gastownhall/gascity) packs with formulas and human approval gates. [Building Three Keypress Sweeps for TUI Testing](https://cyclevault.ai/keypress-sweeps/) shows three factories measured on one job.

## Suggestions

Corrections and examples are welcome as issues or pull requests.

Made by Jason Fullner, [CycleVault](https://cyclevault.ai).

## License

The Monument Method documents and templates are licensed under the
[Creative Commons Attribution 4.0 International License](LICENSE).

Suggested attribution:

> The Monument Method by Jason Fullner and CycleVault.ai, licensed under
> CC BY 4.0. Shared through SolidStateIntelligence.ai.

When publishing an adaptation, identify that changes were made.
