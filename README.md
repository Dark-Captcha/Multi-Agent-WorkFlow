# Multi-Agent-WorkFlow

> Multi-agent protocol for AI-assisted development with 14 specialized agents, workflow phases, and multi-language coding standards.

## Overview

A universal multi-agent system where **14 specialized agents** work together like a company team. Each agent has **one job** and they **criticize each other** to catch errors.

## Documents

| Document                                           | Description                                           |
| -------------------------------------------------- | ----------------------------------------------------- |
| [AGENTS.md](AGENTS.md)                             | 14-agent protocol with roles, handoffs, and workflows |
| [AI-WORKFLOW.md](AI-WORKFLOW.md)                   | Workflow phases: Analyze → Plan → Implement           |
| [languages/RUST.md](languages/RUST.md)             | Rust coding standards                                 |
| [languages/TYPESCRIPT.md](languages/TYPESCRIPT.md) | TypeScript coding standards                           |

## Agents

| Agent          | Role              | One Job              |
| -------------- | ----------------- | -------------------- |
| `@clarifier`   | Business Analyst  | Vague → Specific     |
| `@researcher`  | Research Analyst  | Deep dive knowledge  |
| `@logic`       | Algorithm Analyst | Trace code flow      |
| `@commander`   | CEO               | Final decisions      |
| `@planner`     | Technical PM      | Feature → Tasks      |
| `@tracker`     | Project Manager   | Track progress       |
| `@architect`   | CTO               | Design systems       |
| `@implementer` | Senior Dev        | Write new code       |
| `@refactorer`  | Staff Engineer    | Improve existing     |
| `@reviewer`    | QA Lead           | Approve/Reject       |
| `@tester`      | QA Engineer       | Write tests          |
| `@security`    | Security Engineer | Find vulnerabilities |
| `@debugger`    | SRE               | Fix bugs             |
| `@documenter`  | Tech Writer       | Write docs           |

## Workflow

```
ANALYZE ──► PLAN ──► IMPLEMENT ──► DONE
```

Each phase requires explicit user approval before proceeding.

## Usage

Copy the protocol files to your project root:

```bash
cp AGENTS.md AI-WORKFLOW.md -r languages/ /path/to/your/project/
```

Configure your AI assistant to read these files as system context.

## License

MIT License - see [LICENSE](LICENSE)
