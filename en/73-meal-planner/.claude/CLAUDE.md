# Meal Planner Harness

A meal planning agent team harness.

## Structure

```
.claude/
├── agents/
│   ├── nutritionist.md
│   ├── meal-designer.md
│   ├── recipe-writer.md
│   └── shopping-coordinator.md
├── skills/
│   ├── meal-planner/
│   │   └── SKILL.md              — Orchestrator
│   ├── nutrition-calculator/
│   │   └── SKILL.md              — Nutrition calculator (macro/micronutrients, daily intake, meal balance)
│   └── ingredient-substitution-engine/
│       └── SKILL.md              — Ingredient substitution engine (allergy alternatives, seasonal swaps, budget options)
└── CLAUDE.md                     — This file
```

## Usage

Trigger the `/meal-planner` skill, or make a natural language request.
