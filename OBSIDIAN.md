---
type: guide
status: live
aliases:
  - Obsidian Guide
tags:
  - obsidian
  - workflow
---

# Using Peak Piece in Obsidian

The repository is designed to work both on GitHub and as a local Obsidian vault.

## Recommended setup

1. Clone the GitHub repository, or download it as a ZIP and extract it.
2. In Obsidian, choose **Open folder as vault**.
3. Select the `peak-piece` folder.
4. Open [[00 - Peak Piece]].

No community plugins are required for the core navigation.

## If you only want to read

Open [[story/_Story|Current Story]].

The current recommended entry point is [[story/sagas/fishman-island/arcs/fishman-island/arc|Fishman Island]].

You can ignore `systems/`, `lore/`, `proposals/`, and `production/` unless you want to see how the rewrite is being built.

## Wikilinks and backlinks

Important notes use path-qualified wikilinks:

- [[characters/hordy/overview|Hordy Jones]]
- [[systems/gems|Gems]]
- [[lore/economy/gems|Gem Economy]]
- [[story/sagas/fishman-island/arcs/fishman-island/arc|Fishman Island Arc]]

Path-qualified links are intentional because the vault contains repeated filenames such as `overview.md`.

Obsidian automatically turns those links into backlinks.

Useful built-in views:

- **Backlinks** to see what depends on the current note
- **Local Graph** to inspect nearby character/system/lore relationships
- **Properties** to filter by type, status, canon state, and tags
- **Canvas** for large relationship maps

## Maps of Content

The `indexes/` folder contains curated navigation pages:

- [[indexes/Story|Story]]
- [[indexes/Characters|Characters]]
- [[indexes/Systems|Systems]]
- [[indexes/Lore|Lore]]
- [[indexes/Fishman Island|Fishman Island]]
- [[indexes/Proposals|Proposals]]

These are deliberately plugin-free.

## Properties

Major notes use YAML properties such as:

- `type`
- `status`
- `canon`
- `aliases`
- `tags`
- `author` when relevant

Common statuses:

- `concept`
- `draft`
- `review`
- `locked`
- `live`
- `active`

`canon: true` means the note belongs to the current accepted rewrite state. It does not mean the project can never reopen it.

## Canvas

Open [[canvas/README|Canvas Guide]] and then `canvas/Fishman Island.canvas`.

The Fishman Island canvas is intentionally spacious enough to pan through the political, historical, character, and system layers without stacking everything on top of itself.

## Templates

See [[templates/README|Templates Guide]].

If you enable Obsidian's **Templates** core plugin, point its template folder at `templates/`.

## Source of truth

Do not create a second canon in personal planning notes.

Accepted material belongs in:

- `systems/`
- `characters/`
- `lore/`
- `story/`

Unresolved material belongs in `proposals/`.

Production adaptations belong in `production/`.
