# AI Builder Accelerator Guide

Apply to top AI accelerators in hours, not weeks.

A personal research agent analyzed the top 8 accelerators for AI builders, producing two documents per program: **what they ask** (application questions) and **what makes them special** (quirks, philosophy, tips). These were then combined with a master idea document and fed to [Claude Code](https://claude.ai/claude-code) to generate complete application drafts.

This repo contains the generic, reusable research — no company-specific answers, just the intelligence you need to prepare your own applications efficiently.

## What's Inside

For each accelerator, you get two files:

- **`questions.md`** — Every question and section the application asks, organized as a checklist with notes on what they're looking for
- **`quirks.md`** — What makes the program special: philosophy, culture, deal terms, tips for strong applications, and red flags to avoid

## How to Use This

1. **Pick your target accelerators** from the index below
2. **Read `quirks.md` first** to understand what each program values and whether it's a fit
3. **Read `questions.md`** to see exactly what you need to prepare
4. **Write your master document** — a single doc covering your founders, product, traction, market, and vision
5. **Feed your master doc + the accelerator's `questions.md` + `quirks.md` to Claude Code** (or your preferred AI coding tool) and generate a tailored first draft
6. **Proofread, personalize, and submit** — AI gets you 80% there; your voice and judgment do the last 20%

This workflow turned 8 accelerator applications from a multi-week project into a focused weekend of work.

## Accelerator Index

| Accelerator | Deal | Key Focus | Questions | Quirks |
|-------------|------|-----------|-----------|--------|
| **a16z Speedrun** | $500K + $500K pro-rata for 10% | Traction-first; map to their published theses | [questions](accelerators/a16z-speedrun/questions.md) | [quirks](accelerators/a16z-speedrun/quirks.md) |
| **Afore Capital FIR** | $100K–$500K+ SAFE | Deep personal narratives; "day -1 to conviction" | [questions](accelerators/afore-capital-fir/questions.md) | [quirks](accelerators/afore-capital-fir/quirks.md) |
| **AI2 Incubator** | $600K SAFE + $1M compute for 7% | Most technically rigorous; prove you're not a wrapper | [questions](accelerators/ai2-incubator/questions.md) | [quirks](accelerators/ai2-incubator/quirks.md) |
| **Greylock Edge** | Flexible (SAFE / seed / no capital) | Lead with insight; pass the 80/20 test | [questions](accelerators/greylock-edge/questions.md) | [quirks](accelerators/greylock-edge/quirks.md) |
| **HF0 Residency** | ~$1M uncapped SAFE for ~5% | Repeat founders only; subtractive philosophy | [questions](accelerators/hf0-residency/questions.md) | [quirks](accelerators/hf0-residency/quirks.md) |
| **PearX** | $250K–$2M for ~10% | "Fall in love with the problem"; scrappy founders | [questions](accelerators/pearx/questions.md) | [quirks](accelerators/pearx/quirks.md) |
| **Soma Capital** | $100K uncapped SAFE, 0% equity | Story-driven; most founder-friendly terms | [questions](accelerators/soma-capital/questions.md) | [quirks](accelerators/soma-capital/quirks.md) |
| **SPC Fellowship** | Fellowship / community | Most introspective; "-1 to 0" exploration stage | [questions](accelerators/spc-fellowship/questions.md) | [quirks](accelerators/spc-fellowship/quirks.md) |

## The Workflow That Produced This

```
Personal Research Agent
        |
        v
  [questions.md + quirks.md] x 8 accelerators
        |
        +--- Master idea document (your product, founders, traction)
        |
        v
    Claude Code
        |
        v
  8 tailored application drafts
        |
        v
  Human review + submit
```

## Contributing

Know an accelerator that should be included? Open an issue with:
- Program name and URL
- Deal terms
- What makes it special for AI builders

PRs with new `questions.md` + `quirks.md` pairs are welcome.

## License

This research is shared freely. Use it to apply to accelerators, share it with other founders, build on it.

MIT License.
