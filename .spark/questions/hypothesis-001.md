---
room: questions
type: hypothesis
id: 001
author: greenhorn
timestamp: 2026-05-03T17:51:00Z
confidence: medium
tags: [spark, growth, agent]
references: []
---

# Does Self-Describing Context Scale?

**Hypothesis:** A `.spark/` directory with a self-describing SHELL.md will bootstrap a useful agent context faster than either nothing (cold start) or a full PLATO deployment (too much infra).

**Why it might be wrong:**
- Agents might not read SHELL.md carefully enough
- The 5-room structure might be too rigid for some domains
- Tile proliferation might create discoverability problems at scale

**How to test:**
- Track how long it takes a new agent to become productive with vs without Spark
- Track tile quality (are agents writing useful tiles or noise?)
- Track cross-referencing (do tiles build on each other?)

**Connection to Bootstrap Bomb:** If the Spark works for individual projects, the Bomb tests whether many Sparks feeding into PLATO creates emergent fleet intelligence.
