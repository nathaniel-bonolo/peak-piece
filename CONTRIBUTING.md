---
type: guide
status: live
canon: false
aliases: [Contributing]
tags: [contributing]
---
# Contributing

Peak Piece is collaborative. Disagreement is expected.

The standard is not "does everyone like this?"

The standard is:

> **Does this make the story better, and can it survive questions?**

## Read before redesigning

Before proposing a change to material that already exists, read the relevant current file.

Critique the version we actually have, not the version you assume we have.

If you want to replace an accepted idea, identify what the current version is doing, what problem you see, what your replacement does better, and what would be lost.

## Two contributor workflows

Nobody has to become a Git nerd to write.

Use Discord/shared Docs for the easiest brainstorming and drafting surface.

Use Obsidian when you want the full linked project, folder hierarchy, backlinks, and production bible.

GitHub remains the source of truth underneath both workflows.

For plain Git:

```bash
git clone https://github.com/nathaniel-bonolo/peak-piece.git
```

Do not use `gh repo clone` unless GitHub CLI is installed.

See [[production/WORKFLOW|Writers' Room Workflow]].

## Where an idea goes

If an idea is not accepted yet, put it in `production/proposals/active/`.

When a proposal is accepted, update the real canon files. Do not create a permanent second canon in proposal files.

## When reviewing an idea

Separate canon fact, interpretation, and rewrite decision.

Also separate demonstrated flaw, structural risk, execution risk, taste disagreement, obsolete criticism, and documentation-caused misunderstanding.

See [[production/REVIEW-PROTOCOL|Review Protocol]].

## Good review questions

- What narrative job is this doing?
- If we remove it, which functions still need replacements?
- Does this character know enough to make this decision?
- Is somebody becoming stupid for the plot?
- What is the cost or opportunity cost?
- What changes five chapters later because of this?
- Does this create a contradiction elsewhere?
- Did we make the machinery stronger while accidentally removing the fun?
- **Does this connection deepen the world, or merely reduce the number of independent causes in it?**

## Reader / production boundary

`story/` is the reader-facing product.

`production/` is the writer-facing engine room.

If a chapter needs a production document to make sense, improve the chapter.

If a production document needs to be ugly and technical to keep the chapter consistent, that is fine.
