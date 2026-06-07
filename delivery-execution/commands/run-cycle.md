---
description: Orchestrate a delivery cycle from plan to retro.
argument-hint: "[the delivery cycle or sprint to orchestrate]"
---
# /run-cycle
Orchestrate one delivery cycle end to end.
## Steps
1. **Plan** — Break milestones into owned, dated work using `delivery-plan` skill.
2. **Surface risks** — Build the cycle's risk register using `risk-register` skill.
3. **Clear the path** — Triage blockers as they appear using `blocker-triage` skill.
4. **Close the loop** — Run the retro and capture actions using `retrospective` skill.
## Output
A run-cycle pack: delivery plan, risk register, blocker log, and a retro with owned actions.
Consider following up with `/readiness-review` as the cycle approaches launch.
