# Report Generator Harness

work report datacollection→analysis→visualization→→summary A harness where an agent team collaborates to produce deliverables.

## structure

```
.claude/
├── agents/
│ ├── data-collector.md — data collection ( , figure , refinement)
│ ├── analyst.md — data analysis (statistics, trend, insight derive)
│ ├── visualizer.md — visualization design (chart, , infographic peopletax)
│ ├── report-writer.md — report (structuredone report writing)
│ └── executive-summarizer.md — summary and cross-verification (core summary, consistency confirm)
├── skills/
│ ├── report-generator/
│ │ └── SKILL.md — Orchestrator (team , workflow, error handling)
│ ├── data-visualization-guide/
│ │ └── SKILL.md — data visualization guide (visualizer extension)
│ └── kpi-dashboard-patterns/
│ └── SKILL.md — KPI dashboard design pattern (analyst extension)
└── CLAUDE.md — file
```

## usage

`/report-generator` skill , "work report create it" specialistannual request.

## deliverable

all deliverable `_workspace/` save:
- `00_input.md` — user input organization
- `01_data_collection.md` — collectiondone data organization
- `02_analysis_report.md` — analysis result
- `03_visualization_spec.md` — visualization peopletax
- `04_full_report.md` — final report
- `05_executive_summary.md` — management summary and verify reporting
