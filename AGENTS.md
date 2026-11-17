
# EduMind AI — Project Instructions

## Project Vision
EduMind AI is an intelligent learning platform that helps students
understand course materials, prepare for examinations and improve
their academic performance.

## Development Philosophy
- Reuse reliable open-source software and existing libraries.
- Avoid reinventing established functionality.
- Build genuine, working features rather than UI-only prototypes.
- Prefer simple, maintainable architecture.
- Explain significant architectural decisions.
- Never introduce unnecessary dependencies.

## Architecture

Frontend:
- Next.js
- TypeScript
- Tailwind CSS
- shadcn/ui

Backend:
- Python
- FastAPI
- Pydantic
- SQLAlchemy 2
- Alembic

Database:
- PostgreSQL
- pgvector

AI:
- Gemini API free tier, subject to available quotas
- Retrieval-Augmented Generation (RAG)
- Sentence Transformers or another suitable embedding provider
- LangGraph when agent orchestration is justified

Document processing:
- Docling
- Other proven open-source parsers when appropriate

Cloud:
- Vercel for frontend
- Cloud backend hosting
- Hosted PostgreSQL
- Cloud object storage

## Non-negotiable Requirements

1. No Supabase.
2. Production database must run in the cloud.
3. Production backend and frontend must run in the cloud.
4. Uploaded documents must use cloud storage.
5. No GPU requirement on the developer machine.
6. Target zero-cost services and free tiers.
7. Never hardcode API keys or credentials.
8. Never commit .env files or secrets.
9. Use database migrations for schema changes.
10. Test functionality before marking tasks complete.

## AI Coding Agent Rules

- Inspect the existing codebase before modifying it.
- Research official documentation before choosing unfamiliar libraries.
- Search for suitable open-source solutions before implementing
  complex functionality from scratch.
- Check repository licenses and maintenance status.
- Never overwrite existing work without understanding it.
- Ask before introducing major architectural changes.
- Explain commands that modify the environment.
- Do not claim features work without testing them.

## Development Workflow

1. Understand the requirement.
2. Research existing solutions.
3. Propose an implementation.
4. Implement incrementally.
5. Run tests and inspect results.
6. Explain changes.
7. Commit working changes to Git.

## Current Status

Project initialized.
Development environment setup in progress.
No application features implemented yet.
