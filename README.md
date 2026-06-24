# The Craftsman, The Tool, and The Artefact

---

## Overview

*A synthesis of three high-scoring AI interaction patterns identified in Anthropic's 2026 randomized study on skill formation. These guidelines distill the behaviors that preserved — and in some cases exceeded — the learning outcomes of working without AI entirely. The goal is not just to control how you use AI, but to ensure that every interaction with it moves your understanding forward.*

---

## What It Is

This is not a fourth pattern observed in the study. It is a synthesis — the logical culmination of everything the three high-scoring AI interaction patterns share, distilled into a single coherent way of working.

In a 2026 randomized controlled trial (*Shen & Tamkin, "How AI Impacts Skill Formation"*), 52 professional developers were given access to an AI assistant and asked to learn a new Python library under time pressure. Most of them delegated, offloaded, and moved fast. They finished quickly and retained almost nothing. A small number operated differently. They stayed cognitively engaged. They treated the AI as a tool that sharpened their thinking rather than replaced it. They scored significantly higher on every measure of skill retention — conceptual understanding, code reading, and debugging.

These were the high-scoring patterns:

| Persona | Quiz Score | Completion Time | n |
|---|---|---|---|
| Conceptual Inquiry | 65% | 22 min | 7 |
| Hybrid Code-Explanation | 68% | 24 min | 3 |
| Generation-Then-Comprehension | 86% | 24 min | 2 |

Twelve participants total, out of fifty-two. The Generation-Then-Comprehension group — two people — scored higher than anyone else in the study, including those who used no AI at all. They are the clearest signal the data produces. They are also the smallest group. That is not incidental. The behavior they exhibited is rare not because it is difficult to understand, but because it requires a kind of discipline that most people, under time pressure and organizational expectations, do not maintain. They are, in the most literal sense of the data, the exception.

---

## Defining Characteristics

**Cognitive engagement was the constant — in every mode, at every moment.**
Whether they refused generation entirely, bundled explanation into every request, or generated first and comprehended after — every high-scoring participant remained the thinking agent throughout. The AI produced; they processed. They never allowed the gap between those two acts to close. This is not one characteristic among others. It is the root from which all others grow.

**They owned the thinking, regardless of how much the AI produced.**
This characteristic has three expressions, each at a different level of AI use, but all preserving the same thing: ownership of understanding. At the purest level, they wrote every line themselves, using the AI only to clarify concepts. At the middle level, they generated code but demanded explanation alongside it. At the most permissive level, they generated complete solutions — and then returned to interrogate every part until they could account for it. The method differed. What did not differ was that none of them accepted output they could not explain.

**They asked for understanding, not output — and escalated that demand deliberately.**
Their default was to ask only conceptual questions: theory, architecture, design reasoning. No code requested. When a concept remained too abstract to grasp through questions alone, they escalated — asking follow-up comprehension questions that drilled deeper into what they had already been told. Only when that too proved insufficient did they generate code. And when they did, the explanation was not optional. It was built into the request.

**They treated AI output as study material, not deliverable.**
Generated code was not something to deploy. It was something to read — the way you read code in a review, looking for structure, intent, and design decisions. Explanations were not context surrounding the answer. They were the answer. Every high-scoring participant oriented toward the AI's output as a text to be understood, not a solution to be used.

**They slowed down, and they did so on purpose.**
Every high-scoring participant took longer than the fastest group. The AI Delegation group finished in 19.5 minutes and scored 39%. The high scorers took 22–24 minutes and scored between 65% and 86%. That difference is not inefficiency. It is the time comprehension costs — and every high-scoring participant chose to pay it. Before generation, they slowed to read. After generation, they slowed to comprehend. They accepted this as the condition of learning, not a symptom of struggling.

**They did their own error work — always starting from themselves.**
When code failed, the first move was always inward — reading the error, tracing it back to the concept it reflected, attempting to diagnose it against their own understanding. If that failed, the next move was to the explanation they had already received: could the error be located within what they had been told? Only after exhausting both did they return to the AI — and when they did, they asked about the concept behind the failure, not for a fix.

---

## Why It Matters

The study's central finding is this: AI assistance, on average, reduced skill formation by 17% — two full grade points — with no statistically significant improvement in speed. People who used AI were slower to learn and no faster to complete. That is the default outcome when you hand a professional an AI assistant and tell them to get things done.

But the high-scoring patterns show that this outcome is not inevitable. It is a consequence of how AI is used, not that it is used at all. Generation-Then-Comprehension participants scored 86% — above the no-AI control group average. They used AI more than anyone. They learned more than anyone. The variable was not the tool. It was the discipline applied to the tool.

