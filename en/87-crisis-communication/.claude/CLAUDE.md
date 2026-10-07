# Crisis Communication Harness

crisis situation occurrence when situationidentify→messagestrategy→press release→Q&A→monitoringto agent team to integration crisis package creation .

## structure

```
.claude/
├── agents/
│ ├── situation-analyst.md — situation analysis (companyactualtotal, stakeholder, crisisetc.grade)
│ ├── message-strategist.md — message strategy (coremessage, tone, channelstrategy)
│ ├── press-release-writer.md — press release writing (officialdocument, timeline)
│ ├── qa-preparer.md — Q&A preparation (expectedquestion, answerguide, when)
│ └── media-monitor.md — media monitoring (tracking, riskdegree, afterwithinresponse)
├── skills/
│ ├── crisis-communication/
│ │ └── SKILL.md — Orchestrator (team , workflow, error handling)
│ ├── stakeholder-mapping/
│ │ └── SKILL.md — stakeholder mapping framework (situation-analyst extension)
│ └── media-response-templates/
│ └── SKILL.md — media response template (press-release-writer extension)
└── CLAUDE.md — file
```

## usage

`/crisis-communication` skill , "crisis response communication preparationplease do" specialistannual request.

## deliverable

all deliverable `_workspace/` save:
- `00_input.md` — user input organization
- `01_situation_analysis.md` — situation analysis report
- `02_message_strategy.md` — message strategyfrom
- `03_press_release.md` — press release/official document
- `04_qa_briefing.md` — Q&A when
- `05_monitoring_plan.md` — monitoring plan and afterwithin response guide
