### Barry Pilgrim

**Senior Software Engineer & Technical Lead. 25+ years building enterprise .NET systems, now building AI-native software.**

I spent nearly three decades building and leading mission-critical systems in legal, financial, and B2B data platforms. I have been independent since November 2024, and I used that time to go deep on AI in real engineering. Not demos. Production architecture.

The projects below are that work. I built them the way I build for a client, under real constraints.

---

#### 🔧 What I'm building

**[alpha-loop](https://github.com/bpilgrim/alpha-loop)** · AI-assisted algorithmic trading system

A deterministic live-execution engine (rules, risk limits, hard kill switch) stays separate from an AI-driven research loop, where Claude analyzes logged trade history and proposes strategy changes as structured hypotheses. Nothing reaches production until it has been backtested and beats the incumbent.
`Python · hexagonal architecture · PostgreSQL/TimescaleDB · Solana DEX · Claude`

**[ai-assistant](https://github.com/bpilgrim/ai-assistant)** · Personal AI assistant

A personal assistant exposed as a Telegram bot and an MCP server, with calendar and email integrations and append-only audit logging. Built on ports and adapters, so every integration is swappable.
`Python · ports & adapters · Model Context Protocol · Anthropic Claude`

**[obsidian-claude-workspace](https://github.com/bpilgrim/obsidian-claude-workspace)** · File-based agent harness

The substrate the assistant operates on. No database, no framework, no agent runtime. Folder structure and markdown context files route the work. An agent drops into a folder, reads that folder's instructions, does its job, and exits, never loading more than the task needs.
`Markdown · Obsidian · Claude Code`

**[jam-player](https://github.com/bpilgrim/jam-player)** · Desktop media player *(product, in development)*

A Winamp-inspired player for large local media libraries, built around a custom queue-based playback engine, hardware-accelerated rendering, and tag-based asset management. Working toward commercial release.
`C# · .NET 9 · WPF · Prism · EF Core · libmpv`

---

#### 🧭 Focus

Integrating AI into traditional software engineering. Agentic tooling, AI-assisted development workflows, and data-driven applications, built with the architecture and delivery discipline of 25 years in enterprise systems.

#### 🛠 Core stack

`C#/.NET` · `Python` · `TypeScript/JavaScript` · `SQL Server` · `PostgreSQL` · `WPF · Blazor · ASP.NET` · `Anthropic Claude · OpenAI Codex · GitHub Copilot`

---

📍 Scotch Plains, NJ  ·  📧 barry.pilgrim@gmail.com
