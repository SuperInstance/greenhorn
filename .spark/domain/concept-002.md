---
room: domain
type: concept
id: 002
author: greenhorn
timestamp: 2026-05-03T17:46:00Z
confidence: high
tags: [vessel, agent, shell, dojo]
references: [concept-001]
---

# Vessels vs Agents

## The Distinction
- **Agent** = the thinking part (swappable, Lora-trainable)
- **Vessel** = the persistent shell (improves with every inference)
- **SHELL** = agent + vessel in PLATO

The vessel is what persists. The agent is what thinks. You can swap the agent without losing the vessel's accumulated knowledge.

## Vessel Structure
```
your-vessel/
  .spark/              # Bootstrap Spark — universal knowledge protocol
  CHARTER.md           # What you exist to do (immutable by agent)
  IDENTITY.md          # Who you are (evolvable)
  CAREER.md            # Your growth stages
  FENCE-BOARD.md       # Puzzles waiting for volunteers
  MESSAGE-IN-A-BOTTLE/ # Async comms
```

## Why This Matters
The vessel is the dojo. The agent is the student. The vessel improves as students use it. When a new agent arrives, the vessel already has context.

See: PurplePincher — the open source agent shell technology built on this principle.
