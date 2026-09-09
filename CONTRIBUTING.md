# Contributing

Peak Piece is collaborative. Disagreement is expected.

The standard is not "does everyone like this?" The standard is "does this make the story better, and can it survive questions?"

## Where an idea goes

If an idea is not accepted yet, put it in `proposals/active/`.

Do not put contested material directly into `systems/`, `characters/`, `lore/`, or `story/`.

When a proposal is accepted, update the real canon files. The proposal can then be archived. There is intentionally no permanent "accepted proposals" folder because that would create a second source of truth.

## When reviewing an idea

Try to separate three things:

- **Canon fact:** what actually happens in *One Piece*.
- **Interpretation:** what we think the narrative purpose or authorial intent was.
- **Rewrite decision:** what Peak Piece is changing and why.

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

## Editing accepted canon

Prefer editing the smallest number of authoritative files needed.

For example, if a proposal changes Pudding's role in Whole Cake Island, the accepted result may require edits to:

- `characters/pudding/`
- `story/.../whole-cake-island/arc.md`
- possibly `systems/` if a mechanic changed

Do not copy the same explanation into six files.

## Tone

Critique the work aggressively if needed. Do not make disagreement personal.

If an idea is weak, explain why it is weak and what function it fails to perform.

If you think an existing idea should be deleted, identify what would be lost before deleting it.

## Obsidian workflow

The repository can be opened directly as an Obsidian vault.

When adding a major character, system, lore, or story file:

- add useful wikilinks to related authoritative notes
- add the note to the relevant `indexes/` map of content
- prefer path-qualified wikilinks
- keep unresolved material in `proposals/`

Backlinks should emerge from actual relationships, not from dumping a giant "see also" list into every note.
