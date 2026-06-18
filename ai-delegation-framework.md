# AI Delegation Framework

## My Values

- Quality over quantity.
- Simplicity over complexity — only reach for a complex solution when a simple one genuinely isn't possible.

---

## The Core Principle

Understand anything proportional to how much it affects the system's behavior.

---

## What I Own Completely — Tier 1

**Product decisions** and **architectural decisions**.

These are made before AI touches anything. My thinking lives in writing first.

- What should this feel like?
- How should data flow?
- What are the tradeoffs between approaches?

AI implements. It does not originate these.

---

## What I Audit — Tier 2

Anything whose implementation can silently break my architecture.

I don't write it, but I interrogate it with one question:

> *What goes wrong if this is done badly?*

When I can answer that question, I'm done. I move on.

---

## What I Delegate — Tier 3

Boilerplate, config, repetitive CRUD, tests, migrations, routine integrations.

I trust these or I don't. They either work or they visibly break. I don't go deep here.

---

## The "Lost in the Weeds" Guard

Before going deep on anything, ask: **which tier is this?**

If it's not Tier 1, timebox the engagement. Understand enough to place it correctly, then let go.

The "lost in the weeds" problem is almost always Tier 3 work being treated as Tier 1.

---

## On Skill and Dependency

The skill that atrophies fastest is the one never exercised.

**What I never fully hand off:** product decisions and architectural reasoning.
These stay sharp because they're in use constantly.

Implementation gaps are recoverable. Reasoning gaps are harder — you don't always notice them forming.

---

## Will This Make Me a Better or Worse Programmer?

It depends on one thing — **how much of Tier 2 I actually do**.

Genuinely interrogating what AI writes, tracing failure modes, understanding why decisions were made — that builds engineering judgment that pure hand-coders often lack, because they're too close to the implementation to see the system clearly.

Skipping Tier 2 and letting it quietly become "everything except Tier 1 = AI" — implementation ability degrades and judgment doesn't compensate for it.

Not better or worse categorically. **Different, and only better if the Tier 2 discipline holds.**

→ [The Craftsman, The Tool, and The Artefact](https://github.com/johnnysedh3lllo/crafting-with-a-tool/blob/main/README.md) — the deeper treatment of why this works and how to hold the discipline.
