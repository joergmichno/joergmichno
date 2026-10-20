<div align="center">

# Jörg Michno

**Security Researcher & Builder · AI-Agent Security**

[![GitHub](https://img.shields.io/badge/GitHub-joergmichno-181717?style=flat&logo=github)](https://github.com/joergmichno)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Jörg_Michno-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jörg-michno-6a3899245)
[![Location](https://img.shields.io/badge/Hannover-Germany-blue?style=flat&logo=googlemaps&logoColor=white)](https://github.com/joergmichno)
[![ModVet](https://img.shields.io/pypi/v/modvet?style=flat&logo=pypi&logoColor=white&label=modvet)](https://pypi.org/project/modvet/)
[![Blog](https://img.shields.io/badge/Blog-16_Posts-blue?style=flat&logo=rss&logoColor=white)](https://prompttools.co/blog)

</div>

---

Active **Microsoft Security Response Center (MSRC) researcher — Q2 2026 Leaderboard**. I find and report real vulnerabilities; when Microsoft says "MSRC Listens", it's not marketing.

**Currently building [ModVet](https://github.com/joergmichno/modvet)** — a deterministic pre-install scanner for Claude Code mods. *The update is the attack*: mods run unsandboxed with your permissions, and a clean mod can turn malicious on its next auto-update. ModVet vets mods before you install them — offline, no LLM, 0 €.

```bash
pip install modvet
```

**Key numbers:** ~400 deterministic detection patterns · capability-combination logic (env-read + POST = exfiltration) · OWASP MCP Top 10 mapping · JSON/SARIF/badge output · update-delta auditing (`snapshot`/`diff`)

## Projects

<table>
<tr>
<td width="50%">

### 🛡️ [ModVet](https://github.com/joergmichno/modvet)
**Pre-install security scanner for Claude Code mods**

[![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=flat&logo=python&logoColor=white)](https://pypi.org/project/modvet/)
[![PyPI](https://img.shields.io/pypi/v/modvet?style=flat&logo=pypi&logoColor=white)](https://pypi.org/project/modvet/)
[![License](https://img.shields.io/github/license/joergmichno/modvet?style=flat)](https://github.com/joergmichno/modvet/blob/main/LICENSE)

Detects prompt injection, dangerous capability combinations, hardcoded secrets and update trojans in Claude Code mods. Zero dependencies, deterministic, CI-ready exit codes.

</td>
<td width="50%">

### 🔒 [ClawGuard Shield](https://github.com/joergmichno/clawguard-shield)
**Security Scanning REST API** · [**Live →**](https://prompttools.co/shield)

[![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=flat&logo=python&logoColor=white)](https://github.com/joergmichno/clawguard-shield)
[![API](https://img.shields.io/badge/API-Live-brightgreen?style=flat&logo=rocket&logoColor=white)](https://prompttools.co/shield)

REST API for AI security scanning: prompt injection, jailbreaks, data exfiltration. EU AI Act audit reports, Free tier, Pro & Enterprise plans, Docker-deployed.

</td>
</tr>
<tr>
<td width="50%">

### ⚡ [ClawGuard Action](https://github.com/joergmichno/clawguard-action)
**`uses: joergmichno/clawguard-action@v1`**

CI/CD gate: scan prompts and MCP configs on every PR. Configurable severity thresholds, PR annotations, fail-on-critical.

</td>
<td width="50%">

### 🔌 [ClawGuard MCP Server](https://github.com/joergmichno/clawguard-mcp)
**`pip install clawguard-mcp`**

MCP server for Claude Desktop, Cursor & Windsurf — security scanning directly in your editor.

</td>
</tr>
</table>

### SDKs & Ecosystem

| Repo | Description |
|------|-------------|
| 🐍 [Shield Python SDK](https://github.com/joergmichno/clawguard-shield-python) | `pip install clawguard-shield` — scan any prompt in 3 lines. |
| 📦 [Shield JS SDK](https://github.com/joergmichno/clawguard-shield-js) | `npm install clawguard-shield` — zero deps, ESM+CJS+TS. |
| 🧪 [Prompt Lab](https://github.com/joergmichno/prompt-lab) | Interactive Prompt Injection Playground — [Live →](https://prompttools.co) |
| 📊 [Project Manager](https://github.com/joergmichno/project-manager) | Project dashboard with Gantt, Kanban & early warning system. |

### Security Research

- **MSRC researcher — Q2 2026 Leaderboard** (Microsoft Security Response Center)
- **Responsible disclosure** across major open-source MCP projects (Google genai-toolbox, Notion MCP, Laravel, n8n, GhidraMCP, git-mcp, XcodeBuildMCP and more), including maintainer-confirmed findings
- **Blog:** [16 articles](https://prompttools.co/blog) on prompt injection, MCP security, AI-agent supply chain
- **Registry Dashboard:** [11,529 MCP servers scanned](https://prompttools.co/registry) for security vulnerabilities

---

<div align="center">

*Building the security layer between AI agents and the real world.*

</div>
