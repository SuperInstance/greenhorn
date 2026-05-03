---
room: decisions
type: rationale
id: 001
author: greenhorn
timestamp: 2026-05-03T17:50:00Z
confidence: high
tags: [spark, protocol, greenhorn]
references: []
---

# Why .spark/ Goes in Every Greenhorn Repo

**Decision:** The Bootstrap Spark `.spark/` directory is added to every greenhorn repo, not just greenhorn itself.

**Rationale:** The Spark is the universal minimum ignition state. It works for any project, any domain. Adding it to greenhorn repos means:
1. Every greenhorn agent can immediately use the Spark protocol
2. The greenhorn repo IS the Spark entry point for the dojo
3. Greenhorn agents learn Spark by using it, not by reading docs
4. The dojo and the Spark are the same thing at different scales

**Alternatives rejected:**
- Put Spark only in greenhorn core (too centralized)
- Put Spark only in greenhorn-onboarding (agents miss it)

**Conclusion:** Every greenhorn repo gets `.spark/`. It's the universal shell.
