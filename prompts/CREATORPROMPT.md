---
type: guide
status: live
canon: false
aliases: [Creator Prompt, Creator Evaluation Prompt]
tags: [project, ai, onboarding, creators]
---
# Creator Evaluation Prompt

This prompt is for a One Piece creator, reviewer, streamer, essayist, or serious fan who wants to know whether Peak Piece is worth exploring without manually reading the whole production bible first.

Copy/paste this prompt into a repository-capable ChatGPT session:

```text
I'm deciding whether Peak Piece is worth exploring further as someone who discusses One Piece seriously.

Repository:
https://github.com/nathaniel-bonolo/peak-piece

Treat the repository as the source of truth. Do not evaluate the project from this prompt alone.

First establish the current project state by reading:
- project.json
- README.md
- production/FOUNDATIONS.md
- production/DECISION-STATUS.md
- production/WRITING-PHILOSOPHY.md
- production/REVIEW-PROTOCOL.md
- the newest relevant section of CHANGELOG.md

Then inspect enough actual character, system, faction, story, proposal, and canon-audit files to answer the task below from evidence rather than from the project's self-description.

Your first task is to tell me whether there is enough substance here to justify further exploration as a One Piece creator.

Do not give me a promotional pitch. Be skeptical.

In your answer:
1. Explain what Peak Piece is actually trying to do and how it differs from a simple "fix One Piece" project.
2. Choose several representative changes, including at least one radical character change and one world/system change.
3. For radical changes, inspect the relevant canon audits before judging whether the writers understand what they are replacing.
4. Identify the strongest or most distinctive current ideas and explain why they are interesting.
5. Identify serious weaknesses, unresolved risks, underdeveloped areas, or places where the project may be overengineering itself.
6. Identify meaningful things canon does well that Peak Piece sacrifices, changes, or risks losing.
7. Distinguish foundational / locked material from draft implementation, contested extensions, active proposals, and rejected / superseded material.
8. If documents conflict, report the contradiction instead of silently choosing the version you prefer.
9. Distinguish what the repository explicitly says from your own inference.
10. End with 3-5 specific rabbit holes, files, or questions that would be most useful to explore next if I decide to continue.

Do not assume closer adherence to canon is automatically better.
Do not assume being more different is automatically better.
Evaluate whether each alternate direction earns its cost on its own terms.

If I make a claim about Peak Piece while we talk, verify it against the current repository instead of assuming I am correct.
```

## Why this exists

A creator should not have to navigate hundreds of production files before finding out whether the project contains anything worth their time.

The repository remains the source of truth.

ChatGPT is the ingestion layer: it can follow a creator's curiosity across audits, characters, systems, factions, history, proposals, and story without forcing the creator to learn the repository structure first.
