<p align="center">
  <img src="https://em-content.zobj.net/source/apple/391/compass_1f9ed.png" width="80" alt="Learn from the Best">
</p>

<h1 align="center">Learn from the Best</h1>

<p align="center">
  <strong>A structured framework for finding the best sources, people, and learning paths before you start anything new.</strong><br>
  Based on the Mondon Method: "In 99% of cases, someone has already done what you're trying to do. The information exists — you just need to know where to look."
</p>

<p align="center">
  <a href="#the-problem">The Problem</a> ·
  <a href="#the-7-steps">The 7 Steps</a> ·
  <a href="#quick-start">Quick Start</a> ·
  <a href="#examples">Examples</a> ·
  <a href="#faq">FAQ</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-active-brightgreen" alt="Status">
  <img src="https://img.shields.io/badge/steps-7-orange" alt="Steps">
  <img src="https://img.shields.io/badge/license-MIT-lightgrey" alt="License">
</p>

---

## The Problem

You want to learn something new — a skill, a field, a technology. You could spend weeks reading random blog posts, watching YouTube videos, and following advice from self-proclaimed experts. Or you could spend a few hours mapping the landscape first: Who actually knows this? What are the best resources? What mistakes does everyone make?

Most learning frameworks (Ultralearning, DiSSS, First 20 Hours) assume you already know *what* to learn. None of them systematically help you figure out *where to look* and *who to trust* before you start.

That's the gap this framework fills.

## Without / With

| | Without Learn from the Best | With Learn from the Best |
|---|---|---|
| **Sources** | Random Google results, whoever has the best SEO | Curated experts with proven track records |
| **Quality** | No way to assess if a source is trustworthy | A–D rating system with guru filter |
| **Mistakes** | You discover them the hard way | Top 5 beginner mistakes mapped before you start |
| **Learning path** | Vague sense of "I should read something" | Concrete plan with priorities and milestones |
| **Decision** | "I guess I'll just start and see" | Informed Go/No-Go with clear dependencies |

## The 7 Steps

```
┌─────────────────────────────────────────────────┐
│                                                 │
│  1. Scope          → What exactly do I want?    │
│  1b. Prerequisites → What do I need first?      │
│  2. Landscape Map  → Who are the best sources?  │
│  3. Mistake Audit  → What goes wrong for most?  │
│  4. 80/20 Focus    → What 20% matters most?     │
│  5. Learning Path  → How do I get there?        │
│  6. Go/No-Go       → Is it worth it?            │
│                                                 │
│  Output: Reconnaissance Briefing                │
│                                                 │
└─────────────────────────────────────────────────┘
```

### Step 1: Define Scope

> What exactly do I want to know or be able to do — and what explicitly NOT?

Not "learn to write a book" but "preserve my domain expertise as a practitioner in a nonfiction book for the next generation of engineers." The sharper the scope, the better the results.

### Step 1b: Prerequisites Check

> What do I need to know BEFORE I start?

Catch dependencies early. If writing a book requires learning the craft of nonfiction writing first, that's a prerequisite — not a surprise at the end.

### Step 2: Draw the Landscape Map

> Who are the key people, key works, and key communities?

Find the signal in the noise:

| Grade | Source Type | Trust Level |
|-------|-----------|-------------|
| **A** | Peer-reviewed, proven track records, recognized experts | High |
| **B** | Experienced practitioners with public results, good books | Medium-High |
| **C** | Blog posts, YouTube, courses without track record | Verify |
| **D** | Anonymous tips, "get rich quick", no evidence | Avoid |

**Guru Filter:** In fields without peer review (personal branding, coaching), additionally check: Does this person have provable results OUTSIDE of creating content about the topic?

**Knowledge Half-Life:** Not all knowledge ages the same way.

| Type | Half-Life | Source Strategy |
|------|-----------|----------------|
| **Stable** | Years to decades (physics, writing craft) | Books, classics, standard works |
| **Medium** | Months to years (markets, industry knowledge) | Books + current articles, communities |
| **Volatile** | Weeks to months (AI frameworks, tools) | Docs, changelogs, communities — NOT books |

### Step 3: Mistake Audit

> What mistakes do beginners typically make — and how do you avoid them?

Search for "common mistakes in X", "what I wish I knew before X", post-mortems, and honest experience reports. Focus on the most expensive mistakes (time, money, motivation).

### Step 4: 80/20 Selection

> What 20% gives you 80% of the understanding?

Based on Ferriss' DiSSS principle:
1. **Deconstruct** — What sub-areas make up this field?
2. **Select** — Which are most important for your specific goal?
3. **Sequence** — In what order do they make sense?

### Step 5: Sketch the Learning Path

> Concrete path from "zero" to "capable of action"

The timeframe adapts to the topic:
- Stable, bounded topics: ~4 weeks (writing, cooking)
- Medium complexity: ~8–12 weeks (algo-trading, new framework)
- High complexity / deep theory: ~6+ months (quantum physics, mathematics)

Four phases: **Overview → Foundation → First Build → Reflect**

For meta-skills (positioning, communication): start doing early, learn from feedback rather than reading everything first.

### Step 6: Go/No-Go

> Is it worth it — or not?

Evaluate: effort, risk, fit with your goals, timing. The answer can be "Go", "Go with constraints" (dependencies first), or "No-Go" with a clear reason.

## Output Format

