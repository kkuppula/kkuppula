# Hi, I'm Kiran Kuppula 👋

**AI/ML Engineer** building intelligent developer tools and AI-powered productivity systems.

🎓 **Purdue University** — Post Graduate Program in AI & Machine Learning (2024-2025)  
💼 **14+ years at Blackboard** — Deep EdTech domain expertise (Learn LMS, Ultra UI)

---

## 🚀 What I Build

I specialize in **AI-assisted software development** — tools that help engineers ship faster and safer.

---

### 🤖 PR Reviewer Bot

**Autonomous multi-agent PR reviewer that runs 24/7 and posts structured code reviews.**

```
┌─────────────────────────────────────────────────────────┐
│  PR Reviewer Bot (Polling Loop)                         │
│                                                         │
│  1. Polls GitHub for PRs assigned to you                │
│  2. Fetches diff, filters ignored files                 │
│  3. Delegates to specialist agent team                  │
│  4. Posts structured review with inline comments        │
└─────────────┬───────────────────────────────────────────┘
              │
              ▼
┌─────────────────────────────────────────────────────────┐
│  Review Team (Agno Coordinate Mode)                     │
│                                                         │
│  ┌──────────────┐  ┌──────────────┐                    │
│  │ Architecture │  │   Security   │                    │
│  │   Reviewer   │  │   Reviewer   │                    │
│  └──────────────┘  └──────────────┘                    │
│  ┌──────────────┐  ┌──────────────┐                    │
│  │ Performance  │  │   Testing    │                    │
│  │   Reviewer   │  │   Reviewer   │                    │
│  └──────────────┘  └──────────────┘                    │
│                                                         │
│  → Findings deduplicated & consolidated                 │
│  → Decision: APPROVE / COMMENT / REQUEST_CHANGES        │
└─────────────────────────────────────────────────────────┘
```

**Key Features:**
- 4 specialist agents: Architecture, Security, Performance, Testing
- Severity-based decisions (critical → request changes, nit → approve)
- Inline comments on exact lines with suggestions
- Configurable file ignore patterns, draft PR handling
- SQLite state tracking (no duplicate reviews)

**Stack:** Python • Agno Framework • Claude (GitHub Models) • Pydantic • SQLite

---

### 🔍 Code RAG MCP

**Semantic code search MCP server — find code by meaning, not keywords.**

- Natural language queries → relevant code chunks with file paths and line numbers
- ChromaDB vector store with per-repo isolation
- Find semantically related files (e.g., "what else changes when I touch this file?")
- Plugs into any MCP-compatible editor (OpenCode, Cursor, etc.)

**Stack:** Python • ChromaDB • Sentence Transformers • MCP Protocol

---

### 🔄 Multi-Agent Workflow

**4-agent pipeline with gated approvals for safe AI-assisted code changes.**

```
User Requirement → Discovery → Implementation → Test → Verification → PR Ready
                      │              │             │           │
                   Gate 1         Gate 2        Gate 3      Gate 4
                (approve?)     (approve?)    (approve?)   (approve?)
```

- Discovery Agent: read-only analysis, produces implementation contract
- Implementation Agent: minimal safe code changes following contract
- Test Agent: adds tests following existing conventions
- Verification Agent: final review, produces PR-ready output
- Structured reports at every stage with Teams notifications

**Stack:** Shell • OpenCode • Claude Opus • Markdown Reports

---

### 📊 PR Review Dashboard

**AI-powered pull request triage — zero dependencies, single HTML file.**

- Auto-classifies PR risk (low/medium/high/critical)
- AI-generated summaries of changes
- Voice control for hands-free triage
- Keyboard shortcuts for rapid review workflow
- Works offline after initial load

**Stack:** Vanilla HTML/CSS/JS • Zero dependencies • LocalStorage

---

### 🌊 Log Ocean

**Drop log files, get instant AI-powered insights.**

- Drag-and-drop log file analysis
- Pattern detection (errors, warnings, anomalies)
- Streaming LLM explanations with local model support
- Timeline visualization of incidents

**Stack:** Python • Local LLM • Streaming UI

---

### 📋 ADO Query Skill

**Ask Azure DevOps questions in plain English.**

- "How many bugs were filed this sprint?" → WIQL query → results
- Velocity tracking, regression analysis, team metrics
- Plugs into OpenCode as a skill

**Stack:** Python • Azure DevOps API • WIQL • MCP

---

### 🔧 Jenkins Skill

**Build failure analysis with LLM-powered root cause identification.**

- "Why did the build fail?" → fetches logs → identifies root cause
- DORA metrics tracking
- Failure pattern recognition across builds

**Stack:** Python • Jenkins API • LLM Analysis

---

## 📦 Source Code Access

All repositories are **private**. Interested in the source code?

1. **Connect with me** on [LinkedIn](https://www.linkedin.com/in/kirankuppula/)
2. **Send a message** with which project(s) you'd like access to
3. I'll grant you collaborator access

> 💡 *Happy to share for learning, collaboration, or interview discussions — just reach out!*

---

## 🛠️ Tech Stack

**AI/ML:** LLM APIs (Claude, GPT-4) • RAG Pipelines • Embeddings • Multi-Agent Systems • Prompt Engineering  
**Backend:** Python • Java • Node.js • REST APIs • PostgreSQL  
**Frontend:** React • TypeScript • Angular • Tailwind CSS  
**DevOps:** Docker • Jenkins • GitHub Actions • Azure DevOps

---

## 💡 Philosophy

> *"AI should augment developers, not replace them — better tools, faster feedback, safer deployments."*

I focus on:
- **Semantic understanding** — RAG and embeddings over keyword search
- **Gated workflows** — AI proposes, humans approve
- **Production-ready** — not demos, but tools that work on real 2M+ LOC codebases

---

## 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/kirankuppula/)

---

*Currently exploring opportunities in AI-powered developer tools and EdTech.*
