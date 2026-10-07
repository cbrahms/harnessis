# Research Assistant Harness

An agent team harness for academic research assistance.

## Structure

```
.claude/
├── agents/
│   ├── literature-searcher.md
│   ├── note-taker.md
│   ├── critic-synthesizer.md
│   ├── reference-manager.md
│   └── research-coordinator.md
├── skills/
│   ├── research-assistant/
│   │   └── SKILL.md              — Orchestrator
│   ├── systematic-review-protocol/
│   │   └── SKILL.md              — Systematic review (PRISMA, PICO, Boolean search)
│   └── citation-formatter/
│       └── SKILL.md              — Citation format conversion (APA/MLA/Chicago, BibTeX)
└── CLAUDE.md                     — This file
```

## Usage

Trigger the `/research-assistant` skill, or make a natural language request.
