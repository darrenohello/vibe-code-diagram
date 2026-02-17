# CONTEXT-PURPOSE.md — Vibe-coding spectrum artefact

## What this is

This repo contains a small interactive artefact that explains a practical spectrum of “vibe-coding” (using Cursor / AI-assisted coding) across different intents and levels of consequence.

It is **not** a product feature, analytics dashboard, or a measurement tool.
It is a **communication + decision aid** for workshops and internal alignment.

The artefact exists to help people choose the right “kind of code artefact” for the job:

- Are we coding to **think**, **feel**, **prove feasibility**, **ship**, or **create leverage**?
- How integrated should it be?
- How “real” does it need to feel?
- What rigor/ownership does it require?

## Target audience

Primary:

- Product/design folks learning how Cursor changes the way we explore and communicate ideas.

Secondary:

- Engineers, PMs, and leaders who need a shared language for “what are we building here?” and “how serious is it?”

## The core message (the one thing this should communicate)

AI-assisted coding isn’t one activity.
It spans a spectrum from **low-consequence exploration** to **high-consequence production** — and each point on that spectrum demands different rigor, integration, and ownership.

## The model

The artefact presents:

1. A **5-level spectrum** (L1 → L5) as the main story.
2. A supporting **axes mental model** to explain what changes as you move right:
   - Purpose
   - Integration depth
   - Fidelity
   - Consequence

These axes are intended to be **conceptual**, not numeric scoring.

### Levels (canonical definitions)

- **L1 — Think (Cognitive artefacts):** code used as cognitive scaffolding; disposable by default.
- **L2 — Feel (Experiential prototypes):** code used to make UX/motion/state real beyond what static prototypes can show.
- **L3 — Prove (Feasibility probes):** code spikes to understand technical shape/constraints; “is this even real?”
- **L4 — Ship (Production extensions):** integrated code with production constraints (quality, security, perf, ownership).
- **L5 — Multiply (Organisational leverage):** tools/docs/automation that reduce friction and scale a team’s output.

## Design principles

- **Clarity > completeness.** If a feature makes comprehension harder, it’s not worth it.
- **Progressive disclosure.** Most detail should appear only after selection.
- **Avoid false precision.** Prefer qualitative labels over numeric scoring unless explicitly needed for discussion.
- **Minimize framework-on-framework.** The spectrum should read as the primary story; axes support it.
- **Workshop-first.** The UI should work as a guided conversation, not a self-serve app.

## Non-goals

- Not a rubric for performance evaluation.
- Not a maturity model for individuals/teams.
- Not a “Cursor adoption tracker”.
- Not a hard taxonomy that constrains creativity.

## How to use this in a workshop (suggested flow)

1. Start on **Spectrum** view.
2. Ask: “Which level are you currently operating in for your current work?”
3. Select a level and read out:
   - intent + one-liner
   - one example + one watch-out
4. Switch to **2D map** only to explain axes (integration × fidelity) when needed.
5. Close with the “risk curve” rule: further right = more rigor + ownership.

## How Cursor should help evolve this artefact

When asking Cursor to change this UI/UX, bias toward:

- simplifying the reading flow
- reducing cognitive load
- removing false precision
- improving hierarchy and progressive disclosure
- keeping the artefact workshop-friendly

If a proposed change adds complexity, require a strong justification:

- What confusion does it remove?
- What decision does it make easier?
- What essential message becomes clearer?

## Suggested future enhancements (only if they reduce load)

- “Start here” onboarding line that frames the job-to-be-done.
- 3 clickable “common scenarios” that jump to relevant levels.
- Optional toggle for showing/hiding axis values or advanced detail.
