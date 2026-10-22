# Gabriel Rojas Chamorro

Software engineer working on backend systems and applied AI. I build Go and Python services on AWS, currently at [ZeroFox](https://www.zerofox.com/).

At ZeroFox I:

- Designed the pipeline behind Loud Voices, an Executive Protection feature that flags accounts repeatedly or threateningly targeting a client's executives, and built its Go LLM worker. In September 2026 it processed about 158k profiles at 99.98% success.
- Moved 18 Executive Protection LLM components onto the company's LiteLLM gateway, with a key per component so spend is attributable by component and model.
- Led Executive Protection's observability project: OpenTelemetry tracing, Prometheus metrics, a Grafana dashboard, and 14 alerts with responder playbooks. The alerts led to 10 tracked fixes.
- Led a nine-month Elasticsearch 5 to 7 migration across 7 repositories, including a Go compatibility proxy that now serves about 4.9B requests a month at 24 ms p99.
- Cut the duplicate rate in analyst alerts from about 25% to under 5% with MySQL and Redis deduplication.

## Open source

- [pingdotgg/t3code#14345](https://github.com/pingdotgg/t3code/pull/14345): fix(server): report spawn ENOTDIR as a spawn error instead of a defect
- [steipete/CodexBar#4453](https://github.com/steipete/CodexBar/pull/4453): Price free Codex Auto-review requests at $0
- [steipete/CodexBar#4290](https://github.com/steipete/CodexBar/pull/4290): Count drifted Codex ledger mirrors once
- [steipete/CodexBar#4279](https://github.com/steipete/CodexBar/pull/4279): Keep priced Codex subtotals when some requests are unpriced
- [steipete/CodexBar#4270](https://github.com/steipete/CodexBar/pull/4270): Keep Codex ledger pricing across 0.72.0 cache upgrades
- [steipete/CodexBar#3565](https://github.com/steipete/CodexBar/pull/3565): fix(spend): preserve calendar days across midnight DST

## Projects

- [skills](https://github.com/gabrielrojasc/skills): reusable agent skills for Claude Code and Codex.
- [sgsi](https://github.com/gabrielrojasc/sgsi): ISO 27001 audit platform from my thesis, deployed at Magnet SPA.
