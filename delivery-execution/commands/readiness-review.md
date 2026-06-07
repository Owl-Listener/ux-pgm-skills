---
description: Run a launch readiness review.
argument-hint: "[the launch or release to assess]"
---
# /readiness-review
Run a structured go/no-go review.
## Steps
1. **Verify readiness** — Walk every domain against exit criteria using `launch-readiness` skill.
2. **Score residual risk** — Assess what's still open using `risk-register` skill.
3. **Clear final blockers** — Drive remaining gaps to closure using `blocker-triage` skill.
## Output
A readiness report with a go / no-go / conditional-go call and an owned gap list.
Consider following up with `/run-cycle` to plan any fast-follow work.
