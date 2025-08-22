# AI Round Table

Multi‑LLM "council of models" discussion app — spin up agents for GPT‑4o, Claude 3.5 Sonnet, Gemini 2.0 Flash, DeepSeek Chat, and Llama 3.3 70B. Compose perspectives, create custom agents, and run round‑table dialogues.

## Features
- Agent builder (name, description, provider, personality, avatar)
- Multi‑provider selection per conversation
- Turn‑based simulated responses (mockable service)
- Tailwind UI with accessible controls
- Ready for real provider wiring (OpenAI, Anthropic, Google, etc.)

## Quick Start

```bash
# 1) Install deps
npm i

# 2) Run dev server
npm run dev

# 3) Build for production
npm run build
npm run preview
```

## Real LLM Wiring (optional)
The demo uses a mock `generateResponseWithProvider`. Replace it with actual API calls per provider. Keep a clean switch by provider ID (e.g., 'gpt-4o', 'claude-3-5-sonnet', etc.).

## Open‑Source License
MIT — see [LICENSE](./LICENSE).

## Contributing
PRs welcome! Please open issues for bugs/ideas. See [SECURITY.md](./SECURITY.md) for vulnerability reporting.
