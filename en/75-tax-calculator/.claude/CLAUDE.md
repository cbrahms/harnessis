# Tax Calculator Harness

A tax calculation agent team harness.

## Structure

```
.claude/
├── agents/
│   ├── income-analyst.md
│   ├── deduction-optimizer.md
│   ├── tax-engine.md
│   └── strategy-advisor.md
├── skills/
│   ├── tax-calculator/
│   │   └── SKILL.md              — Orchestrator
│   ├── tax-bracket-simulator/
│   │   └── SKILL.md              — Tax bracket simulator (progressive rates, effective rate calculation, bracket optimization)
│   └── deduction-optimizer-engine/
│       └── SKILL.md              — Deduction optimizer engine (deduction catalog, eligibility checker, savings calculator)
└── CLAUDE.md                     — This file
```

## Usage

Trigger the `/tax-calculator` skill, or make a natural language request.
