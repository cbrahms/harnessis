# ADR Writer Harness

An agent team harness for creating Architecture Decision Records (ADRs).

## Structure

```
.claude/
├── agents/
│   ├── context-analyst.md
│   ├── alternative-researcher.md
│   ├── tradeoff-evaluator.md
│   ├── adr-author.md
│   └── impact-tracker.md
├── skills/
│   ├── adr-writer/
│   │   └── SKILL.md              — Orchestrator
│   ├── quality-attribute-analyzer/
│   │   └── SKILL.md              — Quality attribute analysis (CAP theorem, weighted evaluation, ATAM)
│   └── madr-template-engine/
│       └── SKILL.md              — MADR format (ADR status management, numbering system, dependency graph)
└── CLAUDE.md                     — This file
```

## Usage

Trigger the `/adr-writer` skill, or make a natural language request.
