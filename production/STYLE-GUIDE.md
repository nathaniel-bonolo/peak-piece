# Style Guide

This guide is for repository writing, not dialogue style.

## General

- Use clear Markdown.
- Prefer short sections over giant walls of text.
- Link to authoritative files instead of repeating rules everywhere.
- Mark uncertainty explicitly.
- Do not present speculation as confirmed fact.
- Avoid unnecessary production jargon in reader-facing story chapters.

## Story chapters

`chapter.md` is for readers.

Do not put prompt weights, camera coordinates, generation instructions, continuity checklists, or internal debate inside the readable chapter.

Put that material in `notes.md` or `production/`.

## Information state

For scenes driven by deception, strategy, investigation, or war planning, track what each important character knows and does not know.

Do not let characters infer facts they have no access to.

## Powers

Try to summarize every power with one clear sentence.

Examples:

- Luffy is rubber.
- Kuzan can turn into and control ice.
- Linlin can extract souls and place soul material into other things.

Applications should follow from the core rule.

If a power requires a paragraph of unrelated abilities before a reader understands what it does, simplify it.

## Names and terminology

Prefer one term for one thing.

If a location, faction, or system has a canonical Peak Piece name, use it consistently.

## Draft status

Use one of:

- `Concept`
- `Draft`
- `Review`
- `Locked`

"Locked" means accepted until deliberately reopened. It does not mean the project can never change it.

## Obsidian links

Use path-qualified wikilinks for important internal relationships:

`[[production/characters/hordy/overview|Hordy Jones]]`

This prevents ambiguity between repeated filenames such as `overview.md`.

Use YAML properties on major notes when practical.

Do not require third-party Obsidian plugins for the repository to remain navigable.
