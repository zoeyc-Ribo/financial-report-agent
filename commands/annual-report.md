---
description: Analyze an annual report and create a professional financial analysis report
argument-hint: "[company name or ticker] [fiscal year, e.g. FY2024 or 2024 annual report]"
---

# Annual Report Analysis Command

## Step 1: Parse Input

Extract from user input:
- Company name or ticker
- Fiscal year (e.g., FY2024, 2024 annual report)

If not provided, ask:
- "What company would you like to analyze?"
- "Which fiscal year? (e.g., FY2024)"

## Step 2: Execute

Use `skill: "annual-report-analysis"` to create the report.
Í
Follow ALL instructions in the skill, including:
- `references/workflow.md` for execution steps
- `references/report-structure.md` for formatting
- `references/best-practices.md` for quality checklist

## Step 3: Deliver

Provide the DOCX report and brief summary as specified in workflow.md Step 17.
