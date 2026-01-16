# ai-assistant-engineer

Personal Assistant Engineer web app — Phase 1 complete.

## Vision
A personal AI platform that acts as your software engineer, AI engineer, data scientist, cybersecurity auditor, and website builder — a single workspace that helps you build, test, secure, and deploy software faster.

## Key features (MVP)
- Chat assistant with repository context (code, docs, commits).
- In-browser code editor (Monaco) with "apply patch" commit flow.
- Run code/tests in an isolated sandbox.
- Embeddings and RAG for project-aware answers.
- Basic security scanning and secret detection.

## Tech stack (recommended)
- Frontend: Next.js + TypeScript + Tailwind + Monaco Editor
- Backend: Node.js (TypeScript) or Next API routes
- AI orchestration: LangChain (Python or JS), FastAPI for ML service
- Vector DB: Chroma / Pinecone / Weaviate
- Storage: S3-compatible storage
- CI/CD: GitHub Actions
- Secrets: GitHub Secrets / Vault

## Getting started (local dev)
1. Clone the repo
2. Copy `.env.example` to `.env` and configure:
   - GITHUB_OAUTH_CLIENT_ID/SECRET
   - OPENAI_API_KEY (or other provider)
   - VECTOR_DB_URL
   - DATABASE_URL
3. Run services:
   - Option A: `docker compose up --build` (recommended for first run)
   - Option B: run frontend/backend locally and connect to cloud services
4. Visit `http://localhost:3000`

## Roadmap
See `ROADMAP.md` for milestones and prioritized tasks.

## Contributing
- Follow Conventional Commits
- Use pre-commit hooks (eslint, prettier, typecheck)
- Open an issue for large changes and link a design doc

## Contact
Owner: salahuddinwazir558-debug