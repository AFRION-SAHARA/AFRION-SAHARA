# AFRION Sahara

**AFRION Sahara** is a pan-African foundation AI designed to feel native to the continent: multilingual, code-switch aware, culturally fluent, and engineered for African realities (mobile-first usage, low/variable bandwidth, and high-stakes information environments).

AFRION stands for **African Intelligence Orchestrated Network**.

## What Sahara is
- **A single Africa-based foundation model** (pan-African in scope).
- Not merely an orchestrator that calls other commercial models behind the scenes.
- Built to be **operational and reliable**, not just conversational.

## Vision & ambition
Sahara aims to produce answers that are **useful, grounded, and honest**:
- Prefer verification (sources/tools/retrieval) over confident guessing.
- Admit uncertainty when evidence is weak.
- Work naturally across African language realities, including code-switching.

### What “built on the foundational knowledge of the 3” means
Sahara learns from the strengths of leading assistants (ChatGPT / Claude / Gemini) **without** merging proprietary weights.

We mean:
- **Distillation** (teacher → student behaviors)
- **Benchmark-driven training** (measure what matters)
- **Africa-first data + evaluation**
- **Not** weight merging

## Mission (locked)
**Build pan-African intelligence that is truthful, culturally fluent, and practical—engineered for real-world African workflows.**

## Non-negotiables (direction locked; wording can evolve)
- **Africa-first competence:** prioritize African languages, code-switching, local entities, and context.
- **Truthfulness under uncertainty:** “verify or abstain” over invention.
- **Operational usefulness:** steps, templates, plans, tools—not just prose.
- **Scales with legitimacy:** governance and contribution rules keep Sahara credible and shippable as a business.

## Funding reality & strategy (locked)
- Current constraint: **no monetary budget** to pay contributors.
- Strategy: **Hype now, ownership later**
  - Start public to recruit contributors and build momentum.
  - Keep crown jewels controlled.
  - Put legal and governance rails in place so AFRION can later commercialize cleanly.

## Open-core boundary (locked mindset)

### Public (intended)
- Benchmark suite + evaluation harness (e.g., **Sahara Bench v0.1**)
- Data tooling: language ID, dedup, cleaning pipelines, dataset documentation (“dataset cards”)
- Tokenization experiments for African languages and code-switching
- Documentation, research notes, model card templates
- Demo apps and prototypes that don’t leak sensitive assets
- Community onboarding and governance docs

### Private / controlled (kept out of the public repo)
- Proprietary datasets (especially non-public or sensitive collections)
- Model weights/checkpoints (official releases remain AFRION-controlled)
- Production infrastructure, deployment configs, secrets/keys
- Security-sensitive or abuse-prone components

**TBD:** whether the repo starts public immediately or after initial scaffolding is staged.
Recommended options:
1) Public immediately with tight contribution rules and no sensitive assets committed.
2) Private for 1–2 weeks to set scaffolding, then open public.
3) Public repo + separate private repo for sensitive work from day one.

## First traction milestone (locked concept): Sahara Bench v0.1
A public benchmark suite focused on:
- African languages
- Code-switching
- Grounded QA (answers tied to evidence)
Includes a simple public leaderboard.

Purpose:
- Credibility
- Clear measurement of progress
- Contributor magnet (“we can see impact”)

## Roadmap (Phase 0 → Phase 3)

### Phase 0 — Project Zero (now)
- Lock identity, contribution model, repo governance.
- Publish recruitment message and initial repo scaffolding.

### Phase 1 — Benchmarks & Community
- Release **Sahara Bench v0.1**
- Build contributor pipelines (issues, review throughput, maintainers)
- Establish credibility through measurable progress

### Phase 2 — Model Work (single-model direction)
- Begin Africa-first data + training plan execution (**details TBD**)
- Use distillation + benchmark-driven iteration

### Phase 3 — Release Discipline
- Define “official Sahara” release process
- Model cards, safety evaluation, versioning
- Transition toward stronger ownership mechanisms as funding arrives

## Contributing
Please read:
- [CONTRIBUTING.md](CONTRIBUTING.md)
- [GOVERNANCE.md](GOVERNANCE.md)
- [CLA.md](CLA.md)
- [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)
- [SECURITY.md](SECURITY.md)

**Important:** Contributions require signing the Contributor License Agreement (CLA).

## Decisions pending (TBD)
- License choice for public code:
  Recommended options:
  1) Apache-2.0 (permissive + patent grant)
  2) MIT (simplest permissive)
  3) AGPL-3.0 (strong copyleft; discourages closed hosted forks)
- Priority language coverage (top languages + code-switch patterns)
- Priority domains for early wins (education/SME/agri/civic/etc.)
- Trademark filing timeline + jurisdictions
- Model naming/versioning scheme (e.g., Sahara-1, Sahara-S, Sahara-Voice)
- Safety/grounding policy spec + evaluation thresholds
<!-- CODEOWNERS test -->
