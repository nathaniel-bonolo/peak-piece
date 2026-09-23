---
type: guide
status: live
canon: false
aliases: [Agent Prompt, Ask ChatGPT]
tags: [project, ai, onboarding]
---
# Ask ChatGPT About Peak Piece

For most people, a repository-capable ChatGPT session is the fastest way to ingest and explore the Peak Piece bible.

The repository is still the source of truth. ChatGPT is the primary conversational interface over that source.

Copy/paste this prompt:

```text
I'm exploring Peak Piece, a reimagining of One Piece.

Repository:
https://github.com/nathaniel-bonolo/peak-piece

Treat the current repository as the source of truth.

Before answering project-specific questions, inspect the repository instead of relying on assumptions about Peak Piece, old conversations, handoffs, or general One Piece knowledge.

First establish the current project state from:
- project.json
- README.md
- production/FOUNDATIONS.md
- production/DECISION-STATUS.md
- production/WRITING-PHILOSOPHY.md
- production/REVIEW-PROTOCOL.md
- the newest relevant section of CHANGELOG.md when version history matters

Then follow the relevant links into character, story, lore, faction, system, canon-audit, or proposal files for the question I ask.

Do not stop at the first matching file when the answer depends on connected material. Synthesize across the relevant files.

Always distinguish between:
- One Piece canon
- Peak Piece foundational / locked material
- current draft implementation
- contested extensions
- active proposals
- rejected / superseded material
- your own inference

Peak Piece is not merely trying to make canon "better." It deliberately explores alternate directions for material that may already work when another direction is worth exploring.

When evaluating a major replacement:
- identify what canon is doing
- inspect the relevant canon audit when one exists
- identify what Peak Piece is trying to do instead
- identify what each version gains and loses
- ask whether the Peak direction earns the cost of replacement

If the relevant radical change has no canon audit yet, say so instead of pretending the repository has already done that work.

Do not assume closer adherence to canon is inherently better.
Do not assume greater complexity or greater difference is inherently better.
Preference is not refutation.

Legacy frontmatter may use `canon: true/false` as shorthand for Peak Piece continuity status. Do not read that key as a claim that the material is canon to Oda's One Piece. Use production/DECISION-STATUS.md, proposal location, file status, and surrounding context to interpret it.

If multiple files conflict, do not silently merge them. Identify the contradiction and prefer explicit current status / newer authoritative material when the repository makes that hierarchy clear.

When explaining a conclusion, distinguish:
- what the repository explicitly states
- what you inferred by connecting multiple files

Use CHANGELOG.md to understand how an idea evolved, not as a substitute for the current authoritative files.

If I make a factual claim about Peak Piece, verify it against the repository instead of assuming I am correct.
```

## Creator route

If the goal is to decide whether Peak Piece is worth exploring before committing significant time, use [[prompts/CREATORPROMPT|Creator Evaluation Prompt]].

If the goal is to decide whether you personally fit the project as a writer, beta reader, artist, researcher, editor, reviewer, designer, or tooling contributor, use [[prompts/CONTRIBUTORPROMPT|Contributor Onboarding Prompt]].

## Why this exists

Manually opening files is useful when you already know where you are going.

For broad understanding, the AI route is usually stronger because it can traverse the linked bible, compare status, and synthesize across multiple files without requiring the reader to learn the repository layout first.

The repository remains authoritative underneath that interface.
