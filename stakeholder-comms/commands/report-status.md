---
description: Generate a full status update for the program.
argument-hint: "[program name and reporting period]"
---
# /report-status
Produce a complete, audience-ready status update.
## Steps
1. **Audience** — Identify who's reading and their currency using `stakeholder-map` skill.
2. **Core report** — Draft RAG, progress, risks, asks using `status-report` skill.
3. **Exec layer** — Distil a one-screen version using `executive-update` skill.
4. **Escalations** — Flag anything that needs to move up using `escalation-plan` skill.
## Output
A layered status update: a full report and an executive summary, with any escalations called out.
Consider following up with `/align-stakeholders` if the report surfaces disagreement.
