<div align="center">

<img src="logo.svg" width="72" height="72" alt="GateCtr" />


# GateCtr

**One gateway. Every LLM.**

Cut token costs by 40% without changing a line of code.

[![X](https://img.shields.io/badge/Follow-%40gatectrl-000?logo=x&logoColor=white)](https://x.com/gatectrl)
[![Website](https://img.shields.io/badge/gatectr.com-1B4F82?logo=globe&logoColor=white)](https://gatectr.com)
[![License](https://img.shields.io/badge/license-MIT-00B4C8)](LICENSE)

</div>

---

GateCtr is a middleware gateway that sits between your app and any LLM provider — OpenAI, Anthropic, Mistral, Gemini. One endpoint swap. No code changes. Full control.

```bash
npm install @gatectr/sdk
```

```typescript
import { GateCtr } from '@gatectr/sdk';

const client = new GateCtr({ apiKey: 'your-api-key' });

// Drop-in replacement for your existing LLM calls
const response = await client.complete({
  model: 'gpt-4o',
  messages: [{ role: 'user', content: 'Hello' }],
});
```

That's it. GateCtr handles the rest.

---

## What it does

**Budget Firewall** — Hard caps per project. No surprise invoices.

**Context Optimizer** — Compresses prompts automatically. -40% tokens. Same output quality.

**Model Router** — Picks the right LLM for each request. You pay less.

**Analytics Dashboard** — Every token. Every cost. Real-time.

**Webhooks Engine** — Push events to Slack, Teams, or any URL.

**RBAC** — Admin, Manager, Dev, Viewer. Your team, your rules.

---

## Repositories

| Repo | Description |
|---|---|
| [`sdk-node`](https://github.com/GateCtr/sdk-node) | Node.js / TypeScript SDK |
| [`sdk-python`](https://github.com/GateCtr/sdk-python) | Python SDK |
| [`examples`](https://github.com/GateCtr/examples) | Integration examples (Next.js, LangChain, FastAPI) |
| [`docs`](https://github.com/GateCtr/docs) | Public documentation |

---

## Quick start

1. Sign up at [gatectr.com](https://gatectr.com)
2. Get your API key
3. Swap your endpoint URL
4. Done — your first request is already optimized

---

<div align="center">

[Dashboard](https://gatectr.com) · [Docs](https://gatectr.com/docs) · [Status](https://status.gatectr.com) · [X](https://x.com/gatectrl)

</div>
