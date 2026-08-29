# Anthropic Claude Certification Practice Hub 🚀

An interactive, responsive, scenario-based practice test and study engine for all Anthropic Claude certification tracks. Built with pure HTML, Tailwind CSS, Alpine.js, and client-side storage, hosted on **GitHub Pages**.

🔗 **Live Practice Application:** [https://jason-smithy.github.io/anthropic-exam-practice/](https://jason-smithy.github.io/anthropic-exam-practice/)

---

## 🎯 5 Certification Tracks Covered

1. **Claude Certified Prompt Engineer**
   * Semantic XML formatting & Delimiter isolation
   * Few-Shot demonstration templates (`<examples>`)
   * Assistant message prefilling & JSON-only generation
   * Chain of Thought (CoT) inside `<thinking>` tags
2. **Claude Certified Application Developer**
   * Messages API (`/v1/messages`) structure & System Prompt placement
   * Server-Sent Events (SSE) streaming & Token delta tracking
   * Exponential backoff, jitter, and HTTP 429 rate limit management
3. **Claude Agent & Tool Use Specialist (MCP)**
   * Model Context Protocol (MCP) primitives: Resources, Prompts, Tools
   * Tool schema definition via JSON Schema
   * Multi-turn agent loops & `tool_result` response blocks
   * Local stdio JSON-RPC transport protocol
4. **Claude AI Solutions Architect (Enterprise & Optimization)**
   * Anthropic Prompt Caching (`cache_control: {"type": "ephemeral"}`)
   * Message Batches API (50% async discount)
   * Multimodal vision and document token balancing
5. **Claude Safety, Governance & Red Teaming Specialist**
   * Constitutional AI (CAI) and RLAIF principles
   * Indirect prompt injection mitigation & privilege separation
   * Automated red teaming methodologies & refusal evaluations

---

## ⚡ Key Features

* **Landing Experience:** Direct **"Start practicing — no account needed"** gateway + certification track chooser.
* **Study Mode:** Real-time feedback, deep conceptual rationale, and distractor analysis explaining why incorrect choices fail.
* **Exam Mode:** Timed test simulation (90s per question), countdown clock, and final scoring report (75% passing threshold).
* **Track & Domain Filters:** Filter questions across all 5 certification tracks or practice them collectively.
* **Question Map Navigator:** Jump directly to any question, view answered status, and track real-time accuracy.
* **Bookmarking System:** Flag challenging questions to review later.
* **No Server or Database Required:** Stores progress in browser `localStorage`.
