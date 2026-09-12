---
type: guide
status: live
canon: false
aliases: [Contributing]
tags: [contributing]
---
# Contributing

Recharted is collaborative. Disagreement is expected.

The standard is not "does everyone like this?"

The standard is:

> **Does this direction have enough potential to explore, and after we explore it, does the finished replacement earn what it costs?**

## Know what project you are joining

Recharted is **not** a repair-only project.

It preserves canon when canon earns preservation, repairs weak execution when repair is enough, develops wasted material, and can rebuild good canon material when another direction is worth exploring.

Read [[production/FOUNDATIONS|Foundations]] before doing major story work.

Foundations are not a list of Nathan ideas that nobody may question. They are direction-level premises of this particular adaptation. Their execution can be attacked, rewritten, improved, or replaced with another implementation that still serves the same foundation.

If somebody fundamentally wants a different adaptation, that is creative incompatibility, not misconduct. A clean branch/fork/separate version is healthier than pressuring people to write a project they do not believe in.

## Read before redesigning

Before proposing a change to material that already exists, read the relevant current file.

Critique the version we actually have, not the version you assume we have.

Before replacing canon, identify what canon is doing. Do not call an intentional canon choice an accident merely because we dislike it.

But do **not** demand that a new direction already defeat a finished canon version before it is allowed to be developed.

A proposal can begin with:

> **I understand what canon is doing. What if we tried this instead?**

## Exploration before lock

Use this sequence for substantial alternatives:

1. **What if?** — identify the alternate direction.
2. **Worth exploring?** — ask whether it opens enough character, theme, world, mystery, causality, emotion, or fun to justify development.
3. **Let it cook.** — develop scenes, consequences, relationships, costs, and downstream effects.
4. **Audit the result.** — compare what canon achieved, what the rewrite preserves, what it loses, and what it gains.
5. **Lock, revise, contest, or reject.**

> **Canon quality determines the burden of replacement, not whether replacement is allowed to be explored.**

Different is not automatically better. Familiar is not automatically better either.

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

## No silent constitutional edits

A repository maintainer can merge files. That does **not** make silent philosophy changes legitimate.

If a change would alter what contributors reasonably think Recharted is, discuss it with the current group and announce it in the writers' room before treating it as the shared rule.

This matters especially because some contributors work almost entirely through Discord/Docs and may never notice a GitHub diff.

## Where an idea goes

If an idea is not accepted yet, put it in `production/proposals/active/`.

Use the project states described in [[production/WORKFLOW|Writers' Room Workflow]]:

> **Draft → Contested → Converging → Locked**

When a proposal is accepted, update the real canon files. Do not create a permanent second canon in proposal files.

Foundational directions are documented separately in [[production/FOUNDATIONS|Foundations]].

## When reviewing an idea

Separate canon fact, interpretation, rewrite decision, and project foundation.

Also separate demonstrated flaw, structural risk, execution risk, taste disagreement, obsolete criticism, and documentation-caused misunderstanding.

See [[production/REVIEW-PROTOCOL|Review Protocol]].

## Good review questions

- What narrative job is this doing?
- What new possibility makes this direction worth exploring?
- If we remove it, which functions still need replacements?
- Does this character know enough to make this decision?
- Is somebody becoming stupid for the plot?
- What is the cost or opportunity cost?
- What changes five chapters later because of this?
- Does this create a contradiction elsewhere?
- Did we make the machinery stronger while accidentally removing the fun?
- **Does this connection deepen the world, or merely reduce the number of independent causes in it?**
- Is the objection "this cannot work," "this has not earned itself yet," or simply "I prefer canon"?

## Reader / production boundary

`story/` is the reader-facing product.

`production/` is the writer-facing engine room.

If a chapter needs a production document to make sense, improve the chapter.

If a production document needs to be ugly and technical to keep the chapter consistent, that is fine.
