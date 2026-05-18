# Architecture Diagrams Library

🚧 **Library in progress.** Reusable diagram sources + exports landing soon.

Reusable AI and enterprise architecture diagrams — designed to be forked, adapted, and dropped into your own documentation. All diagrams are inline text-style ASCII inside fenced code blocks: readable on GitHub, version-controlled, diff-able, no rendering tooling required.

**Categories being populated:**
- **Enterprise RAG patterns** — retrieval topologies, embedding stores, hybrid retrieval, re-ranking layers, scoped RAG over multi-tenant data
- **Agentic systems** — single-dispatcher vs team-of-agents, dispatch authorization graphs, audit-trail topologies, sandboxing patterns
- **Deployment topologies** — on-prem vs cloud, co-located dev/prod patterns, secrets isolation, observability layers
- **Orchestration patterns** — MCP integration shapes, scheduled-cron + watchdog patterns, human-in-the-loop approval flows, multi-platform messaging routing

**Diagram conventions:**
- Text-style ASCII inside fenced code blocks (` ```text … ``` `)
- Box-drawing characters (`┌─┐ │ └─┘`) for containers, `+---+` / `|` for compatibility
- Arrows: `→ ↓ ←` for primary flow, ASCII `--->` where Unicode would be ambiguous
- Layered top-to-bottom: persona → experience → application → integration → data
- Connector labels sit on the arrow line, not floating
- 4-class encoding by label prefix: persons / internal containers / data stores / external SaaS

**In the meantime:**
- 🔗 [Portfolio index](https://github.com/jccosta94) — see all projects
- 🔗 [OpenClaw-Hermes Evolution](https://github.com/jccosta94/openclaw-hermes-evolution) — contains the first set of inline ASCII diagrams documenting a real multi-agent system in this style

---

📧 [jccosta94@gmail.com](mailto:jccosta94@gmail.com)
