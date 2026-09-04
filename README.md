# Konstantin Perikov — Chief Technologist · AI Engineering & Search

> **“Intelligence is nothing without accurate retrieval and secure boundaries.”**

I lead the strategy and architecture of retrieval-heavy AI systems under enterprise constraints: quality, security, data sovereignty, cost, and operability.

My foundation is more than a decade of search engineering across Lucene, Solr, Elasticsearch, and OpenSearch. Today I apply that experience to grounded RAG, agent platforms, local inference, AI evaluation, and secure data boundaries.

I think about enterprise AI through three connected constraints: **Scale, Sovereignty, and Security**.

| Constraint | Architecture question |
|---|---|
| **Scale** | Will retrieval quality, latency, cost, and operations hold up beyond a prototype? |
| **Sovereignty** | Where may data and inference run, and what leaves each trust boundary? |
| **Security** | How do identity, tenancy, testing, auditability, and adversarial failure shape the design? |

## What I lead

- **AI platform strategy:** reference architectures, build-vs-buy decisions, provider portability, governance, and technical roadmaps.
- **Production architecture:** retrieval, evaluation, observability, identity boundaries, failure modes, and cost-aware model routing.
- **Engineering organisations:** technical direction, architecture reviews, reusable platform patterns, and mentoring senior and principal engineers.
- **Applied R&D:** production-shaped prototypes that expose trade-offs before an organisation commits to a platform.

My professional work includes centralised RAG and search ecosystems, provider-neutral model gateways spanning managed and local inference, distributed tracing for agent flows, and lexical-to-hybrid search transformations. Employer-specific implementation details and metrics are intentionally generalised here.

The hands-on foundation includes relevance engineering, multi-region search, JVM/GC tuning, Lucene segment behaviour, and operational debugging under load.

## Public architecture evidence

| Project | Question it explores | What is inspectable |
|---|---|---|
| [forgetest](https://github.com/MysterionRise/forgetest) | How should coding-agent regressions be evaluated without trusting the model’s narrative? | Execution-backed grading, bounded traces, a calibrated Rust task corpus, CI, explicit non-claims, and a versioned release |
| [encrypted-information-retrieval](https://github.com/MysterionRise/encrypted-information-retrieval) | What does tenant-scoped encrypted retrieval protect—and what does it still leak? | Threat-oriented design, OIDC/KMS paths, audit records, benchmarks, and an explicit evidence ledger |
| [adaptive-knowledge-graph](https://github.com/MysterionRise/adaptive-knowledge-graph) | When does graph-aware retrieval improve an adaptive-learning loop? | Neo4j + OpenSearch prototype, local-model path, citations, architecture notes, and an evaluation harness |
| [flavours-of-elastic](https://github.com/MysterionRise/flavours-of-elastic) | How do lexical, dense, and hybrid retrieval trade quality for latency and complexity? | Reproducible BM25/dense/RRF examples, evaluation code, CI, and candid benchmark boundaries |
| [ctf-kit](https://github.com/MysterionRise/ctf-kit) | How can an AI assistant support repeatable, authorised CTF work? | Installable CLI/plugin, category-specific workflows, security-tool integrations, tests, and CI |

**Current product bet:** [whystack](https://github.com/MysterionRise/whystack), an evidence-backed workspace for architecture decisions. It is currently a walking skeleton; the next public milestone is a complete decision journey from constraints and evidence to a reviewable recommendation and ADR.

## Search lineage

Search is not a recent addition to my AI profile. [Information Retrieval Adventure](https://github.com/MysterionRise/information-retrieval-adventure) records work across Lucene, Solr, Elasticsearch, custom analysers, scoring, faceting, and automated version verification. That history shapes how I approach RAG: corpus design, relevance, permissions, latency, and observability matter at least as much as the model call.

## Applied research and adversarial practice

I maintain active CTF practice and use small “Danger Zone” experiments as applied-research sandboxes: places to test emerging tools, failure modes, and security assumptions before promoting a pattern into serious architecture. These are experiments, not production claims.

## How I work

1. **Evidence before claims.** Benchmarks need inspectable environments, datasets, methods, and limitations.
2. **Retrieval is a system.** Relevance, grounding, latency, access control, cost, and failure handling belong in the same decision.
3. **Trust boundaries are architecture.** Identity, tenancy, data movement, model providers, and observability are first-class concerns.
4. **Portability is earned through interfaces and tests.** Provider abstraction without behavioural evaluation merely moves lock-in.
5. **Prototypes should expose the production path.** State what is real, what is simulated, and what evidence is still missing.

## Speaking and community

- **Panel host:** Innovation Day 2025, “AI Made Real,” Brussels
- [Python Generators for Search Engines](https://www.youtube.com/watch?v=88WF7MturzM) — Summer Python Meetup
- [Deploying Solr in Multi-Region Environments](https://www.meetup.com/Apache-Lucene-Solr-London-User-Group/events/266888836/) — Apache Lucene/Solr London
- [Effective Molecule Search in Elasticsearch](https://www.youtube.com/watch?v=2OU1j2EY8M0) — Cambridge Cheminformatics & Zed Conference
- [Browser Fingerprinting and Privacy](https://wearecommunity.io/events/fingerprinting-privacy-issues-and-3rd-party-cookies-departure/talks/15685) — Privacy research
- [CTF Competitions](https://www.youtube.com/watch?v=Pbi1Zo8qow0) — Codeberry Club

## Connect

<a href="https://www.linkedin.com/in/konstantin-p-8b0573142/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://stackoverflow.com/users/2663985/mysterion?tab=profile"><img src="https://img.shields.io/badge/Stack_Overflow-FE7A16?style=for-the-badge&logo=stackoverflow&logoColor=white" alt="Stack Overflow" /></a>
