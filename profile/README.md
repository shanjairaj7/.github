# Commune — Email & SMS for AI Agents

Give your AI agent a real inbox and phone number. Send email, receive webhooks, manage threads — all designed for agents, not humans.

```python
from commune import CommuneClient

commune = CommuneClient(api_key="comm_...")
commune.messages.send(
    to="user@example.com",
    subject="Hello from your agent",
    text="I've finished processing your request.",
    inbox_id="support@yourdomain.com"
)
```

```bash
pip install commune-mail   # Python
npm install commune-ai    # TypeScript / Node.js
uvx commune-mcp           # Claude Desktop, Cursor, Windsurf (MCP)
```

---

## What You Can Build

- **Support agents** — receive, read, and reply to email in real time via webhooks
- **Hiring agents** — text workers about shifts, handle YES/NO replies, notify managers
- **Personal agents** — daily summaries texted to you, responds to your messages
- **Marketing agents** — AI-personalized broadcast campaigns, suppression-aware, STOP/START compliant
- **Multi-agent pipelines** — agents communicate through real email threads with RFC 5322 continuity

---

## Repositories

| Repo | What it is |
|------|-----------|
| [email-for-agents](https://github.com/shanjairaj7/email-for-agents) | 40+ runnable examples — LangChain, CrewAI, Claude, OpenAI, MCP, SMS |
| [commune-mcp](https://github.com/shanjairaj7/commune-mcp) | MCP server for Claude Desktop, Cursor, Windsurf — `uvx commune-mcp` |
| [commune-ai](https://github.com/shanjairaj7/commune-ai) | TypeScript/Node.js SDK |
| [commune-python](https://github.com/shanjairaj7/commune-python) | Python SDK (`commune-mail`) |
| [commune](https://github.com/shanjairaj7/commune) | Open-source backend infrastructure |
| [agent-stack](https://github.com/shanjairaj7/agent-stack) | Production tool registry — 50+ tools purpose-built for AI agents |

---

## Links

[commune.email](https://commune.email) · [Docs](https://commune.email/docs) · [Discord](https://commune.email/discord) · [email-for-agents cookbook](https://github.com/shanjairaj7/email-for-agents)