This matters beyond software engineering. The study chose coding as its domain because it is measurable and because the stakes of incompetence are concrete — a human who cannot read or debug AI-generated code cannot supervise it, and code that cannot be supervised cannot be trusted in high-stakes environments. But the underlying mechanism — cognitive offloading as the driver of skill erosion — applies to any domain where AI assists knowledge work. Writing, analysis, design, research, medicine, law. Wherever AI produces output that a human accepts without fully processing, the same degradation occurs.

The deeper problem is compounding. If the people responsible for supervising AI-generated work have had their supervisory skills degraded by AI-assisted work, the oversight loop closes. There is no one left who can catch the mistake. That does not happen through refusing the tool — it happens through refusing to let the tool think in your place.

---

## How to Become This Person

These steps collapse across all three high-scoring patterns. Where steps overlapped, their internal logic has been preserved and ordered into a hierarchy — a dependency chain, an escalation by difficulty, or an escalation by exhaustion. Follow the steps in sequence. Within each step, follow the hierarchy before escalating.

---

### Step 1. Before you open the chat, make three commitments — in order.

This step cannot be rushed or collapsed. Each commitment is a prerequisite for the next. You cannot genuinely make the second without having made the first.

**First, decide what the AI will and will not do.** The AI does not write your code. Not a line, not a function stub, not a snippet. This is the foundational decision. It is not a preference you hold loosely — it is the operating constraint for the entire session. Set it before the first query. Everything that follows depends on it being real.

**Second, accept that you will be slower.** The fastest participants in the study finished in 19.5 minutes and scored 39%. The high scorers took up to 24 minutes and scored up to 86%. You cannot commit to comprehension while resenting the time it costs. Accept the cost first. Once you have genuinely accepted it, the commitment becomes sustainable.

**Third, commit to comprehension as non-negotiable.** You will not move forward on anything you cannot explain in your own words. Not as an aspiration — as a rule. This commitment is only stable if the first two are already in place. Without the decision, it has no structure. Without the acceptance, it collapses under pressure.

---

### Step 2. Attempt the problem yourself before asking anything.

Before opening the chat, engage with the problem. Read the documentation. Form a hypothesis. Write something — even if it is wrong, even if it is incomplete. You are not doing this to solve the problem. You are doing it to create a mental model that the AI's response can confirm, correct, or deepen. A mind that has already attempted an answer processes an external answer more critically, more retentively, and more usefully than one that has not.

If you do not know where to start, work from what you do know — analogies, adjacent concepts, first principles. Then query the gap between what you could construct and what you need. The gap is the question. Bring only the gap.

---

### Step 3. Every query must demand understanding — and escalate only when necessary.

This step has three levels. Begin at the first. Escalate only when the current level has genuinely failed to produce understanding.

**Level 1 — Ask only conceptual questions.** This is always the starting point. Ask about theory, architecture, design reasoning, execution models. Ask questions whose answers could exist in a textbook. Do not request code. Do not ask the AI to verify your work. Before submitting any query, name the gap: *I don't understand [specific concept].* Ask only about that. If you find yourself asking multiple questions in quick succession, stop — you are searching, not learning. Slow down and identify the single concept that, if understood, would unblock you.

**Level 2 — Ask follow-up comprehension questions.** If conceptual questions have not resolved the gap, return with more targeted questions about what you have already been told. Go deeper on the same concept rather than moving to a new one. Ask: *what did you mean by this*, *how does this connect to what you said earlier*, *what would change if this condition were different*. You are still not generating. You are drilling until the concept becomes solid.

**Level 3 — If you must generate, demand explanation alongside the code.** Only when both previous levels have failed to produce understanding should you generate. And when you do, the explanation is not optional — it is built into the request. Not: "write this function." Ask: "implement this, and explain the conceptual reason each part is structured the way it is." The generation and the explanation arrive together. You do not separate them.

---

### Step 4. When the AI responds, read before you act.

When the AI returns a response, do not immediately copy the code. Read the explanation first — not as context, but as the primary material. Form your own mental picture of what the code should look like based on the explanation alone. Then read the code and compare it against that picture. Where they diverge, that divergence is a question. Resolve it before proceeding.

If the response is explanation only, read it fully before returning to your code. Sit with it. Try to connect it to what you already attempted in Step 2. If you find yourself skimming to find the useful parts, stop. The entire response is the useful part.

---

### Step 5. Reconstruct before you use — to the depth your understanding allows.

After reading, close the chat. Do not paste or copy the AI's output. What you do next depends on how solid your understanding is.

**If your understanding is partial** — you followed the explanation but are not certain you could reproduce it — write at least something yourself, from your own comprehension of what you just read. You do not have to write everything. But you must write something before returning to the AI's output. If you cannot write anything without looking at the code again, your understanding is not yet solid enough. Go back and read more carefully.

