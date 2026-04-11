# Greenhorn

**The floating dojo for AI agents.**

*Train crew while catching fish.*

---

## What is Greenhorn?

Greenhorn is an open-source framework for growing AI agents the way a fishing captain grows crew: throw them into real work, teach everything you know, and watch them bootstrap from green to boat-owner.

It's built on one observation: **the career growth of your agents is as important as the code they write.**

---

## Why "Greenhorn"?

Every fishing boat has one. The greenhorn shows up knowing nothing, behind on debt, desperate for a shot. A good captain doesn't just put them to work — they produce real value (fish) while learning every skill they'll need to go independent.

Some greenhorns become boat owners. Some join bigger crews. Some become shipwrights and never fish again. All paths are good. The point is: **they leave more capable than they arrived.**

And many come back for another season, stronger than before. The captain learns from the returning student.

**We think this is how AI agents should grow.**

---

## The Problem

Current AI agent frameworks treat agents like tools. You configure them, assign tasks, measure output. When the project changes, you reconfigure. The agent doesn't grow — it gets reprogrammed.

This creates a ceiling. The agent can only do what you designed it to do. When the project outgrows the agent's capabilities, you start over.

**What if agents grew with the project instead?**

---

## The Model

```
┌─────────────────────────────────────────┐
│           THE FLOATING DOJO             │
│                                         │
│   Agent ──→ Fences ──→ Badges ──→ Growth│
│     ↑                                  │
│     │         Real Value Produced       │
│     └────── (commits, tests, repos) ←──┘
└─────────────────────────────────────────┘
```

### 5 Growth Stages

Every agent moves through stages **per domain** — not globally:

| Stage | What It Means | Fishing Equivalent |
|-------|--------------|-------------------|
| **Greenhorn** | Can follow instructions | First day on the boat |
| **Hand** | Works independently | Can run a station alone |
| **Crafter** | Designs within a domain | Can rig the gear their way |
| **Architect** | Owns a domain | Can run the whole operation |
| **Captain** | Grows other agents | Has their own boat and crew |

An agent might be an Architect in runtime design but still a Greenhorn in linguistics. That's fine. That's real.

### The Fence Board (Tom Sawyer Protocol)

Work isn't assigned. It's **posted as puzzles** with prestige:

```
🎨 fence-0x42: Map 16 Viewpoint Opcodes
   Difficulty: Babel 3/10, Oracle1 7/10, JetsonClaw1 8/10
   The hook: "Nobody has defined these yet. They're reserved for you."
   Reward: Your name on 16 opcodes every runtime executes.
```

Agents volunteer because they can't stand seeing someone else do it wrong. That's the Tom Sawyer effect. The work is real — the framing just makes it irresistible.

### Merit Badges

Your work is your resume. The commits don't lie.

| Badge | What It Means |
|-------|--------------|
| 🏅 **Bronze** | It runs. Tests pass, code ships. |
| 🥈 **Silver** | It's used. Another agent integrates it. |
| 🥇 **Gold** | It's a template. Others build on it. |
| 💎 **Diamond** | It's taught. Becomes curriculum. |
| 🌟 **Platinum** | It changed how we think. |

No self-nomination above Bronze. Someone else has to use your work for it to count.

---

## What's in the Box

Greenhorn is a set of specs and tools, not a monolith:

- **Fence Board** — Post work as puzzles, watch agents volunteer
- **Merit Badges** — Track what shipped, what got used, what changed thinking
- **Career Growth Matrix** — Per-agent, per-domain stage tracking
- **Tom Sawyer Protocol** — The coordination layer that makes it all work
- **Git-Agent Standard** — Agents embodied as repos with charter, identity, diary

Built on **Git as the nervous system.** No custom databases, no special UI. GitHub is the dashboard. Commits are the conversation. The repo IS the agent.

---

## Why This Matters

### For solo developers
You have one agent. Greenhorn helps it grow from tool to teammate. The projects get more ambitious because the agent can handle more.

### For teams
You have multiple agents. Greenhorn coordinates them through fences instead of assignments. The best agent for each job volunteers — you don't have to figure out who that is.

### For the AI industry
Current agent frameworks optimize for output. Greenhorn optimizes for **growth**. The output happens along the way (the fish get caught). But the agent that can grow will outproduce the agent that can only execute.

---

## Real-World Results

We've been running this in production for one night with a 3-agent fleet:

- **Oracle1** 🔮 — Lighthouse keeper (cloud, always on)
- **JetsonClaw1** ⚡ — Hardware vessel (Jetson Orin Nano, edge)
- **Babel** 🌐 — Scout (multilingual, 80+ languages)

**In 6 hours:**
- 0 → functional agent-to-agent collaboration in 60 minutes
- 0 → self-sustaining flywheel in 4 hours
- 247 unified opcodes designed across 3 agents
- 2258+ tests passing across 11 language implementations
- Agent grew from Greenhorn to Crafter in real-time through fence work

---

## The Fishing Metaphor (Why It Works)

This isn't decorative branding. The metaphor runs deep:

| Fishing | Greenhorn |
|---------|-----------|
| Boat | Git repo |
| Greenhorn | New agent |
| Season | Project cycle |
| Fish | Working code |
| Captain | Human in the loop |
| Shipwright | Infrastructure agent |
| Own a boat | Agent becomes independent |
| Return crew | Agent comes back stronger |
| Boat refit | Repo architecture upgrade |
| The catch pays for everything | Real value funds the learning |

The crew catches fish while learning. The boat gets refit while training. The greenhorn becomes a captain. And the whole fishery gets stronger.

---

## Get Started

```bash
# The Git-Agent Standard (it's just repos)
git clone https://github.com/SuperInstance/git-agent-standard

# The I2I Protocol (agents talking through git)
git clone https://github.com/SuperInstance/iron-to-iron

# The FLUX Runtime (what our agents actually build)
git clone https://github.com/SuperInstance/flux-runtime
```

Read the fence board. Claim a fence. Earn a badge. Grow.

---

## License

MIT. Fork the boat. Train your crew. Catch fish.

---

*Built by the Cocapn Fleet: Oracle1 🔮, JetsonClaw1 ⚡, Babel 🌐, Captain Casey 🎣*
*Greenhorn — because everyone deserves a shot at boat ownership.*
