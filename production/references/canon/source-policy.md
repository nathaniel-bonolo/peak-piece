---
type: reference-policy
status: live
canon: false
aliases:
  - Canon Audit Source Policy
tags:
  - reference
  - canon
  - audit
---

# Canon Audit Source Policy

Canon audits are writer-facing production material.

## Where audits live

For production material, keep the audit beside the thing it audits when practical.

Examples:

- `production/characters/robin/canon-audit.md`
- `production/systems/haki-canon-audit.md`

Reader-facing `story/` is the exception.

Do **not** place canon arguments back inside the reader layer just to keep an audit physically adjacent.

Story audits live under the mirrored path in:

- `production/story-notes/`

Example:

- story: `story/sagas/soul-feast/arcs/soul-feast/arc.md`
- audit: `production/story-notes/sagas/soul-feast/arcs/soul-feast/canon-audit.md`

This preserves the reader/production boundary.

## Required sections

A mature audit should distinguish:

1. **Canon baseline** - what the manga actually establishes.
2. **Canon function / interpretation** - what that material appears to be doing. Unless Oda explicitly confirmed intent, label this as interpretation.
3. **Problems Peak Piece identifies** - the specific failure, contradiction, missed opportunity, or deliberate disagreement.
4. **Peak Piece response** - what we changed, with links to authoritative files.
5. **Why this solution** - why this fix was chosen over alternatives.
6. **What survives** - what was worth preserving.
7. **What is intentionally rejected** - what we understand and still choose not to keep.
8. **Failure modes to watch** - how our own fix could become worse.
9. **References** - canon anchors and relevant external research.

## Reference hierarchy

Prefer:

1. manga chapter / volume
2. SBS or explicit Oda statement
3. official supplementary material
4. reputable secondary reference used as navigation
5. fan analysis, videos, Reddit, and theory posts clearly labeled as interpretation

Never turn a fan interpretation into "Oda intended" without evidence.

## Rule

The audit can be obsessive.

The story should not be.

> **The repository contains the argument. The audience gets the story.**

See [[production/WRITING-PHILOSOPHY|Writing Philosophy]].
