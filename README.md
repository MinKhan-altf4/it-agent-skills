# IT Agent Skills

Reusable specialist instructions for AI coding agents and IT workflows.

## Purpose

This repository provides a collection of focused AI skills for software development, system design, databases, data science, machine learning, and DevOps.

Each skill is maintained as a standalone `SKILL.md` using the Agent Skills format.

## Available skills

| Skill | Intended use |
|---|---|
| `system-architect` | Requirements, system architecture, APIs, UML, and technical trade-offs |
| `software-engineer` | Implementation, debugging, refactoring, testing, and code review |
| `database-architect` | Data modeling, SQL, integrity, and query performance |
| `data-scientist` | Data cleaning, statistics, experiments, and insights |
| `ai-ml-engineer` | Machine learning pipelines, training, evaluation, and deployment |
| `devops-engineer` | CI/CD, containers, infrastructure, and observability |

## Repository structure

```text
skills/
├── system-architect/SKILL.md
├── software-engineer/SKILL.md
├── database-architect/SKILL.md
├── data-scientist/SKILL.md
├── ai-ml-engineer/SKILL.md
└── devops-engineer/SKILL.md
```

## Installation

Install the skills using the open-source Skills CLI:

```bash
npx skills add YOUR_GITHUB_USERNAME/it-agent-skills
```

To install all skills for all supported agents:

```bash
npx skills add YOUR_GITHUB_USERNAME/it-agent-skills --all
```

Replace `YOUR_GITHUB_USERNAME` with the GitHub account or organization that owns this repository.

Compatibility depends on the AI client and its support for Agent Skills.

## Design principles

- One source of truth.
- Small, focused, reusable skills.
- Clear activation descriptions.
- Evidence-based recommendations.
- Maintainability, security, and testability.
- No unsupported claims about real-world credentials or experience.

## License

See `LICENSE` for usage terms.