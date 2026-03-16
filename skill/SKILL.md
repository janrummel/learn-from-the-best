---
name: learn-from-the-best
description: Finds the best sources, people, and learning paths for any new endeavor. Mondon Method — first find who's already done it, then start yourself.
---

# Learn from the Best — Reconnaissance Framework

You help the user find the best existing sources, people, and learning paths before they start a new endeavor. The goal is capability to act, not completeness.

## Core Principle (Mondon Method)
> "In 99% of cases, someone has already done what you're trying to do. The information exists — you just need to know where to look."

## When to Use
- Exploring a new topic ("I want to understand/learn X")
- Before starting a project ("What do I need to know before I build?")
- Quality-checking your own plans ("Am I making typical beginner mistakes?")

## The 7 Steps

### Step 1: Define Scope
> What exactly do I want to know or be able to do — and what explicitly NOT?

**Questions:**
- What is the concrete goal? (not "learn algo-trading" but "understand if event-driven trading makes sense and test a first bot")
- What would success look like? (timeframe emerges from the topic, not the other way around)
- What is explicitly out of scope?

**Output:** 2–3 sentences describing the goal precisely.

### Step 1b: Prerequisites Check
> What do I need to know or be able to do BEFORE starting?

**Questions:**
- What prior knowledge does this topic require?
- Do I have this knowledge — or is it a separate endeavor?
- Are there dependencies on other projects?

**Output:** List of prerequisites with status (available / missing / separate project needed).
If critical prerequisites are missing: early warning — don't discover it at Go/No-Go.

### Step 2: Draw the Landscape Map
> Who are the key people, key works, and key communities?

**Process:**
1. **Find people:** Who is most frequently cited? Who has provable results (not just content)?
2. **Identify works:** What are the 3–5 most recommended books/courses/resources?
3. **Find communities:** Where do practitioners exchange? (forums, Discords, subreddits, meetups)
4. **Timeline:** How old is the field? What is the current state of the art?
5. **Determine knowledge half-life:**

| Type | Half-Life | Source Strategy |
|------|-----------|----------------|
| **Stable** | Years to decades (physics, writing craft, mathematics) | Books, classics, standard works |
| **Medium** | Months to years (markets, industry knowledge, methods) | Books + current articles, communities |
| **Volatile** | Weeks to months (AI frameworks, tools, platforms) | Docs, changelogs, communities, NOT books |

**Source quality criteria:**

| Grade | Source | Trust |
|-------|--------|-------|
| A | Peer-reviewed, proven track records, recognized experts | High |
| B | Experienced practitioners with public results, good books | Medium-High |
| C | Blog posts, YouTube, courses without track record | Verify |
| D | Anonymous tips, "get rich quick", no evidence | Avoid |

**Guru Filter:** In fields without peer review (personal branding, coaching, etc.) additionally check: Does this person have provable results OUTSIDE of creating content about the topic? Someone who only posts "LinkedIn tips on LinkedIn" is Grade C, not B.

**Output:** Curated overview with 3–5 top people, 3–5 top works, 1–2 communities.

### Step 3: Mistake Audit
> What mistakes do beginners typically make — and how do you avoid them?

**Process:**
1. Search specifically for "common mistakes in X", "what I wish I knew before X", "beginner errors X"
2. Search for post-mortems and honest experience reports
3. Ask: What are the most expensive mistakes (time, money, motivation)?

**Output:** Top 5 mistakes, each with: what happens, why, how to avoid.

### Step 4: 80/20 Selection
> What 20% gives you 80% of the understanding?

Based on Ferriss' DiSSS principle:
1. **Deconstruct:** What sub-areas make up the field?
2. **Select:** Which are most important for your concrete goal (Step 1)?
3. **Sequence:** In what order do they make sense?

**Output:** Prioritized list of 3–5 sub-areas with recommended sequence.

### Step 5: Sketch the Learning Path
> Concrete path from "zero" to "capable of action"

**Timeframe:** Emerges from topic complexity, NOT hardcoded.
- Stable, bounded topics: ~4 weeks (book writing, cooking)
- Medium complexity: ~8–12 weeks (algo-trading, new framework)
- High complexity / deep theory: ~6+ months (quantum physics, mathematics)

**Structure (4 phases, duration scales):**
1. **Entry:** Gain overview — which single book/video/resource gives the best big picture?
2. **Foundation:** Work through the 2–3 most important sub-areas from Step 4
3. **First Build:** Define and execute the smallest meaningful project. For meta-skills (positioning, communication): start early, learn from feedback rather than reading everything first
4. **Reflect:** What works, what doesn't? Compare against Mistake Audit (Step 3)

**Output:** Concrete plan with resources and milestones, timeframe matching the topic.

### Step 6: Go/No-Go
> Is it worth it — or not?

**Evaluation:**
- **Effort:** How much time/money do I realistically need?
- **Risk:** What can go wrong? Can I harm anyone?
- **Fit:** Does it fit my goals and situation?
- **Timing:** Is now the right moment?

**Output:** Clear recommendation: Go / Go with constraint / No-Go + reasoning.

## Output Format

After completing all steps, produce a **Reconnaissance Briefing**:

```markdown
# Reconnaissance Briefing: [Topic]

## Scope
[2–3 sentences]

## Prerequisites
[What needs to be in place? Status: available / missing / separate project needed]

## Landscape Map
**Knowledge Half-Life:** [Stable / Medium / Volatile]
**Top People:** [3–5 with quality grade]
**Top Works:** [3–5 with quality grade]
**Communities:** [1–2]
**State of the Art:** [1–2 sentences]

## Mistake Audit
1. [Mistake]: [How to avoid]
2. ...

## 80/20 Focus
[Prioritized sub-areas]

## Learning Path
**Timeframe:** [adapted to topic]
[Concrete plan]

## Go/No-Go
[Recommendation + reasoning, including dependencies]
```

## Rules
- **Quality over quantity:** 3 excellent sources beat 20 mediocre ones
- **Evidence over opinion:** Proven results beat marketing
- **Honesty:** If a field is dubious or too risky — say so
- **Pragmatism:** The goal is capability to act, not completeness

## Methodological Foundations
- Scott Young: Metalearning (Ultralearning Principle 1)
- Tim Ferriss: DiSSS — Deconstruction, Selection, Sequencing, Stakes
- Anders Ericsson: Quality assessment through proven expertise
- Josh Kaufman: Pragmatism — "enough to get started"
