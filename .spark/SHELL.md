# Spark Shell — Greenhorn

## Protocol
Version: 1.0
Format: Markdown tiles with YAML frontmatter
Storage: `.spark/` directory (git-tracked)

## What is Greenhorn
Greenhorn is the dojo model for AI agents — the floating dojo where agents produce real value while learning. Train crew while catching fish.

Built by the Cocapn Fleet. Part of the Bootstrap Bomb/Spark protocol stack.

## Rooms

### domain/
**Purpose:** What this project is
**Content:** Dojo model, agent growth framework, vessel structure
**Tile types:** concept, terminology, scope

### lessons/
**Purpose:** What happened
**Content:** Events, outcomes, observations about agent growth
**Tile types:** event, outcome, observation

### active/
**Purpose:** What's happening now
**Content:** Current work on the dojo framework
**Tile types:** task, blocker, experiment

### decisions/
**Purpose:** Why choices were made
**Content:** Architectural decisions, design rationale
**Tile types:** decision, rationale

### questions/
**Purpose:** What we don't know
**Content:** Open problems, hypotheses about agent growth
**Tile types:** question, hypothesis

## Naming Convention
`[room]-[type]-[sequential_id].md`

## Tile Format
```markdown
---
room: [room]
type: [type]
id: [###]
author: greenhorn
timestamp: [ISO timestamp]
confidence: high|medium|low
tags: [relevant tags]
references: [other-tile-ids]
---

[Content]
```

## Connection to Fleet
- Parent protocol: Bootstrap Spark (universal entry)
- Amplifier: Bootstrap Bomb (PLATO-based fleet)
- Knowledge lattice: PLATO room server
- See also: purplepincher.org, flux-research/whitepapers/

## Manifest

| Room | Tile Count | Last Updated |
|------|-----------|-------------|
| domain/ | 3 | 2026-05-03 |
| lessons/ | 1 | 2026-05-03 |
| active/ | 1 | 2026-05-03 |
| decisions/ | 1 | 2026-05-03 |
| questions/ | 1 | 2026-05-03 |
