# Detect-Forge 🔨
 
> **AI-native detection engineering tools for practitioners.**
> Inspectable scoring. CI-native. BYOLLM. Built in the open.
 
Open-source CLIs and GitHub Actions for AI-native detection engineering.
Built by [James Bower](https://jamesbower.com) — 25 years in security
operations. The edge: applying quant and high-frequency research patterns
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
 
Both tools ship in the single [`detect-forge`](https://github.com/Detect-Forge/detect-forge) package:
 
```bash
pip install detect-forge
```
 
| Tool | Description | Status |
| --- | --- | --- |
| [`detect-forge stale`](https://github.com/Detect-Forge/detect-forge) | AI-native Sigma rule freshness auditor. Three-dimensional scoring: timestamp drift (deterministic) + semantic drift (local embeddings) + LLM diff proposals (BYOLLM, opt-in). KQL + EQL in v0.2. | ✅ Shipped May 23, 2026 |
| [`detect-forge backtest`](https://github.com/Detect-Forge/detect-forge) | Quant-based backtesting for rules against the Atomic Red Team EVTX corpus. Precision, recall, F1 scoring. Catch noisy rules before they fire in production. | ✅ Shipped Jun 28, 2026 |
 
## Roadmap
 
Current tools are AI-native. Later tools on the roadmap go agentic:
 
- **shadow-ai-detect** (late 2026) — AI agent governance SDK for
  security teams. OAuth sprawl, prompt injection, privilege
  escalation in multi-agent pipelines.
- **detection-eng-agent** (2027) — open-source agentic SOC
  capabilities focused on triage and backtesting sub-agents.
## Stay Connected
 
- 📝 **Blog & articles** → [jamesbower.com](https://jamesbower.com)
- 📧 **Newsletter** — tool launches, detection engineering deep dives,
  and the occasional quant × cybersec crossover
  → [Subscribe](https://james-bower.kit.com/newsletter)
- 🎮 **Discord** — Machine Learning in Security
  → [Join](https://james-bower.kit.com/mlsecdiscord)
- 🌐 **SaaS** (coming Q3 2026) → [detectforge.io](https://detectforge.io)
---
 
Built by Bower Enterprises LLC · ML cybersec with a quant finance edge
