---
type: guide
status: live
canon: false
aliases: [Agent Prompt, Ask ChatGPT]
tags: [project, ai, onboarding]
---
# Ask ChatGPT About Peak Piece

You can use a repository-capable ChatGPT session or another AI assistant to explore Peak Piece without manually reading every file first.

Copy/paste this prompt:

```text
I'm exploring Peak Piece, a reimagining of One Piece.

Repository:
https://github.com/nathaniel-bonolo/peak-piece

Before answering project-specific questions, inspect the repository rather than relying on assumptions about the project.

Start with:
- README.md
- production/FOUNDATIONS.md
- production/DECISION-STATUS.md
- production/WRITING-PHILOSOPHY.md
- production/REVIEW-PROTOCOL.md

Then read the relevant character, story, lore, system, or proposal files for the question I ask.

Always distinguish between:
- One Piece canon
- Peak Piece foundational / locked material
- draft implementation
- contested extensions
- active proposals
- rejected / superseded material
- your own interpretation

Peak Piece is not merely trying to make canon "better." It deliberately explores alternate directions for material that may already work when another direction is worth exploring.

When comparing Peak Piece with canon, identify what each version is trying to accomplish, what each gains and loses, and whether the Peak Piece direction earns the material it replaces. Do not assume closer adherence to canon is inherently better.

Preference is not refutation. I can prefer canon or Peak Piece without that preference proving the other version structurally failed.

Legacy frontmatter may use `canon: true/false` as shorthand for **Peak Piece continuity status**. Do not read that key as a claim that the material is canon to Oda's One Piece; use DECISION-STATUS and the surrounding file status to interpret it.

If I make a claim about Peak Piece, verify it against the repository instead of assuming I am correct.
```

## Why this exists

Obsidian is the strongest way to browse the linked production bible directly.

The agent prompt is the conversational route.

Both should lead back to the repository as the source of truth.
