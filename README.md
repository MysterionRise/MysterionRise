# Konstantin Perikov

Chief Technologist, AI Engineering & Search.

I spent over ten years building and tuning search on Lucene, Solr, Elasticsearch and OpenSearch:
relevance, multi-region clusters, JVM/GC tuning, Lucene segment behaviour, debugging under load.
These days I design retrieval-heavy AI systems for enterprises, where security, data residency
and cost matter as much as answer quality.

At work that means centralised RAG and search platforms, model gateways that span managed and local
inference, tracing for agent flows, and moving search from lexical to hybrid. Most of it can't be
published, so the repos below are where I work through the same problems in the open.

## Projects

| Project | What it is |
|---|---|
| [adaptive-knowledge-graph](https://github.com/MysterionRise/adaptive-knowledge-graph) | Local-first tutor for open textbooks: Neo4j knowledge graph, hybrid BM25 + vector retrieval in OpenSearch, a local LLM via Ollama, cited answers and adaptive quizzes |
| [forgetest](https://github.com/MysterionRise/forgetest) | Regression harness for coding agents on a Rust task corpus. It grades by running the code, not by reading the agent's account of what it did |
| [agentic-search-audit](https://github.com/MysterionRise/agentic-search-audit) | Audits e-commerce site search with Playwright and an LLM judge |
| [encrypted-information-retrieval](https://github.com/MysterionRise/encrypted-information-retrieval) | Tenant-scoped encrypted retrieval prototype (OIDC, KMS, audit log), with notes on what it protects and what still leaks |
| [flavours-of-elastic](https://github.com/MysterionRise/flavours-of-elastic) | Docker Compose setups for Elasticsearch and OpenSearch, with BM25, dense and hybrid (RRF) examples and evaluation code |
| [ctf-kit](https://github.com/MysterionRise/ctf-kit) | AI-assisted CTF toolkit: a CLI plus plugins for Claude Code, Cursor and Copilot that wire in the usual tools per challenge category |

Now building [whystack](https://github.com/MysterionRise/whystack), a workspace that takes an architecture
decision from constraints and evidence to a reviewable ADR. It is early.

Older search work is in [information-retrieval-adventure](https://github.com/MysterionRise/information-retrieval-adventure).
I play CTFs regularly and follow AI red-teaming closely; the `*-dangerzone` repos are where I try tools out.

## Talks

- Innovation Day 2025, "AI Made Real", Brussels (panel host)
- [Python Generators for Search Engines](https://www.youtube.com/watch?v=88WF7MturzM), Summer Python Meetup
- [Deploying Solr in Multi-Region Environments](https://www.meetup.com/Apache-Lucene-Solr-London-User-Group/events/266888836/), Apache Lucene/Solr London
- [Effective Molecule Search in Elasticsearch](https://www.youtube.com/watch?v=2OU1j2EY8M0), Cambridge Cheminformatics / Zed Conference
- [Browser Fingerprinting and Privacy](https://wearecommunity.io/events/fingerprinting-privacy-issues-and-3rd-party-cookies-departure/talks/15685)
- [CTF Competitions](https://www.youtube.com/watch?v=Pbi1Zo8qow0), Codeberry Club

## Contact

<a href="https://www.linkedin.com/in/konstantin-p-8b0573142/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://stackoverflow.com/users/2663985/mysterion?tab=profile"><img src="https://img.shields.io/badge/Stack_Overflow-FE7A16?style=for-the-badge&logo=stackoverflow&logoColor=white" alt="Stack Overflow" /></a>