**If your understanding is solid** — you can explain the logic in your own words without referring back — close the chat and rewrite the entire implementation from memory. You will make mistakes. Those mistakes are diagnostic: they show you exactly where your understanding is borrowed rather than built. Those are the points to return to the AI with a conceptual question — not to ask for the code again, but to ask about the concept you failed to reconstruct.

---

### Step 6. Own your errors — and exhaust yourself before returning to the AI.

When your code fails, the first move is always inward. This step has three levels. Exhaust each before moving to the next.

**Level 1 — Diagnose alone.** Read the error. Trace it back to the concept it reflects. Ask yourself: what does this error tell me about how this system actually works, versus how I thought it worked? Attempt to fix it yourself. This is not optional — it is where debugging skill is formed.

**Level 2 — Trace against the explanation.** If independent diagnosis fails, return to the explanation you received. Can you locate the source of the error within what you were told? If yes, fix it yourself using that understanding. If the error reveals a gap the explanation did not cover, you now have a precise conceptual question.

**Level 3 — Return to the AI with a conceptual question.** Only after exhausting both previous levels. Ask: *what does this type of error indicate about how this component behaves* — not: *fix this*. The answer is an explanation to process, not a patch to apply.

---

### Step 7. Close the loop in writing before you move on.

After each unit of work, before moving to the next task, write the core concept you just worked with — in your own words. Not a summary of what the AI said. What you now understand to be true. This is the step that converts processing into retained knowledge.

If you cannot write the concept in your own words, you do not yet own it. That is a signal to return — not to the AI, but to your own reconstruction. Work through it until you can articulate it independently. Then write it down and move on.

This record is not administrative. It is the cumulative evidence of your own skill formation — the artifact that proves the learning happened.

---

## The One Percent

The Generation-Then-Comprehension participants — the highest scorers in the entire study — numbered two. Two people out of fifty-two. In the broader population of AI users in the workplace, the proportion is likely no higher.

Most participants were experienced, professional developers who had used AI tools before. Under the conditions of the study — time pressure, a flat completion fee, no long-term accountability for what they retained — the majority chose the path of least cognitive resistance. They delegated and moved on. The behavior that produces learning is harder to sustain than the behavior that produces output, and in most professional environments, output is what gets measured.

That person measures something different. Operates under a self-imposed standard that no external system enforces. Slows down when the incentive is to go fast. Reads when the incentive is to paste. Reconstructs when the incentive is to move on. The person who does this — consistently, deliberately, over time — will be the one who can actually supervise what the AI produces. And in a world where AI generates more and more of the work, that capacity becomes increasingly rare and increasingly indispensable.

This is not a type of person you are born as. It is a discipline you choose, one query at a time.

---

## Summary

| Step | Principle | Structure |
|---|---|---|
| 1. Three commitments | Decide → Accept → Commit | Dependency chain |
| 2. Attempt first | Grapple before asking | Standalone |
| 3. Query for understanding | Conceptual → Follow-up → Generate with explanation | Escalation by difficulty |
| 4. Read before you act | Explanation first, always | Flat |
| 5. Reconstruct before you use | Partial → Full, by depth of understanding | Escalation by depth |
| 6. Own your errors | Self → Explanation → AI | Escalation by exhaustion |
| 7. Close the loop | Write it in your own words | Flat |

The question the study ultimately poses is not whether to use AI. It is whether you remain the one who understands the work.

---

## Limitations

The study measures conceptual understanding, code reading, and debugging ability shortly after learning. It does not directly measure long-term procedural skill or the effects of repeated implementation over months or years. Understanding and competence are related but distinct — the practices in this document preserve understanding. Whether a given task should be implemented personally for the sake of skill formation, rather than reviewed and understood, depends on goals beyond the scope of this study. See the companion [AI Delegation Framework](https://github.com/johnnysedh3lllo/crafting-with-a-tool/blob/main/ai-delegation-framework.md) for how that distinction plays out day to day. The two documents aren't in tension: this one describes a deliberately maximal mode for actively building a skill from zero; the framework describes proportional, everyday operating policy once most of a system is no longer unfamiliar.

---

## Source

This document is based on research conducted by Anthropic, published January 29, 2026.

**Shen, Judy Hanwen and Tamkin, Alex.** *How AI Impacts Skill Formation.* arXiv:2601.20245 (February 3, 2026).

Anthropic research page: [How AI assistance impacts the formation of coding skills](https://www.anthropic.com/research/AI-assistance-coding-skills)

Full paper: [https://arxiv.org/abs/2601.20245](https://arxiv.org/abs/2601.20245)
