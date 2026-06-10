<div align="center">

# Jörg Michno

**Software Developer · GenAI & AI Security**

[![GitHub](https://img.shields.io/badge/GitHub-joergmichno-181717?style=flat&logo=github)](https://github.com/joergmichno)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Jörg_Michno-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jörg-michno-6a3899245)
[![Location](https://img.shields.io/badge/Hannover-Germany-blue?style=flat&logo=googlemaps&logoColor=white)](https://github.com/joergmichno)
[![Shield](https://img.shields.io/badge/ClawGuard_Shield-Live_API-brightgreen?style=flat&logo=rocket&logoColor=white)](https://prompttools.co/shield)
[![Blog](https://img.shields.io/badge/Blog-14_Posts-blue?style=flat&logo=rss&logoColor=white)](https://prompttools.co/blog)

</div>

---

I build security tools for AI agents, working at the intersection of **Generative AI** and **Cybersecurity**. Focus: making autonomous AI agents safer — from prompt injection detection to EU AI Act compliance scanning.

**Key numbers:** 225 detection patterns · 15 languages · <6ms latency · deterministic regex engine (zero LLM dependency) · per-pattern OWASP LLM + Agentic Top 10 mapping · 11,529 MCP servers scanned

## Projects

<table>
<tr>
<td width="50%">

### 🛡️ [ClawGuard](https://github.com/joergmichno/clawguard)
**Security Scanner for AI Agents**

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat&logo=python&logoColor=white)](https://github.com/joergmichno/clawguard)
[![PyPI](https://img.shields.io/pypi/v/clawguard?style=flat&logo=pypi&logoColor=white)](https://pypi.org/project/clawguard/)
[![Tests](https://img.shields.io/badge/Benchmark-269_cases-brightgreen?style=flat&logo=pytest&logoColor=white)](https://github.com/joergmichno/clawguard)
[![License](https://img.shields.io/github/license/joergmichno/clawguard?style=flat)](https://github.com/joergmichno/clawguard/blob/main/LICENSE)

Real-time detection of prompt injection, jailbreaks, code injection, social engineering and data exfiltration. **225 patterns across 15 languages.** Zero LLM dependency, <6ms latency.

</td>
<td width="50%">

### 🔒 [ClawGuard Shield](https://github.com/joergmichno/clawguard-shield)
**Security Scanning REST API** · [**Live →**](https://prompttools.co/shield)

[![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=flat&logo=python&logoColor=white)](https://github.com/joergmichno/clawguard-shield)
[![API](https://img.shields.io/badge/API-Live-brightgreen?style=flat&logo=rocket&logoColor=white)](https://prompttools.co/shield)
[![EU AI Act](https://img.shields.io/badge/EU_AI_Act-Ready-blue?style=flat)](https://prompttools.co/audit)

REST API for AI security: 225 patterns, PDF compliance reports mapped to EU AI Act (Art. 9, 15, 17, 61). Free tier, Pro & Enterprise plans. Stripe payments, Docker-deployed.

</td>
</tr>
<tr>
<td width="50%">

### ⚡ [ClawGuard Action](https://github.com/joergmichno/clawguard-action)
**`uses: joergmichno/clawguard-action@v1`**

[![GitHub Action](https://img.shields.io/badge/GitHub_Action-v1-2088FF?style=flat&logo=githubactions&logoColor=white)](https://github.com/joergmichno/clawguard-action)

CI/CD gate: scan prompts and MCP configs on every PR. Configurable severity thresholds, PR annotations, fail-on-critical.

</td>
<td width="50%">

### 🔌 [ClawGuard MCP Server](https://github.com/joergmichno/clawguard-mcp)
**`pip install clawguard-mcp`**

[![PyPI](https://img.shields.io/pypi/v/clawguard-mcp?style=flat&logo=pypi&logoColor=white)](https://pypi.org/project/clawguard-mcp/)
[![MCP](https://img.shields.io/badge/MCP-Compatible-8A2BE2?style=flat)](https://github.com/joergmichno/clawguard-mcp)

MCP server for Claude Desktop, Cursor & Windsurf — security scanning directly in your editor. 5 tools, FastMCP + async.

</td>
</tr>
</table>

### SDKs & Ecosystem

| Repo | Description |
|------|-------------|
| 🐍 [Shield Python SDK](https://github.com/joergmichno/clawguard-shield-python) | `pip install clawguard-shield` — 3 lines to scan any prompt. Dataclass results, type hints, FastAPI & LangChain ready. |
| 📦 [Shield JS SDK](https://github.com/joergmichno/clawguard-shield-js) | `npm install clawguard-shield` — Zero deps, ESM+CJS+TS, full TypeScript support. |
| 🧪 [Prompt Lab](https://github.com/joergmichno/prompt-lab) | Interactive Prompt Injection Playground — test 225 patterns in real time. [Live →](https://prompttools.co) |
| 📊 [Project Manager](https://github.com/joergmichno/project-manager) | Project dashboard with Gantt, Kanban & early warning system — Next.js 16, React 19, Tailwind CSS 4 |

### Security Research

- **Responsible-disclosure security research** across major open-source MCP projects (Google genai-toolbox, Notion MCP, Laravel, n8n, GhidraMCP, git-mcp, XcodeBuildMCP and more), including maintainer-confirmed findings
- **Blog:** [14 articles](https://prompttools.co/blog) on prompt injection, MCP security, EU AI Act compliance
- **Registry Dashboard:** [11,529 MCP servers scanned](https://prompttools.co/registry) for security vulnerabilities

---

<div align="center">

*Building the security layer between AI agents and the real world.*

</div>
