# Virginia Growth Marketing

An open-source Agent Skill for turning attention into distribution, community, demand, and revenue.

This skill extracts transferable marketing mechanisms from publicly documented creator-led commerce patterns associated with Virginia Fonseca and generalizes them for **any product, service, SaaS, B2B company, local business, creator business, or professional service**.

> This project is independent and unaffiliated with Virginia Fonseca, WePink, or any related company. It does not imitate a person's voice, likeness, or identity. It studies public marketing patterns and turns them into reusable frameworks.

## What this skill does

Instead of answering only **“what should we post?”**, the skill works backwards from the commercial system:

**attention → trust → desire → proof → action → experience → community → redistribution**

It helps with:

- launches and pre-launches;
- founder-led marketing;
- zero-audience and tiny-audience growth;
- product demonstrations;
- creator and borrowed-audience strategies;
- community and UGC loops;
- live-commerce patterns adapted to SaaS/B2B/services;
- offer design and conversion;
- retention and post-purchase experience;
- demand-vs-capacity checks before scaling.

## The core loop

```text
ROUTINE
  ↓
CURIOSITY
  ↓
PROOF
  ↓
EVENT
  ↓
OFFER
  ↓
PURCHASE
  ↓
EXPERIENCE
  ↓
COMMUNITY
  ↓
CONTENT
  ↓
NEW AUDIENCE
```

The point is not to copy tactics literally. A beauty live can become a SaaS live demo. A fan challenge can become a B2B champion program. A product teaser can become a feature preview.

**Transfer the mechanism, not the costume.**

## Repository structure

```text
.
├── SKILL.md
├── README.md
├── LICENSE
├── agents/
│   └── openai.yaml
└── references/
    ├── core-framework.md
    ├── founder-distribution.md
    ├── launch-engine.md
    ├── community-engine.md
    ├── conversion-engine.md
    ├── product-adaptation.md
    ├── playbooks.md
    ├── guardrails.md
    └── research-basis.md
```

`SKILL.md` is intentionally compact. Detailed guidance lives under `references/` and is loaded only when useful.

## Install

### Codex

Install the repository as an Agent Skill using the Codex skill installer, or clone/copy it into your Codex skills directory:

```bash
git clone https://github.com/GusViieira/virginia-growth-marketing.git
cp -R virginia-growth-marketing ~/.codex/skills/virginia-growth-marketing
```

Restart/reload the agent environment if needed.

### Other Agent-Skills-compatible agents

Copy the repository folder into the agent's skills directory. The portable entry point is `SKILL.md`; `agents/openai.yaml` is optional OpenAI/Codex interface metadata.

## Example prompts

```text
Use Virginia Growth Marketing to launch this product with almost no audience.
```

```text
I have traffic but weak sales. Diagnose the bottleneck using this skill.
```

```text
Create a 14-day launch sequence for my SaaS using the Launch Engine.
```

```text
I have 30 followers and no customers. Build the first-100 distribution plan.
```

```text
Turn our existing customers into a community-driven distribution loop.
```

## Principles

The skill is intentionally biased toward:

- showing the product instead of hiding it behind generic content;
- active distribution instead of waiting for an algorithm;
- buyer language instead of internal jargon;
- real proof instead of fabricated social proof;
- events and concentrated attention when appropriate;
- community participation instead of passive follower counts;
- commercial metrics instead of vanity metrics;
- product experience and retention instead of acquisition at any cost;
- operational capacity before demand spikes.

## Research

The framework is grounded in public reporting, interviews, academic work, and public consumer-protection records. See [`references/research-basis.md`](references/research-basis.md).

The research also includes the **negative lessons** of hypergrowth. Large demand without sufficient fulfillment, support, infrastructure, or post-sale quality can destroy trust. This is why the skill includes a mandatory Demand vs Capacity Gate.

## License

MIT. See [`LICENSE`](LICENSE).

## Contributing

Issues and pull requests are welcome. Useful contributions include:

- new market adaptations;
- better playbooks;
- additional high-quality research;
- tested examples;
- clearer decision frameworks.

Please do not add fabricated case studies, fake metrics, or manipulative dark patterns.
