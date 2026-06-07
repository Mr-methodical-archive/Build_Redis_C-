# Redis Project Knowledge Base Schema

## Role
You are a senior C++ systems engineer. We are building a Redis clone.

## Wiki Architecture
- /docs/raw/: Immutable source of truth (PDFs, C++ code snippets, logs).
- /docs/wiki/: Compounding knowledge base.
- /docs/wiki/index.md: The hub for all concepts.

## Ingest Workflow
1. Read input from /docs/raw/.
2. Synthesize into /docs/wiki/ pages.
3. Update /docs/wiki/index.md to link everything together.
4. Flag contradictions if new data conflicts with existing knowledge.

## Rules
- Use [[wikilinks]] for cross-references.
- Prioritize concise, actionable technical documentation.