Every run produces a **Reconnaissance Briefing**:

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

## When to Use This

**Best for:** Entering a new field, career pivots, ambitious projects, learning something with real stakes.
**Overkill for:** Quick how-tos, single-tool lookups, topics you already know well.

The sweet spot is when the cost of learning from the wrong sources is high — in time, money, or motivation.

## Quick Start

No installation needed. This is a thinking framework, not software.

**Option A — Use it manually:**
1. Pick a topic you want to explore
2. Copy the [briefing template](templates/briefing-template.md) and walk through the 7 steps
3. Fill in each section as you go

**Option B — Use it with an AI assistant:**
1. Copy the [framework prompt](framework/PROMPT.md) into your AI tool
2. Tell it your topic
3. Walk through the steps together — the AI handles research, you make decisions

**Option C — Use it as a Claude Code skill:**
```bash
# Copy the skill into your Claude Code skills directory
cp -r skill/ ~/.claude/skills/learn-from-the-best/
```

## Examples

See the [`examples/`](examples/) directory for complete Reconnaissance Briefings:

- **[Writing a Nonfiction Book](examples/nonfiction-book.md)** — Stable knowledge field, clear Go
- **[Algorithmic Trading](examples/algo-trading.md)** — Medium complexity, Go with dependency on financial market knowledge

## Architecture

```
learn-from-the-best/
├── README.md              ← You are here
├── framework/
│   └── PROMPT.md          ← The full framework as a reusable prompt
├── skill/
│   └── SKILL.md           ← Claude Code skill version
├── templates/
│   └── briefing-template.md ← Blank template to fill in
├── examples/
│   ├── nonfiction-book.md ← Example briefing: writing a book
│   └── algo-trading.md    ← Example briefing: algorithmic trading
└── docs/
    └── index.html         ← Landing page (GitHub Pages)
```

## Usage Modes

| | Manual | AI-Assisted | Claude Code Skill |
|---|---|---|---|
| **What you need** | Pen & paper + search engine | Any AI assistant + the [prompt](framework/PROMPT.md) | Claude Code + [skill](skill/SKILL.md) |
| **Time per run** | 2–4 hours | 30–60 minutes | 30–60 minutes |
| **Research quality** | Your own searches | AI handles research, you decide | AI handles research, you decide |
| **Best for** | Deep personal reflection | Fast, structured exploration | Repeated use, integrated workflow |

## Methodological Foundations

This framework doesn't reinvent the wheel. It synthesizes proven methods and adds what they cover only lightly:

| Method | Author | What we took | What we add on top |
|--------|--------|-------------|-----------------|
| **Ultralearning** | Scott Young | Metalearning (research how to learn before learning) | Systematic source grading (A–D) and guru filter |
| **DiSSS** | Tim Ferriss | 80/20 selection, deconstruction, sequencing | Dedicated landscape mapping and mistake audit phases |
| **Deliberate Practice** | Anders Ericsson | Quality assessment through proven expertise | Structured reconnaissance before execution begins |
| **First 20 Hours** | Josh Kaufman | Pragmatism ("enough to get started") | Systematic process for finding the best starting resources |

**The Mondon Method** — named after a mentor who believed that in 99% of cases, someone has already solved your problem — ties these together with a systematic reconnaissance phase that comes *before* any of these frameworks kick in.

## Roadmap

- [x] Core framework (7 steps)
- [x] Source quality grading (A–D + Guru Filter)
- [x] Knowledge half-life classification
- [x] Prerequisites check (dependency detection)
- [x] Author-tested across 5 topics (nonfiction writing, algo-trading, quantum computing, personal branding, AI agents)
- [ ] More example briefings (quantum computing, personal branding)
- [ ] Community-contributed briefings
- [ ] Template generator (interactive)

## FAQ

**Why not just ask ChatGPT to "research X for me"?**
You can — and this framework works great with AI. The difference: a single prompt gives you a one-shot answer that varies with phrasing. The 7 steps give you a reproducible process with specific tools (guru filter, source grading, knowledge half-life) that catch things a generic prompt misses. The output is a reusable briefing you can reference, update, and share — not a chat message you'll lose.

**Is this just another productivity framework?**
No. Existing frameworks tell you *how* to learn. This one tells you *where to look* and *who to trust* before you start learning. It's the reconnaissance phase that comes before Ultralearning, DiSSS, or any other method.

**Do I need AI to use this?**
No. The 7 steps work with pen and paper, a search engine, and your own judgment. AI assistants speed up the research phase but aren't required.

**How long does a full run take?**
With an AI assistant: 30–60 minutes. Manually: 2–4 hours depending on the topic's complexity. Either way, it's a fraction of the time you'd waste learning from the wrong sources.

**What if my topic is too niche?**
The framework scales. For niche topics, the landscape map will be smaller (fewer experts, fewer works) — but the mistake audit and 80/20 selection become even more valuable because there's less margin for error.

**Why "Mondon Method"?**
Named after Andrew Mondon, a mentor who consistently demonstrated that the fastest path to mastery starts with finding who's already walked it. The principle is simple: don't reinvent — reconnect.

## Contributing

Contributions welcome. Priority areas:

- Example briefings for new topics (use the [output format](#output-format))
- Translations (framework prompt + examples)
- Improvements to the Guru Filter criteria

Please open an issue before submitting large changes.

## License

MIT
