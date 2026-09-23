---
type: guide
status: live
canon: false
aliases: [Contributing]
tags: [contributing]
---
# Contributing

Peak Piece is collaborative when people choose to contribute. Disagreement is expected.

The standard is not "does everyone like this?"

The standard is:

> **Does this direction have enough potential to explore, and after we explore it, does the finished replacement earn what it costs?**

## Know what project you are joining

Peak Piece is **not** a repair-only project.

It preserves canon when canon earns preservation, repairs weak execution when repair is enough, develops wasted material, and can rebuild good canon material when another direction is worth exploring.

Read [[production/FOUNDATIONS|Foundations]] and [[production/DECISION-STATUS|Decision Status]] before doing major story work.

Foundations are not a list of ideas that nobody may question. They are direction-level premises of this particular adaptation. Their execution can be attacked, rewritten, improved, or replaced with another implementation that still serves the same foundation.

If somebody fundamentally wants a different adaptation, that is creative incompatibility, not misconduct.

Peak Piece and **One Piece: Recharted** already demonstrate that two variants can grow from the same early collaboration without becoming competitors.

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

> **Preference is not refutation.**

## Ways to work with the project

Nobody has to become a Git nerd to contribute ideas.

Use whatever drafting surface is practical for the people involved: chat, shared Docs, local notes, or GitHub.

Use Obsidian when you want the full linked project, folder hierarchy, backlinks, and production bible.

Use [[prompts/AGENTPROMPT|Agent Prompt]] when you want a repository-capable AI to help navigate the project.

Use [[prompts/CONTRIBUTORPROMPT|Contributor Onboarding Prompt]] if you are not sure whether you fit best as a writer, beta reader, artist, researcher, editor, continuity reviewer, fight choreographer, designer, tooling contributor, or detailed reader. The onboarding is deliberately short-question-first rather than essay-first.

Using AI is not required to contribute. GitHub remains the source of truth.

For plain Git:

```bash
git clone https://github.com/nathaniel-bonolo/peak-piece.git
```

Do not use `gh repo clone` unless GitHub CLI is installed.

See [[production/WORKFLOW|Writers' Room Workflow]].

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
- **What irrational consequence survived anyway?**
- Is the objection "this cannot work," "this has not earned itself yet," or simply "I prefer canon"?

## Reader / production boundary

`story/` is the reader-facing product.

`production/` is the writer-facing engine room.

If a chapter needs a production document to make sense, improve the chapter.

If a production document needs to be ugly and technical to keep the chapter consistent, that is fine.
