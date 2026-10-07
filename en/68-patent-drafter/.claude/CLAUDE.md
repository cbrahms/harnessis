# Patent Drafter Harness

A patent application drafting agent team harness.

## Structure

```
.claude/
├── agents/
│   ├── prior-art-researcher.md
│   ├── claim-drafter.md
│   ├── specification-writer.md
│   ├── drawing-designer.md
│   └── patent-reviewer.md
├── skills/
│   ├── patent-drafter/
│   │   └── SKILL.md              — Orchestrator
│   ├── claim-drafting-patterns/
│   │   └── SKILL.md              — Claim drafting patterns (Jepson/Markush/means-plus-function, dependent claim strategies)
│   └── prior-art-search-strategy/
│       └── SKILL.md              — Prior art search strategy (patent DB search, classification codes, citation analysis)
└── CLAUDE.md                     — This file
```

## Usage

Trigger the `/patent-drafter` skill, or make a natural language request.
