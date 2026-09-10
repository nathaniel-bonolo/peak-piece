---
type: guide
status: live
canon: false
aliases:
  - Contributing
tags:
  - contributing
---

# Contributing

Peak Piece is collaborative. Disagreement is expected.

The standard is not "does everyone like this?"

The standard is:

> **Does this make the story better, and can it survive questions?**

## Read before redesigning

Before proposing a change to material that already exists in Peak Piece, read the relevant current file.

Critique the version we actually have, not the version you assume we have.

If you want to replace an accepted idea, identify:

- what the current version is doing
- what problem you see
- what your replacement does better
- what would be lost

Canon *One Piece* is not automatically the starting point once Peak Piece has already rewritten that material.

For example, Wano discussion should start from [[story/sagas/soul-feast/arcs/soul-feast/arc|Soul Feast]], not silently reset to canon Onigashima.

## Where an idea goes

If an idea is not accepted yet, put it in `production/proposals/active/`.

Do not put contested material directly into `production/systems/`, `production/characters/`, `production/lore/`, or `story/`.

When a proposal is accepted, update the real canon files.

The proposal can then be archived.

There is intentionally no permanent "accepted proposals" folder because that would create a second source of truth.

## When reviewing an idea

Separate:

- **Canon fact** - what actually happens in *One Piece*
- **Interpretation** - what we think the narrative purpose, theme, or authorial intent may be
- **Rewrite decision** - what Peak Piece changes and why

Do not silently turn interpretation into fact.

## Good review questions

- What narrative job is this scene or mechanic doing?
- If we remove it, which functions still need replacements?
- Are we preserving a canon beat only because canon had it?
- Does this character know enough to make this decision?
- Is somebody becoming stupid for the plot?
- What is the cost or opportunity cost?
- What does the world do differently because this exists?
- What happens five chapters later because of this decision?
- Does this create a contradiction somewhere else?
- Can the audience infer this through action instead of exposition?
- Did we make the machinery stronger while accidentally removing the fun?

## Editing accepted canon

Prefer editing the smallest number of authoritative files needed.

Do not copy the same explanation into six files.

## Tone

Critique the work aggressively if needed.

Do not make disagreement personal.

If an idea is weak, explain why it is weak and what function it fails to perform.

If you think an existing idea should be deleted, identify what would be lost before deleting it.

## Obsidian workflow

When adding a major character, system, lore, or story file:

- add useful wikilinks to related authoritative notes
- add the note to the relevant `production/indexes/` map of content
- prefer path-qualified wikilinks
- keep unresolved material in `production/proposals/`

Backlinks should emerge from actual relationships, not from dumping a giant "see also" list into every note.


## Maintain the canon audit

When a major rewrite changes **why** a character, arc, faction, or system works differently from canon, update its production-side canon audit.

Character/system audits normally live beside their production files. Story audits mirror the reader path under `production/story-notes/`. The audit contains the argument; the story contains the result. Do not paste a five-paragraph defense of the rewrite into a reader-facing arc note.

When making a canon claim, include a useful chapter/volume anchor. When making an author-intent claim, distinguish confirmed intent from interpretation. When using history/science/psychology, link a source in `production/references/` and state only what it actually supports.

See [[production/references/canon/source-policy|Canon Audit Source Policy]].


## Reader / production boundary

`story/` is the reader-facing product.

`production/` is the writer-facing engine room.

Do not move technical reasoning into the reader layer merely because the reasoning is important to us.

If a chapter needs a production document to make sense, improve the chapter.

If a production document needs to be ugly and technical to keep the chapter consistent, that is fine.
