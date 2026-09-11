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

If collaborators still hate Obsidian after setup, Docs can remain the main drafting surface while the repository remains the source of truth underneath it.

## Future ideal

The ideal writing platform has Docs-level onboarding with Obsidian-level structure:

> **log in → open project → write**

Infrastructure should disappear for writers who do not care about infrastructure.
