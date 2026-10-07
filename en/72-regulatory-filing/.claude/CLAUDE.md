# Regulatory Filing Harness

A regulatory filing and permit application agent team harness.

## Structure

```
.claude/
├── agents/
│   ├── requirements-investigator.md
│   ├── document-drafter.md
│   ├── attachment-preparer.md
│   └── submission-verifier.md
├── skills/
│   ├── regulatory-filing/
│   │   └── SKILL.md              — Orchestrator
│   ├── permit-requirements-db/
│   │   └── SKILL.md              — Permit requirements database (filing types, required documents, processing timelines)
│   └── form-filling-guide/
│       └── SKILL.md              — Form filling guide (field-by-field instructions, common mistakes, example entries)
└── CLAUDE.md                     — This file
```

## Usage

Trigger the `/regulatory-filing` skill, or make a natural language request.
