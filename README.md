# Chengyun

**Applied AI · RAG · Agent Workflows · LLM Products**

I build knowledge assistants and AI workbenches that connect retrieval, evidence, and human review to practical workflows. My focus is on making answers traceable, long-running tasks recoverable, and generated content reviewable before it is used.

[Writing & experiments](https://modelwithin.cloud) · [Public projects](https://github.com/Ev1ldore?tab=repositories)

## Selected work

### [Customer Profile](https://github.com/Ev1ldore/customer-profile)

A local B2B customer workbench for PDF, DOCX, Markdown, and text materials. Structured reports connect fields to source evidence, preserve human edits across regeneration, and support reviewable web-verification workflows and JSON / Markdown export.

**Stack:** Python · SQLite · JSON Schema · Vanilla JavaScript

### [Amazon After-Sales Agent](https://github.com/Ev1ldore/amazon-after-sales-agent)

An internal after-sales workbench for Amazon seller teams: case management, order checks, policy retrieval, reply drafts, and human review. An eight-node LangGraph workflow connects analysis to versioned knowledge releases, local execution traces, and offline evaluation.

**Stack:** Python · FastAPI · Vue 3 · TypeScript · LangGraph · MySQL · Milvus

The Amazon read-only adapter is implemented and tested with fixtures and simulated responses; live seller integration remains unverified. Replies require human approval, and the application does not send Amazon messages or issue refunds automatically.

### [Content Studio](https://github.com/Ev1ldore/content-studio)

A Chinese content workbench that takes source materials through topic selection, article editing, visual production, and downloadable Xiaohongshu / WeChat content packages. Human review is tied to specific versions; persistent checkpoints support workflow recovery, and individual visual pages can be regenerated.

**Stack:** React · FastAPI · LangGraph · PostgreSQL · Chromium

Includes a local Mock demo and documented validation paths. Content is exported for manual publishing; generation and rendering behavior depend on the selected runtime mode.

### [Domain Knowledge Assistant](https://github.com/Ev1ldore/domain-knowledge-assistant)

A document-grounded Q&A application combining dense retrieval, BM25, RRF fusion, and optional CrossEncoder reranking. Claim-level evidence checks, source snapshots, conflict handling, and administrator review make the path from retrieved text to an answer inspectable.

**Stack:** Python · FastAPI · SQLite · NumPy · BM25 · CrossEncoder

Designed for small knowledge bases in a single-process deployment. Evidence checks reduce unsupported output, but model-based review still requires evaluation for each domain.

### [Model Within AI Reader](https://github.com/Ev1ldore/model-within-ai-reader)

An AI reading assistant for the [Model Within](https://modelwithin.cloud) knowledge site. It supports article summaries, selection-based Q&A, and site-wide retrieval. The public repository is a documentation-first case study; the production implementation remains private.

### [LLM Video Script Generator](https://github.com/Ev1ldore/llm-video-script-generator)

A Streamlit application that turns a topic, target duration, and creativity setting into a structured Chinese video script. It supports multiple OpenAI-compatible model providers and augments generation with Chinese Wikipedia retrieval.

## Engineering focus

- **Evidence-grounded RAG:** document processing, hybrid retrieval, reranking, citations, and conflict handling.
- **Stateful agent workflows:** orchestration, checkpoints, human interrupts, version checks, and failure recovery.
- **Practical AI products:** full-stack workbenches, model gateways, background jobs, and reviewable deliverables.
- **Evaluation and observability:** offline evaluation, execution traces, reproducible demos, and explicit integration boundaries.

## Working principles

I prefer systems that are measurable, debuggable, and honest about their boundaries. A useful AI application should make it clear where an answer came from, what happens when a step fails, and which decisions still belong to a person.

Public repositories document their implementation and validation scope. Demo behavior, simulated integrations, and live-service verification are kept distinct.
