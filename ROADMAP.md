# ROADMAP

This file lists prioritized milestones to build the Personal Assistant Engineer platform.

## Sprint 0 — Foundation (1–2 weeks)
- Repo audit & dependency cleanup
- Choose final stack and deployment target
- Scaffolding: Next.js + API routes + basic auth

## Sprint 1 — Core Workspace (2–3 weeks)
- Monaco editor & file explorer connected to repo (read-only)
- Chat UI with LLM calls (OpenAI / provider)
- GitHub OAuth and repo read access

## Sprint 2 — RAG & Context (2–3 weeks)
- Document + code embedding pipeline
- Vector DB integration
- Project-aware answers using RAG

## Sprint 3 — Code Edit & Runner (2–3 weeks)
- "Apply patch" flow and Git commit API integration
- Sandboxed code runner (Docker) to execute snippets and tests
- Unit test runner integration

## Sprint 4 — Security & CI (2–3 weeks)
- Dependency scanning and secret scanning on push
- CI pipelines for tests + linting
- Basic RBAC and audit logging

## Phase 2 — Assistants & Automation (4–6 weeks)
- Named assistants (Code, Data, Security, Web)
- Workflow/pipeline builder & scheduled tasks
- Plugin system for integrations (DB, cloud, analytics)

## Phase 3 — Team & Scale (ongoing)
- Multi-user collaboration, roles, and shared projects
- Self-hosted model support and fine-tuning UIs
- Marketplace for plugins and templates

---

Add issues for the items above and estimate individually when ready.