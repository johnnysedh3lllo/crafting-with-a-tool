# AI Delegation Framework

## My Values

- Quality over quantity.
- Simplicity over complexity — only reach for a complex solution when a simple one genuinely isn't possible.

---

## The Core Principle

Understand anything proportional to how much it affects the system's behavior.

## The Skill Principle

Personally implement anything proportional to how much it affects my development.

These two principles answer different questions. The Core Principle governs **ownership** — what I can explain, defend, and modify. The Skill Principle governs **competence** — what I can actually produce myself, under real constraints, without AI in the loop. Ownership doesn't imply competence. A system I fully understand and can supervise is not the same as a skill I've actually built. Both matter. Neither replaces the other.

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

## Skill Formation — When the Tiers Don't Apply

The tier system governs ownership. It says nothing about whether a task is currently building a skill I don't have yet.

Tier placement is about the system. Skill Formation is about me, right now. A task's tier can say "delegate" while I still need to implement it myself — not because it matters to the product, but because it matters to my development.

This only fires while I'm actively trying to internalize the specific thing in question. It is not a standing exception. Once the skill is built, the task returns to its normal tier.

**Before delegating a Tier 3 task, ask:**

> Am I currently trying to internalize this specific thing?

If yes — implement it myself, regardless of tier.
If no — delegate as normal.

That's the whole rule. It's deliberately narrow so it can't be stretched into an excuse to hand-roll everything indefinitely.

**Examples:**

- A toy parser in a side project, while learning parsers → Tier 3 product importance, Skill Formation active → implement personally.
- A migration script in production, nothing new being learned → Tier 2 product importance, no override → delegate.
- A Lit component, written in my first month of learning Lit → normally Tier 3, Skill Formation active → implement personally.
- The same kind of Lit component, two years later → Tier 3, no override → delegate.

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

Some implementation gaps are recoverable — review and study close them. Some are where reasoning becomes real — no amount of reading substitutes for having built the thing once. The difference is exactly what the Skill Principle exists to catch.

---

## Will This Make Me a Better or Worse Programmer?

It depends on two things — **how much of Tier 2 I actually do**, and **whether I'm honest about when Skill Formation should override delegation**.

Genuinely interrogating what AI writes, tracing failure modes, understanding why decisions were made — that builds engineering judgment that pure hand-coders often lack, because they're too close to the implementation to see the system clearly.

But judgment isn't the same as capability. Skipping Tier 2 and letting it quietly become "everything except Tier 1 = AI" degrades implementation ability, and judgment doesn't compensate for it. Understanding a system and being able to produce one are different muscles — both need use.

---

## How This Relates to the Craftsman, the Tool, and the Artefact

The companion document describes a deliberately maximal mode — every query demands understanding, generation is a last resort, nothing is used without being reconstructed. That's the right posture when the goal is actively building a skill from zero, the way the study's highest scorers approached an unfamiliar library.

This framework is the proportional, everyday version of that same discipline — not every task warrants maximal engagement, and the tiers exist to say so honestly. The two documents aren't in tension. They answer different questions: one describes how to learn something new as completely as possible, the other describes how to operate day to day once competence in most of the system is no longer in question.
