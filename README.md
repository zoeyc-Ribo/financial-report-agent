# Annual Report Analysis Skill

A modular **Claude Code agent skill** that produces institutional-grade annual
report financial analyses (8–12 pages, 3,000–5,000 words) for public companies,
following professional equity-research standards.

This repository is a personal project demonstrating how to design a structured,
reliable, and source-disciplined LLM agent for a real analytical task. All
materials analyze **publicly available** company filings (10-K / 20-F / annual
reports / investor relations pages) only.

## What it does

Given a company and fiscal year, the agent researches the latest annual
materials and writes a structured DOCX research report covering:

- Year-over-year revenue, EPS, and margin performance
- Segment and geographic breakdowns
- Profitability and cash-flow / balance-sheet quality
- Management commentary and forward outlook
- Thesis update, valuation implications, and key risks
- 8–12 charts and 1–3 summary tables, with fully cited sources

## Why it's built this way

The design targets the three failure modes that matter most for financial
analysis with LLMs:

1. **Stale data.** A mandatory data-collection phase forces the agent to verify
   today's date and search for the *latest* filings instead of relying on
   training-data memory.
2. **Hallucination.** A strict no-fabrication rule and an explicit source
   hierarchy (earnings release → SEC filing → transcript → investor deck →
   consensus) keep every figure traceable. Missing data is labeled, never
   invented.
3. **Inconsistent output.** A fixed 5-phase workflow and page-by-page report
   template make the output structure repeatable across companies.

## Architecture

```
.
├── CLAUDE.md                          # Workspace-level rules and guardrails
├── commands/
│   └── annual-report.md               # Slash command: parses input, invokes the skill
└── skills/
    └── annual-report-analysis/
        ├── SKILL.md                   # Skill definition: scope, requirements, workflow
        └── references/
            ├── workflow.md            # 5-phase, step-by-step execution procedure
            ├── report-structure.md    # Page-by-page DOCX templates and formatting
            └── best-practices.md      # Quality checklist + good/bad examples
```

- **`CLAUDE.md`** sets global rules: timeliness, source hierarchy, no
  fabrication, citation standards, and the default report structure.
- **`commands/annual-report.md`** is the entry point — it parses the company
  and fiscal year, then hands off to the skill.
- **`SKILL.md`** is the core skill spec; the **`references/`** files hold the
  detailed workflow, output templates, and a comprehensive quality checklist.

## How to use

In a Claude Code environment, place these files in your project, then run the
command with a company and fiscal year, for example:

```
/annual-report Nike FY2024
```

The agent will collect the latest annual materials, run the analysis, generate
charts, and produce a DOCX report named like
`Nike_FY2024_Annual_Report_Analysis.docx`.

## Scope and limitations

- Designed for **annual** results (10-K / 20-F / annual reports), not quarterly
  flash notes or full initiation reports.
- Requires web access to public filings and investor-relations materials.
- Nothing in this report constitutes investment advice.

## License

MIT