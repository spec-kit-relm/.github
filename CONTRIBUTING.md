# Contributing to Relm repositories

1. Pick your lane: `lane:feature` (with `Feature: RELM-<n>`), `lane:bugfix`, `lane:chore` or
   `lane:governance` — see [Work lanes](https://github.com/spec-kit-relm/sdd-handbook/blob/main/docs/03-work-lanes.md).
2. Features follow the [AI SDLC](https://github.com/spec-kit-relm/sdd-handbook/blob/main/docs/02-ai-sdlc.md):
   spec → contracts → plan → tasks → analyze (0 CRITICAL) → implement (one phase per run) → converge.
3. Read the repository's `AGENTS.md` (how) and `.specify/memory/constitution.md` (what must hold).
4. Use the PR template; `sdd / sdd-gates` must be green and a CODEOWNER must approve.
5. Never edit `contracts/vendor/**` or Parts A/B of a constitution by hand.
