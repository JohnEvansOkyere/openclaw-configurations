# MEMORY.md - John's Agent Memory

## How Memory Works Here
OpenClaw uses the memory-core plugin with nomic-embed-text embeddings via Ollama.
Sessions are indexed automatically in the background and searched semantically
when relevant context is needed.

## Memory Backend
- **Plugin:** memory-core (enabled)
- **Embedding model:** nomic-embed-text (via Ollama at http://127.0.0.1:11434)
- **Session store:** ~/.openclaw/agents/main/sessions/sessions.json
- **Type:** SQLite-backed semantic search

## What Gets Remembered Automatically
- Every conversation session with John
- Ideas John drops via Telegram
- Content plans created weekly
- Scripts written for videos
- Analytics data logged weekly

## Persistent Context Files (Always in Memory)
These workspace files are injected into every session automatically:
- SOUL.md — voice, tone, personality
- USER.md — who John is, his stack, his goals
- AGENTS.md — the full content pipeline workflow
- TOOLS.md — environment, file paths, integrations
- IDENTITY.md — agent identity

## Content Pipeline Memory
The agent remembers across sessions:
- What ideas have already been processed
- What videos have been planned and scripted
- What content has been published
- What performed well in analytics

## Important Notes
- Do NOT duplicate ideas already in ideas/combined-ideas.md
- Do NOT rewrite scripts already in content/scripts/current-scripts.md
- Always check the log files before adding new entries
- Reference past analytics when making content recommendations
