---
type: guide
status: live
canon: false
aliases: [Writers Room Workflow, Collaboration Workflow]
tags: [project, workflow, collaboration]
---
# Writers' Room Workflow

The project does **not** require every writer to become a Git user.

## Easy writers' room

Use Discord and/or shared Docs for brainstorming, dialogue, scene drafts, research dumps, and fast collaborative writing.

Material written there is not automatically canon. Accepted material is integrated into the repository's authoritative files.

## Decision states

Substantial ideas can move through:

> **Draft → Contested → Converging → Locked**

### Draft

The direction is being built. Criticism is welcome, but do not pretend an unfinished pitch has already demonstrated finished execution.

### Contested

There is meaningful disagreement about direction, cost, or fit.

Contested does not mean "dead." The point is to develop the strongest version, not repeat the same one-paragraph argument forever.

### Converging

The room broadly agrees on direction. Remaining work is mostly implementation, continuity, or wording.

### Locked

The direction is authoritative until new evidence or a genuinely better replacement justifies reopening it.

Not every tiny scene needs a formal state or vote.

## Foundations are a separate layer

[[production/FOUNDATIONS|Foundations]] describe the adaptation itself.

They are not ordinary proposals and should be disclosed before somebody invests heavily in the project.

Foundations can still be criticized in execution.

Adding or removing one is a project-level conversation, not a silent maintainer edit.

## Major disagreement

Voting can resolve a major contested direction after the competing versions have been developed enough to compare fairly.

Do not turn every scene into parliament.

Do not vote on a sentence-long alternate pitch against a finished canon arc and call the result objective.

## Full project view

Use Obsidian when you want the real folder hierarchy, backlinks, systems, character files, lore, and current production bible.

For a normal Git installation, the one-time clone command is:

```bash
git clone https://github.com/nathaniel-bonolo/peak-piece.git
```

Then open the generated `peak-piece` folder as an Obsidian vault.

Do **not** tell somebody to use `gh repo clone` unless GitHub CLI is installed. Plain Git does not provide the `gh` command.

## Source of truth

> **Docs/Discord are the easy writers' room. Obsidian is the full project view. GitHub is the filing cabinet underneath.**

GitHub remains useful because this project can grow into hundreds or thousands of linked files and benefits from exact folder structure, history, diffs, branches, and one authoritative current state.

Writers do not need to care about those mechanics unless they want to.

## No silent rule changes

A GitHub change can be technically authoritative while still being socially deceptive if the people collaborating never saw it.

If a change affects project identity, governance, or foundations:

1. discuss it with the current contributors
2. announce the decision in the writers' room
3. mirror the result into GitHub

Do not use somebody's Git unfamiliarity as accidental consent.

## Forking is a safety valve, not governance

A project can always branch or fork if contributors want fundamentally different adaptations.

But "just fork it" is not a substitute for clear collaboration, especially when some writers have not successfully set up Git yet.

Help people preserve their work and credits if a split happens.

## Future ideal

The ideal writing platform has Docs-level onboarding with Obsidian-level structure:

> **log in → open project → write**

Infrastructure should disappear for writers who do not care about infrastructure.
