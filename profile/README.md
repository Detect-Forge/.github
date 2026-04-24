# Detect-Forge 🔨

> **AI-native detection engineering tools for practitioners.**
> Inspectable scoring. CI-native. BYOLLM. Built in the open.

Open-source CLIs and GitHub Actions for ML-native detection engineering.
Built by [James Bower](https://jamesbower.com) — 25 years in security
operations. The edge: applying quant finance and HFT research patterns
to ML cybersec problems, in ways most of the industry hasn't considered.

## The Bet

The overlap between detection engineers and AI/ML cybersecurity
practitioners is an underserved audience. Enterprise platforms solve
the detection lifecycle problem for Fortune 500 SOCs at $150K+ ACV.
Detect-Forge solves it for the detection engineer with a CI pipeline.

## Design Principles

- **Free + OSS + CI-native.** Runs locally, runs in GitHub Actions,
  no data leaves your environment.
- **Explainability is a feature, not a constraint.** Every score
  has a reason. Every layer is inspectable Python. Every AI output
  is human-gated. In security, false confidence is worse than slow.
- **BYOLLM.** Opt-in LLM features use your API key — we never pay
  inference for you, and there's no vendor lock-in on model choice.
- **Quant research as an edge.** HFT and quant finance already
  solved signal decay, embedding drift, and multi-signal scoring —
  years before ML cybersec ran into the same problems. Detect-Forge
  imports those patterns into detection engineering, not the other
  way around.

## Tools

| Tool | Description | Status |
| --- | --- | --- |
| [ttp-staleness](https://github.com/Detect-Forge/ttp-staleness) | AI-native Sigma rule freshness auditor. Three-dimension scoring: timestamp drift (deterministic) + semantic drift (local embeddings) + LLM diff proposals (BYOLLM, opt-in). KQL + EQL in v0.2. | 🔨 Launching May 23, 2026 |
| [detection-backtest](https://github.com/Detect-Forge/detection-backtest) | HFT-style backtesting for Sigma rules against the Atomic Red Team EVTX corpus. Precision, recall, F1 scoring. Catch noisy rules before they fire in production. | 📅 Launching Jun 28, 2026 |

## Roadmap

Current tools are AI-native. Later tools on the roadmap go agentic:

- **shadow-ai-detect** (late 2026) — AI agent governance SDK for
  security teams. OAuth sprawl, prompt injection, privilege
  escalation in multi-agent pipelines.
- **detection-eng-agent** (2027) — open-source agentic SOC
  capabilities focused on triage and backtesting sub-agents.

## Stay Connected

- 📝 **Blog & articles** → [jamesbower.com](https://jamesbower.com)
- 📧 **Newsletter** — get the GitHub link 24 hours before each launch
  → [Subscribe](https://james-bower.kit.com/newsletter?_gl=1*nvfcem*_gcl_au*ODI3MjMwMzUyLjE3NzY2ODk5NDIuMTQ4MzU3NDg4OS4xNzc2Njg5OTQ2LjE3NzY2ODk5NDg.)
- 🎮 **Discord** — Machine Learning in Security
  → [Join](https://discord.gg/YOUR_REAL_INVITE)
- 🌐 **SaaS** (coming Q3 2026) → [detectforge.io](https://detectforge.io)

---

Built by Bower Enterprises LLC · ML cybersec with a quant finance edge
