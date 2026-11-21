<div align="center">

# Hi, I'm Truscotta 👋

**AI Infrastructure & TypeScript Engineer**  
Building open-source runtime governance, security, and cost-control tooling for **MCP & AI Agents**.

[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-truscotta-EA4AAA?style=for-the-badge&logo=githubsponsors&logoColor=white)](https://github.com/sponsors/truscotta)
[![TypeScript](https://img.shields.io/badge/TypeScript-100%25_Strict-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![GitHub followers](https://img.shields.io/github/followers/truscotta?style=for-the-badge&logo=github&color=181717)](https://github.com/truscotta?tab=followers)

</div>

---

### 🛡️ The Sentinel Open-Source Ecosystem

Deploying AI Agents to production breaks when tool calls loop infinitely, token budgets spike silently, or sensitive data leaks across MCP servers. I build lightweight, zero-bloat TypeScript infrastructure to make agentic systems observable, safe, and predictable.

```mermaid
flowchart LR
    A[AI Agent / LLM Client] --> B[mcp-sentinel<br/>Budget • PII Guard • Circuit Breaker]
    B --> C[MCP Servers & Tools]
    D[mcp-doctor CLI<br/>Pre-flight Security Audit] -.-> C
    B -->|Structured Audit Logs| E[sentinel-studio<br/>Self-Hosted Dashboard]
