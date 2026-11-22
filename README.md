<div align="center">

# Chengyun

**Applied AI · RAG · Agent Workflows**

Bringing models into workflows—and making each step inspectable.  
Building AI applications around knowledge, process, and human judgment.

[![Blog — Model Within](https://img.shields.io/badge/Blog-Model%20Within-2563EB?style=for-the-badge&logo=wordpress&logoColor=white)](https://modelwithin.cloud)
[![GitHub — Ev1ldore](https://img.shields.io/badge/GitHub-Ev1ldore-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ev1ldore?tab=repositories)

</div>

## Projects

### 01
**[Domain Knowledge Assistant ↗](https://github.com/Ev1ldore/domain-knowledge-assistant)**

Go from “What is the answer?” to “What supports it?” A document-grounded Q&A application combining hybrid retrieval, optional reranking, and claim-level evidence links, with explicit handling of missing information, conflicting sources, and human review.

`Python` `FastAPI` `SQLite` `Hybrid Retrieval`

### 02
**[Amazon After-Sales Agent ↗](https://github.com/Ev1ldore/amazon-after-sales-agent)**

Give support teams order facts and policy evidence alongside their cases. A LangGraph workflow connects checks, retrieval, recommendations, and reply drafts, with version management, execution traces, and human approval for traceable collaboration.

`Python` `LangGraph` `FastAPI` `Vue 3`

### 03
**[Content Studio ↗](https://github.com/Ev1ldore/content-studio)**

Take source material to a reviewable content package. Topic selection, article editing, visual production, and export share a workflow with version-bound approvals, checkpoint recovery, and individual visual-page revisions.

`React` `FastAPI` `LangGraph` `PostgreSQL`

### 04
**[Customer Profile ↗](https://github.com/Ev1ldore/customer-profile)**

Turn documents and conversation notes into structured, reviewable customer reports. Connect fields to original evidence, preserve disagreements and human edits, and support web-verification and export workflows.

`Python` `SQLite` `JSON Schema` `JavaScript`

<details>
<summary>Project status and validation boundaries</summary>

- **Domain Knowledge Assistant:** Designed for small knowledge bases and single-process deployment. Scale and concurrency remain unverified; model-based review requires domain-specific evaluation.
- **Amazon After-Sales Agent:** Order integration is validated with fixtures and simulated responses. Live seller integration and real MySQL/Milvus paths require separate validation. No automatic message sending or refunds.
- **Content Studio:** Includes a local Mock demo. Mock / text-API modes use fixed sample images; separate-process mode uses template rendering. Users publish exported content manually.
- **Customer Profile:** Intended for local use. Demo materials are synthetic; evidence support is calculated using rules.

See each repository for implementation details and validation records.

</details>

## Engineering focus

**Evidence & provenance** / **State & recovery** / **Human review** / **Evaluation & observability**

I focus on what happens after a model produces an answer: how evidence is retained, how state moves forward, how failures are handled, and who makes the final call.

---

[**Model Within ↗**](https://modelwithin.cloud) · Technical writing and experiments
